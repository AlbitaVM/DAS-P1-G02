# Rectificación Patrón de diseño algoritmos

* Status: proposed
* Date: 2023-11-08

## Context and Problem Statement

Hemos detectado que en las pasadas decisiones de diseño cometimos un error al elegir el patrón de diseño Abstract Factory para gestionar los dos algoritmos existentes.

## Decision Drivers

* RF04-3-1 Elección de algoritmos de optimización

## Considered Options

* 0010-1-Patrón de Bridge
* 0010-2-Patrón de State
* 0010-3-Patrón de Strategy
* 0010-4-Patrón de Command
* 0010-5-Patrón de Template Method

## Decision Outcome

Chosen option: "0010-3-Patrón de Strategy", because nos permite extraer la situación de los algoritmos y así poder seleccionar el que más convenga según los intereses.
