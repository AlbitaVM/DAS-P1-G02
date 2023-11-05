# Decisión Diseño Dispositivos

* Status: accepted
* Date: 2023-11-01

## Context and Problem Statement

La arquitectura cuenta con una parte de clientes PC y móvil que acceden a los datos de la empresa alojados en 2 BBDD SQL (Clientes, Pedidos). Procederemos a seleccionar la mejor decisión de diseño para poder tener las dos posibildades de acceso (PC y móvil).

## Decision Drivers

* RF06: Acceder a datos de la empresa desde diferentes dispositivos

## Considered Options

* 0004-1 Decisión de Diseño Responsivo
* 0004-2 Decisión de Diseño Adaptativo
* 0004-3 Decisión de Diseño Maestro-Detalle
* 0004-4 Decisión de Diseño Navegación Drawer
* 0004-5 Decisión de Diseño Navegación por Pestañas
* 0004-6 Decisión de Diseño de Tarjetas
* 0004-7 Decisión de Diseño de Cuadrícula

## Decision Outcome

Chosen option: "0004-1 Patrón de Diseño Responsivo", because Este Modelo permite adaptar la misma pantalla a diferentes tipos de dispositivos.
