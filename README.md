# Java-MySQL 📖📈
<h2>Java MySQL - Sistema Completo - Relacionamento de Tabelas.</h2>

Nessa página do livro de conhecimentos que estou adquirindo, vou avançando um pouco mais no Java e no MySQL. Onde será exercitado 
o conhecimento no Java e na criação de um banco de dados que será consumido pela aplicação desenvolvida.

<h3>Nesse Readme irei documentar os passos do aprendizado</h3>

Passo para a criação de uma tabela:

Comando que cria um banco de dados -> **create database (nome da tabela);**

comando que escolhe o banco de dados -> **use (nome da tabela);**

Bloco de instruções que cria uma tabela: 
**create table (nome da tabela)(
iduser int primary key,
usuario varchar (xxxx) not null,
fone varchar (xxxx),
login varchar (xxxx) not null unique,
senha varchar (xxxx) not null
);**

**O not null é usuado quando o campo deva ter preenchimento obrigatório.**

Os comandos que descrevem a tabela: **describe (nome da tabela); e desc tbusuarios;**

<h2>CRUD</h2>
<h3>create -> Insert</h3>
<h3>read -> select</h3>
<h3>update -> update</h3>
<h3>delete -> delete</h3>






