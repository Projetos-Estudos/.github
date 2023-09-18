# GQS-A3

Este é um projeto acadêmico desenvolvido em Java.

# Sumário

* [Sobre](#gqs-a3)
* [Sumário](#sumário)
* [Características](#características)
* [Requisitos](#requisitos)
* [Tecnologias](#tecnologias)
* [Instalação](#instalação)
* [Licença](#licença)

## Características

- MVC
- CRUD
- Login

## Requisitos

- Java JDK 1.8
- MySql >= 5.1.47

## Tecnologias

- Java
- MySql

## Instalação

```
$ git clone gh repo clone Projetos-Estudos/GQS-A3

```

Crie um banco de dados com o nome "cbdata_gqs_a3" no seu Mysql. Execute o seguinte script no MySql da seguinte forma:

```
CREATE DATABASE IF NOT EXISTS cbdata_gqs_a3;

USE cbdata_gqs_a3;

CREATE TABLE IF NOT EXISTS USUARIO
(
    COD_USUARIO INT UNSIGNED AUTO_INCREMENT NOT NULL,
    NOM_ACESSO VARCHAR(50) NOT NULL,
    NOM_USUARIO VARCHAR(180) NOT NULL,
    SENHA_USUARIO VARCHAR(20) NOT NULL,
    DSC_EMAIL VARCHAR(40),
    DSC_OBSERVACAO VARCHAR(200),
    PRIMARY KEY (COD_USUARIO)
);

INSERT INTO USUARIO (NOM_ACESSO, NOM_USUARIO, SENHA_USUARIO, DSC_EMAIL, DSC_OBSERVACAO)
VALUES 
    ('Admin', 'Administrador', '123', 'admin@example.com', 'Observação para o Admin'),
    ('User1', 'Teste Usuario', 'teste@123', 'user1@example.com', 'Observação para o User1');

```

A conexão com o banco é gerenciada pela classe `ConexaoDAO`. Se você encontrar algum erro na integração com o banco de dados, recomenda-se verificar esta classe para identificar possíveis problemas.
https://github.com/gustagt
https://github.com/nadine-e-pereira

# Autores
<table>
  <tr>
    <td align="center"><a href=""><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/90219219?v=4" width="100px;" alt=""/><br /><sub><b>Breno</b></sub></a><br /><a href="" title="Breno"></a></td>
    <td align="center"><a href="https://github.com/troxx10"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/134012902?v=4" width="100px;" alt=""/><br /><sub><b>Gabriel Rocha</b></sub></a><br /><a href="https://github.com/troxx10" title="Gabriel Rocha"></a></td>
    <td align="center"><a href="https://github.com/gustagt"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/88049338?v=4" width="100px;" alt=""/><br /><sub><b>Gustavo Silva</b></sub></a><br /><a href="https://github.com/gustagt" title="Gustavo Silva"></a></td>
    <td align="center"><a href="https://github.com/ErickVieitas"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/90138559?v=4" width="100px;" alt=""/><br /><sub><b>Erick Lopes</b></sub></a><br /><a href="https://github.com/ErickVieitas" title="Erick Lopes"></a></td>
    <td align="center"><a href="https://github.com/nadine-e-pereira"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/81249310?v=4" width="100px;" alt=""/><br /><sub><b>Nadine Pereira</b></sub></a><br /><a href="https://github.com/nadine-e-pereira" title="Nadine Pereira"></a></td>
  </tr>
</table>

## Licença

Projeto licenciado sob <a href="LICENSE">The MIT License (MIT)</a>.

# Agradecimentos

Em Desenvolvimento...
