# Patrón de diseño GestorPedidos

* Status: proposed
* Date: 2023-11-08

## Context and Problem Statement

Necesitamos especificar un patrón de diseño para nuestro componente GestorPedidos ya que es el que hace de intermediario entre los clientes, pedidos, el reparto y las incidencias comunicando dichas funcionalidades.

## Decision Drivers

* RF05: Usar intermediario de comunicación entre funcionalidades

## Considered Options

* 0009-1-Mediator
* 0009-2-Chain-of-Responsibility
* 0009-3-Command
* 0009-4-Observer
* 0009-5-Facade

## Decision Outcome

Chosen option: "0009-1-Mediator", because porque es el que mejor implementa la funcionalidad de mediador entre módulos que necesitamos.
