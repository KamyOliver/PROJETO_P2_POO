# RPG Java com PostgreSQL

## Descrição

Projeto desenvolvido em Java utilizando Programação Orientada a Objetos (POO) e integração com PostgreSQL via JDBC.

O sistema simula um jogo de RPG contendo personagens com comportamentos distintos, sistema de inventário, aprendizado de músicas e duelos entre personagens.

## Tecnologias Utilizadas

* Java 17
* PostgreSQL
* JDBC
* Programação Orientada a Objetos

## Funcionalidades

* Sistema de personagens (Caçador e Bardo)
* Herança e polimorfismo
* Inventário de itens
* Sistema de duelos
* Aprendizado de músicas
* Integração com banco de dados PostgreSQL

## Requisitos

* Java 17 ou superior
* PostgreSQL
* Driver JDBC PostgreSQL

## Configuração do Banco

Criar o banco de dados:

```sql
CREATE DATABASE jogo_db;
```

Criar a tabela:

```sql
CREATE TABLE tb_musica(
    faixa SERIAL PRIMARY KEY,
    titulo VARCHAR(255)
);
```

Popular a tabela com músicas conforme o arquivo `ScriptMusica.sql`.

## Observação

O projeto depende do driver JDBC do PostgreSQL para execução completa. Certifique-se de adicionar o arquivo `postgresql-42.x.x.jar` ao classpath antes de executar a aplicação.

## Integrantes

* Kamily Carvalho de Oliveira
* Michel Pablo dos Santos Ferreira Silva
* Rafael Kenzo Sato Bezerra

