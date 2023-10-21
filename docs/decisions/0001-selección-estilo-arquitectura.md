# Selección-Estilo-Arquitectura

* Status: accepted
* Date: 2023-10-20

## Context and Problem Statement

Se necesita una arquitectura de software para migrar la arquitectura de un sistema monolítico a una basada en microservicios.

## Decision Drivers

* RF01: Migración a arquitectura basada en microservicios
* RF02: Cambio de acceso a las bases de datos mediante protocolos HTTP/REST
* RF03: Cambio de acceso a las bases de datos mediante un componente Gateway
* RF04-1: Módulo de clientes (crítico)
* RF04-2: Módulo de pedidos (no crítico)
* RF04-3: Módulo de reparto y rutas (crítico)
* RF04-3-1: Algoritmos de optimización
* RF04-4: Módulo de estadísticas (no crítico)
* RF04-5: Módulo de incidencias (semi crítico)
* RF04-6: Módulo de pagos (crítico)
* RF05: Intermediario comunicador entre funcionalidades
* RF08: Acceder a datos de la empresa desde diferentes dispositivos

## Considered Options

* 0001-1-Arquitectura-MVC-Eventos.md
* 0001-2-Arquitectura-dos-Capas-MVC-Eventos.md
* 0001-3-Arquitectura-dos-Capas-Cliente-Servidor-Eventos.md
* 0001-4-Arquitectura-Cliente-Servidor-Eventos.md
* 0001-5-Arquitectura-SOA.md
* 0001-6-Arquitectura-SOA-Eventos.md
* 0001-7-Arquitectura-SOA-MVC.md
* 0001-8-Arquitectura-SOA-dos-Capas.md

## Decision Outcome

Chosen option: "0001-2-Arquitectura-dos-Capas-MVC-Eventos.md", because Estilo predominante por capas, ya que vemos en los requisitos que hemos extraido, una capa de interfaces y otra de procesamiento de información. 
MVC proporciona interacción entre los modulos, nos facilita la UI/UX y nos permite tener diferentes vistas de los mismos datos. 
Eventos ya que contaremos con atributos que son en tiempo real.
