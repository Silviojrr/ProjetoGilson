use cadastrodeusuario;
create table usuario(
id int not null auto_increment,
nome varchar(20) not null,
numero int not null,
email varchar (30) not null,
senha varchar (8) not null,
primary key (id)
);