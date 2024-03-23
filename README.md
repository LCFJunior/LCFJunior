## *SQL Server 🪑* 

ㅤDuring the course and development of my project, the database that best suited my programming methodology was *SQL SERVER*, having fitted perfectly into *BACKEND* programming in *JAVASCRIPT*. Using *SQLSERVER* models, you can model extensive databases and manage them through related or unrelated tables, facilitating organization and operation.
##
*EXAMPLE...*
```SQL
CREATE TABLE usuario (
    id_usuario INT IDENTITY(1,1) PRIMARY KEY,
    Nome VARCHAR(255) NOT NULL,
    CPF CHAR(11) UNIQUE NOT NULL, -- CPF com exatamente 11 caracteres, apenas números
    DataNascimento DATE NOT NULL,
    Endereco VARCHAR(255) NOT NULL,
    Email VARCHAR(255),
    Senha VARCHAR(255) NOT NULL
);
```
