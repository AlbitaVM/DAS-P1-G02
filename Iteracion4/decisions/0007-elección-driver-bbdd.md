# Elección-driver-bbdd

* Status: accepted
* Date: 2023-11-08

## Context and Problem Statement

Necesitamos especificar un driver para conectarnos a nuestras 2 BBDD SQL (Clientes, Pedidos).

## Decision Drivers

* RF02: Cambio de acceso a las bases de datos mediante protocolos HTTP/REST.
* RF03: Cambio de acceso a las bases de datos mediante un componente Gateway.
* RF06: Acceder a datos de la empresa desde diferentes dispositivos.

## Considered Options

* 0007-1-MySQL
* 0007-2-Microsoft SQL Server
* 0007-3-Oracle Database
* 0007-4-MongoDB
* 0007-5-Apache Cassandra

## Decision Outcome

Chosen option: "0007-1-MySQL", because Es una base de datos gratuita, es muy fácil de usar, es una base de datos muy rápida, utiliza varias capas de seguridad, pocos requerimientos y eficiencia de memoria, es compatible con Linux y Windows.
