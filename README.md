# SQL-DDL-DML-Locadora

![image](https://github.com/DaviQzR/SQL-DDL-DML-Locadora/assets/125469425/d8150fe4-5162-4827-b551-6ad9dff56712)

N – atributo NULL

Restrições:
Ano de filme deve ser menor ou igual a 2021
Data de fabricação de DVD deve ser menor do que hoje
Número do endereço de Cliente deve ser positivo
CEP do endereço de Cliente deve ter, especificamente, 8 caracteres
Data de locação de Locação, por padrão, deve ser hoje
Data de devolução de Locação, deve ser maior que a data de locação
Valor de Locação deve ser positivo

Esquema:
A entidade estrela deveria ter o nome real da estrela, com 50 caracteres
Verificando um dos nomes de filme, percebeu-se que o nome do filme deveria ser um atributo
com 80 caracteres

Considere os dados:


![image](https://github.com/DaviQzR/SQL-DDL-DML-Locadora/assets/125469425/03dfd0d1-e3a5-4594-8a93-6d536099ff95)


![image](https://github.com/DaviQzR/SQL-DDL-DML-Locadora/assets/125469425/264a8d29-58e9-47fc-a465-de7d9b1171f8)

![image](https://github.com/DaviQzR/SQL-DDL-DML-Locadora/assets/125469425/68f6f541-74f8-46ce-90e8-e90aac9026f2)

Operações com dados:

--> Os CEP dos clientes 5503 e 5504 são 08411150 e 02918190 respectivamente

--> A locação de 2021-02-18 do cliente 5502 teve o valor de 3.25 para cada DVD alugado

--> A locação de 2021-02-24 do cliente 5501 teve o valor de 3.10 para cada DVD alugado

--> O DVD 10005 foi fabricado em 2019-07-14

--> O nome real de Miles Teller é Miles Alexander Teller

--> O filme Sing não tem DVD cadastrado e deve ser excluído

Consultar:

1) Fazer um select que retorne os nomes dos filmes de 2014
2) Fazer um select que retorne o id e o ano do filme Birdman
3) Fazer um select que retorne o id e o ano do filme que tem o nome terminado por
plash
4) Fazer um select que retorne o id, o nome e o nome_real da estrela cujo nome começa
com Steve
5) Fazer um select que retorne FilmeId e a data_fabricação em formato (DD/MM/YYYY)
(apelidar de fab) dos filmes fabricados a partir de 01-01-2020
6) Fazer um select que retorne DVDnum, data_locacao, data_devolucao, valor e valor
com multa de acréscimo de 2.00 da locação do cliente 5505
7) Fazer um select que retorne Logradouro, num e CEP de Matilde Luz
8) Fazer um select que retorne Nome real de Michael Keaton
9) Fazer um select que retorne o num_cadastro, o nome e o endereço completo,
concatenando (logradouro, numero e CEP), apelido end_comp, dos clientes cujo ID é
maior ou igual 5503




