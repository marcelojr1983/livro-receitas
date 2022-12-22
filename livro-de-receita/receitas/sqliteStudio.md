insert into funcionarios(nome, cidade, cpf, telefone, estado)
values ("edilson","salvador","132.456.789-00","11 9973-55014","sp");

select * from funcionarios

select *
from funcionarios
where estado="sp";

create table livros (codigo int, nome text, categoria text, resumo text, precocusto number, precovenda number);

insert into livros (codigo,nome,precocusto)
values (1,"A arte da Guerra",6);

select nome, categoria
from livros
where codigo=1;

select nome,cidade
from alunos
where codigo=1;

select nome, categoria
from livros
where codigo=3;

drop table livros;

alter table alunos rename to estudantes;

alter table estudantes add estado text;

select * from estudantes

select nome from funcionarios order by nome;

select nome from estudantes order by nome;

select * from fornecedores2;

select nome from fornecedores2 order by nome;

select nome from estudantes order by nome;

select nome from estudantes order by nome desc;

select nome,telefone from estudantes;

select nome,telefone from estudantes order by telefone;

select nome,telefone from estudantes order by telefone desc;

create table produtos (codigo, nomeproduto);

select * from produtos;

create table produtos (codigo int, nomeproduto text);

select * from produtos;

alter table produtos add (codigo,nomeproduto 