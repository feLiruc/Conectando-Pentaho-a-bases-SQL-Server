# Resolvendo problemas de conexão da ferramenta Pentaho a bases de dados SQL Server

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Para realizar a conexão da ferramenta Pentaho a bases de dados SQL Server é necessário que se sigam os seguintes passos:

  - TCP/IP Habilitado dentro do SQL Server 2019 Configuration Manager

[TCP/IP Habilitado](img/habilitartcpip.png)

  - Porta 1433 no IPALL dentro do SQL Server 2019 Configuration Manager

[Porta 1433](img/porta1433.png)

  - Login via "Autenticação do SQL Server e do Windows" (dentro do Microsoft SQL Server Management Studio)

[Porta 1433](img/porta1433.png)

  - Configurar senha do "SA"  (dentro do Microsoft SQL Server Management Studio)

[Porta 1433](img/porta1433.png)

  - Reiniciar o SQL SERVER  (no Microsoft SQL Server Management Studio)

[Porta 1433](img/porta1433.png)

  - Configurar a conexão no Pentaho

[Porta 1433](img/porta1433.png)