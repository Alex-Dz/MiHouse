# MiHouse

## Descripción

MiHouse es un software de gestión para conjuntos resindenciales pensado para organizar, automatizar y facilitar muchas de las funciones que se llevan a cabo en un conjunto residencia, ideado inicialmente con 3 tipos de usuario:
 - Residentes
 - Recepción
 - Administración

## Arquitectura y diseño

La arquitectura consiste de un aplicativo que maneja distintas interfaces (_Front-ends_) según el tipo de usuario y las funciones que puede desempeñar, siendo estos una aplicación web, una aplicación de escritorio y una aplicación movil. 

En todos los casos el Front-end está desarrollado mediante el framework de **Flutter** que es un framework que permite el desarrollo de interfaces adaptativas y multiplataforma en un solo proyecto.

Por su parte los Front-ends se conectan a una RestAPI de servicio (_Back-end_) desarrollada en **Spring Boot** que se encarga de llevar a cabo todos los procesos, funciones y la magia negra detrás del aplicativo (:smirk:).

Y como en algún lado se deben guardar los datos, el Back-end se conecta con una base de datos relacional de **MySQL** donde se almacenan todos los registros y datos necesarios para el aplicativo.


## Repositorios

### Fron-end Administrador

https://github.com/nestorsgarzonc/mi_house_administrator

### Back-end

https://github.com/Alex-Dz/Mi_House_API

## Desarrolladores
#### _(porque si, hay que dar los créditos respectivos)_

- Alejandra Superlano
- Alexander Cárdenas
- Juan Santamaría
- Paulino Acuña
- Sebastián Garzón
- Tania Quijano
