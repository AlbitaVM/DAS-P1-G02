# Selección Patrón de Diseño Algoritmos

* Status: accepted
* Date: 2023-10-27

## Context and Problem Statement

Debido a que tenemos dos algortimos diferentes, de los cuales se selecciona uno en función a la demora del camión, debemos implementar un patrón de diseño que permita reflejar esta condición.

## Decision Drivers

* RF04-3-1 Elección de algoritmos de optimización

## Considered Options

* 0002-1-Abstract-Factory
* 0003-1-Factory-Method

## Decision Outcome

Chosen option: "0002-1-Abstract-Factory", because refiriendonos a los eventos, vamos a necesitar escoger entre dos algoritmos y este patrón nos permite abstraernos y dependiendo de lo que se necesite en ese momento instancie un tipo u otro.
