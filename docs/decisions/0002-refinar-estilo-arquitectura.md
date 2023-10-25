# Refinar-Estilo-Arquitectura

* Status: proposed
* Date: 2023-10-25

## Context and Problem Statement

Se necesita cambiar nuestra arquitectura de dos capas a tres capas, ya que las bases de datos conformarian la tercera capa y no deberia estar incluida en la segunda capa, la cual hace el proceso de información.

## Decision Drivers

* RF01: Migración a arquitectura basada en microservicios
* RF02: Cambio de acceso a las bases de datos mediante protocolos HTTP/REST
* RF03: Cambio de acceso a las bases de datos mediante un componente Gateway
* RF04-1: Crear módulo de clientes (crítico)
* RF04-2: Crear módulo de pedidos (no crítico)
* RF04-3: Crear módulo de reparto y rutas (crítico)
* RF04-3-1: Elección de algoritmos de optimización
* RF04-4: Crear módulo de estadísticas (no crítico)
* RF04-5: Crear módulo de incidencias (semi crítico)
* RF04-6: Crear módulo de pagos (crítico)
* RF05: Usar intermediario de comunicación entre funcionalidades
* RF06: Acceder a datos de la empresa desde diferentes dispositivos

## Considered Options

* 0002-1-Arquitectura-tres-Capas-MVC-Eventos
* 0002-2-Arquitectura-dos-capas-MVC-Eventos

## Decision Outcome

Chosen option: "", because comes out best.
