## *SQL Server 🪑* 

ㅤAo decorrer do curso e dos meus desenvolvimentos de projetos, o banco de dados que mais se encaixou a minha metodologia de programação foi o *SQL SERVER*, tendo encaixado perfeitamente com a programação BACKEND em *JAVASCRIPT*. Por meio do SQLSERVER modelos modelar bancos extensos e administrar por meio de tabelas relacionadas ou não, facilitando a organização e o funcionamento.
##
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
