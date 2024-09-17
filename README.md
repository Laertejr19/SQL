-- Criar banco de dados
create database AULABANCOJUNTO;

-- Escolher o banco que ira usar
use AULABANCOJUNTO;

-- Criar tabela
create table tbseriea(
id_clube int primary key,
clube varchar(50) not null,
login varchar(50) not null unique,
senha varchar(15) not null
);

describe tbseriea;

-- Inserir dados na tabela(create)
insert into tbseriea(id_clube, clube, login, senha)
values(1, 'Bota Fogo', 'botafogo', '1');

-- Inserir dados na tabela(create)
insert into tbseriea(id_clube, clube, login, senha)
values(2, 'Palmeiras', 'palmeiras', '12');

-- Inserir dados na tabela(create)
insert into tbseriea(id_clube, clube, login, senha)
values(3, 'Fortaleza', 'fortaleza', '123');

-- Inserir dados na tabela(create)
insert into tbseriea(id_clube, clube, login, senha)
values(4, 'Flamengo', 'flamengo', '1234');

-- Inserir dados na tabela(create)
insert into tbseriea(id_clube, clube, login, senha)
values(5, 'São Paulo', 'saopaulo', '12345');

-- Inserir dados na tabela(create)
insert into tbseriea(id_clube, clube, login, senha)
values(6, 'Bahia', 'bahia', '123456');

-- Inserir dados na tabela(create)
insert into tbseriea(id_clube, clube, login, senha)
values(7, 'Cruzeiro', 'cruzeiro', '1234567');

-- Inserir dados na tabela(create)
insert into tbseriea(id_clube, clube, login, senha)
values(8, 'Internacional', 'internacional', '12345678');

-- Inserir dados na tabela(create)
insert into tbseriea(id_clube, clube, login, senha)
values(9, 'Vasco da Gama', 'vascodagama', '123456789');

-- Inserir dados na tabela(create)
insert into tbseriea(id_clube, clube, login, senha)
values(10, 'Atlético MG', 'atleticomg', '12345678910');

select * from tbseriea;

-- editar itens da tabela(update)
update tbseriea set clube = 'Edit1' where id_clube = 1;
update tbseriea set clube = 'Edit2' where id_clube = 2;
update tbseriea set clube = 'Edit3' where id_clube = 3;
update tbseriea set clube = 'Edit4' where id_clube = 4;
update tbseriea set clube = 'Edit5' where id_clube = 5;
update tbseriea set clube = 'Edit6' where id_clube = 6;
update tbseriea set clube = 'Edit7' where id_clube = 7;
update tbseriea set clube = 'Edit8' where id_clube = 8;
update tbseriea set clube = 'Edit9' where id_clube = 9;
update tbseriea set clube = 'Edit10' where id_clube = 10;

-- excluir um item da tabela(delete)
delete from tbseriea where id_clube = 1;
-- excluir um item da tabela(delete)
delete from tbseriea where id_clube = 2;
-- excluir um item da tabela(delete)
delete from tbseriea where id_clube = 3;
-- excluir um item da tabela(delete)
delete from tbseriea where id_clube = 4;
-- excluir um item da tabela(delete)
delete from tbseriea where id_clube = 5;

-- Criar tabela
create table tbserieb(
id_clube int primary key,
clube varchar(50) not null,
login varchar(50) not null unique,
senha varchar(15) not null
);

describe tbserieb;

-- Inserir dados na tabela(create)
insert into tbserieb(id_clube, clube, login, senha)
values(1, 'Novorizontino', 'novorizontino', '1');

-- Inserir dados na tabela(create)
insert into tbserieb(id_clube, clube, login, senha)
values(2, 'Santos', 'santos', '12');

-- Inserir dados na tabela(create)
insert into tbserieb(id_clube, clube, login, senha)
values(3, 'Mirassol', 'mirassol', '123');

-- Inserir dados na tabela(create)
insert into tbserieb(id_clube, clube, login, senha)
values(4, 'Sport Recife', 'sportrecife', '1234');

-- Inserir dados na tabela(create)
insert into tbserieb(id_clube, clube, login, senha)
values(5, 'Vila Nova', 'vilanova', '12345');

-- Inserir dados na tabela(create)
insert into tbserieb(id_clube, clube, login, senha)
values(6, 'Ceará SC', 'cearasc', '123456');

-- Inserir dados na tabela(create)
insert into tbserieb(id_clube, clube, login, senha)
values(7, 'América MG', 'americamg', '1234567');

-- Inserir dados na tabela(create)
insert into tbserieb(id_clube, clube, login, senha)
values(8, 'Avaí', 'avai', '12345678');

-- Inserir dados na tabela(create)
insert into tbserieb(id_clube, clube, login, senha)
values(9, 'Goiás', 'goias', '123456789');

-- Inserir dados na tabela(create)
insert into tbserieb(id_clube, clube, login, senha)
values(10, 'Operário', 'operario', '12345678910');

select * from tbserieb;

-- editar itens da tabela(update)
update tbserieb set clube = 'Edit1' where id_clube = 1;
update tbserieb set clube = 'Edit2' where id_clube = 2;
update tbserieb set clube = 'Edit3' where id_clube = 3;
update tbserieb set clube = 'Edit4' where id_clube = 4;
update tbserieb set clube = 'Edit5' where id_clube = 5;
update tbserieb set clube = 'Edit6' where id_clube = 6;
update tbserieb set clube = 'Edit7' where id_clube = 7;
update tbserieb set clube = 'Edit8' where id_clube = 8;
update tbserieb set clube = 'Edit9' where id_clube = 9;
update tbserieb set clube = 'Edit10' where id_clube = 10;

-- excluir um item da tabela(delete)
delete from tbserieb where id_clube = 1;
-- excluir um item da tabela(delete)
delete from tbserieb where id_clube = 2;
-- excluir um item da tabela(delete)
delete from tbserieb where id_clube = 3;
-- excluir um item da tabela(delete)
delete from tbserieb where id_clube = 4;
-- excluir um item da tabela(delete)
delete from tbserieb where id_clube = 5;

-- Criar tabela
create table tbseriec(
id_clube int primary key,
clube varchar(50) not null,
login varchar(50) not null unique,
senha varchar(15) not null
);

describe tbseriec;

-- Inserir dados na tabela(create)
insert into tbseriec(id_clube, clube, login, senha)
values(1, 'Volta Redonda', 'voltaredonda', '1');

-- Inserir dados na tabela(create)
insert into tbseriec(id_clube, clube, login, senha)
values(2, 'Remo', 'remo', '12');

-- Inserir dados na tabela(create)
insert into tbseriec(id_clube, clube, login, senha)
values(3, 'São Bernardo', 'saobernardo', '123');

-- Inserir dados na tabela(create)
insert into tbseriec(id_clube, clube, login, senha)
values(4, 'Bota Fogo PB', 'botafogopb', '1234');

-- Inserir dados na tabela(create)
insert into tbseriec(id_clube, clube, login, senha)
values(5, 'Ferroviária', 'ferroviaria', '12345');

-- Inserir dados na tabela(create)
insert into tbseriec(id_clube, clube, login, senha)
values(6, 'Athletic', 'athletic', '123456');

-- Inserir dados na tabela(create)
insert into tbseriec(id_clube, clube, login, senha)
values(7, 'Ypiranga', 'ypiranga', '1234567');

-- Inserir dados na tabela(create)
insert into tbseriec(id_clube, clube, login, senha)
values(8, 'Londrina', 'londrina', '12345678');

-- Inserir dados na tabela(create)
insert into tbseriec(id_clube, clube, login, senha)
values(9, 'Time A', 'timea', '123456789');

-- Inserir dados na tabela(create)
insert into tbseriec(id_clube, clube, login, senha)
values(10, 'Time B', 'timeb', '12345678910');

select * from tbseriec;

-- editar itens da tabela(update)
update tbseriec set clube = 'Edit1' where id_clube = 1;
update tbseriec set clube = 'Edit2' where id_clube = 2;
update tbseriec set clube = 'Edit3' where id_clube = 3;
update tbseriec set clube = 'Edit4' where id_clube = 4;
update tbseriec set clube = 'Edit5' where id_clube = 5;
update tbseriec set clube = 'Edit6' where id_clube = 6;
update tbseriec set clube = 'Edit7' where id_clube = 7;
update tbseriec set clube = 'Edit8' where id_clube = 8;
update tbseriec set clube = 'Edit9' where id_clube = 9;
update tbseriec set clube = 'Edit10' where id_clube = 10;

-- excluir um item da tabela(delete)
delete from tbseriec where id_clube = 1;
-- excluir um item da tabela(delete)
delete from tbseriec where id_clube = 2;
-- excluir um item da tabela(delete)
delete from tbseriec where id_clube = 3;
-- excluir um item da tabela(delete)
delete from tbseriec where id_clube = 4;
-- excluir um item da tabela(delete)
delete from tbseriec where id_clube = 5;

-- Criar tabela
create table tbseried(
id_clube int primary key,
clube varchar(50) not null,
login varchar(50) not null unique,
senha varchar(15) not null
);

describe tbseried;

-- Inserir dados na tabela(create)
insert into tbseried(id_clube, clube, login, senha)
values(1, 'Manauara EC', 'manauaraec', '1');

-- Inserir dados na tabela(create)
insert into tbseried(id_clube, clube, login, senha)
values(2, 'Porto Velho', 'portovelho', '12');

-- Inserir dados na tabela(create)
insert into tbseried(id_clube, clube, login, senha)
values(3, 'Princesa', 'princesa', '123');

-- Inserir dados na tabela(create)
insert into tbseried(id_clube, clube, login, senha)
values(4, 'Manaus', 'manaus', '1234');

-- Inserir dados na tabela(create)
insert into tbseried(id_clube, clube, login, senha)
values(5, 'Trem', 'trem', '12345');

-- Inserir dados na tabela(create)
insert into tbseried(id_clube, clube, login, senha)
values(6, 'São Raimundo', 'saoraimundo', '123456');

-- Inserir dados na tabela(create)
insert into tbseried(id_clube, clube, login, senha)
values(7, 'Rio Branco', 'riobranco', '1234567');

-- Inserir dados na tabela(create)
insert into tbseried(id_clube, clube, login, senha)
values(8, 'Humaitá', 'humaita', '12345678');

-- Inserir dados na tabela(create)
insert into tbseried(id_clube, clube, login, senha)
values(9, 'Maranhão', 'maranhao', '123456789');

-- Inserir dados na tabela(create)
insert into tbseried(id_clube, clube, login, senha)
values(10, 'Altos', 'altos', '12345678910');

select * from tbseried;

-- editar itens da tabela(update)
update tbseried set clube = 'Edit1' where id_clube = 1;
update tbseried set clube = 'Edit2' where id_clube = 2;
update tbseried set clube = 'Edit3' where id_clube = 3;
update tbseried set clube = 'Edit4' where id_clube = 4;
update tbseried set clube = 'Edit5' where id_clube = 5;
update tbseried set clube = 'Edit6' where id_clube = 6;
update tbseried set clube = 'Edit7' where id_clube = 7;
update tbseried set clube = 'Edit8' where id_clube = 8;
update tbseried set clube = 'Edit9' where id_clube = 9;
update tbseried set clube = 'Edit10' where id_clube = 10;

-- excluir um item da tabela(delete)
delete from tbseried where id_clube = 1;
-- excluir um item da tabela(delete)
delete from tbseried where id_clube = 2;
-- excluir um item da tabela(delete)
delete from tbseried where id_clube = 3;
-- excluir um item da tabela(delete)
delete from tbseried where id_clube = 4;
-- excluir um item da tabela(delete)
delete from tbseried where id_clube = 5;

-- Criar tabela
create table tbseriegauchao(
id_clube int primary key,
clube varchar(50) not null,
login varchar(50) not null unique,
senha varchar(15) not null
);

describe tbseriegauchao;

-- Inserir dados na tabela(create)
insert into tbseriegauchao(id_clube, clube, login, senha)
values(1, 'Internacional', 'internacional', '1');

-- Inserir dados na tabela(create)
insert into tbseriegauchao(id_clube, clube, login, senha)
values(2, 'Grêmio', 'gremio', '12');

-- Inserir dados na tabela(create)
insert into tbseriegauchao(id_clube, clube, login, senha)
values(3, 'Caxias', 'caxias', '123');

-- Inserir dados na tabela(create)
insert into tbseriegauchao(id_clube, clube, login, senha)
values(4, 'Guarany', 'guarany', '1234');

-- Inserir dados na tabela(create)
insert into tbseriegauchao(id_clube, clube, login, senha)
values(5, 'Juventude', 'juventude', '12345');

-- Inserir dados na tabela(create)
insert into tbseriegauchao(id_clube, clube, login, senha)
values(6, 'São José', 'saojose', '123456');

-- Inserir dados na tabela(create)
insert into tbseriegauchao(id_clube, clube, login, senha)
values(7, 'Brasil de Pelotas', 'brasildepelotas', '1234567');

-- Inserir dados na tabela(create)
insert into tbseriegauchao(id_clube, clube, login, senha)
values(8, 'São Luiz', 'saoluiz', '12345678');

-- Inserir dados na tabela(create)
insert into tbseriegauchao(id_clube, clube, login, senha)
values(9, 'Ypiranga', 'ypiranga', '123456789');

-- Inserir dados na tabela(create)
insert into tbseriegauchao(id_clube, clube, login, senha)
values(10, 'Avenida', 'avenida', '12345678910');

select * from tbseriegauchao;

-- editar itens da tabela(update)
update tbseriegauchao set clube = 'Edit1' where id_clube = 1;
update tbseriegauchao set clube = 'Edit2' where id_clube = 2;
update tbseriegauchao set clube = 'Edit3' where id_clube = 3;
update tbseriegauchao set clube = 'Edit4' where id_clube = 4;
update tbseriegauchao set clube = 'Edit5' where id_clube = 5;
update tbseriegauchao set clube = 'Edit6' where id_clube = 6;
update tbseriegauchao set clube = 'Edit7' where id_clube = 7;
update tbseriegauchao set clube = 'Edit8' where id_clube = 8;
update tbseriegauchao set clube = 'Edit9' where id_clube = 9;
update tbseriegauchao set clube = 'Edit10' where id_clube = 10;

-- excluir um item da tabela(delete)
delete from tbseriegauchao where id_clube = 1;
-- excluir um item da tabela(delete)
delete from tbseriegauchao where id_clube = 2;
-- excluir um item da tabela(delete)
delete from tbseriegauchao where id_clube = 3;
-- excluir um item da tabela(delete)
delete from tbseriegauchao where id_clube = 4;
-- excluir um item da tabela(delete)
delete from tbseriegauchao where id_clube = 5;
