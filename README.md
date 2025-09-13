# Sistema de Gestión de Taller de Laptops (SGTL)

El **SGTL** es un sistema diseñado para optimizar la operación de un *taller de reparación de laptops*. Administra de forma centralizada las áreas clave del negocio:  
Clientes, Equipos, Diagnóstico y Cotización, Órdenes de Servicio, Catálogo, Inventario, Ventas, Pagos & Facturación, Garantías, Marketing, Personal y Proveedores.

## Problemática del proyecto

En los talleres de reparación suelen existir **fallas de organización y trazabilidad**: diagnósticos y cotizaciones dispersos, seguimiento manual de órdenes, control limitado de inventario, **pagos sin conciliación** y poca visibilidad del desempeño (ventas, rotación de refacciones, tiempos de reparación y garantías). Esto genera respuestas lentas, costos ocultos y pérdida de confianza del cliente.

## Objetivo del proyecto

**Sistematizar** los procesos de recepción, diagnóstico, reparación y entrega mediante un sistema digital que integre inventario, catálogo y finanzas. El objetivo es **agilizar el flujo** de Órdenes de Servicio de punta a punta, mejorar la precisión de *cotizaciones y cobros*, y habilitar **análisis de ventas** y métricas operativas para la toma de decisiones.

## Módulos del sistema

El sistema se fragmentó empleando la estrategia de *divide y vencerás*, identificando módulos independientes que se integran fácilmente en una solución completa:

- Clientes
- Equipos
- Diagnóstico y Cotización
- Órdenes de Servicio
- Catálogo
- Inventario
- Ventas
- Pagos & Facturación
- Garantías
- Marketing
- Personal
- Proveedores
- Análisis de Ventas

## Miembros del proyecto

- Cortes Ceron Jose Manuel ([230110688@itsoeh.edu.mx](mailto:230110688@itsoeh.edu.mx))

## Estructura de carpetas

```
/assets
  /css/styles.css
  /js/router.js
  /js/app.js
  /img/...
/modules
  analisis-ventas.html
  catalogo.html
  clientes.html
  diagnostico-cotizacion.html
  equipos.html
  garantias.html
  inventario.html
  marketing.html
  ordenes-servicio.html
  pagos-facturacion.html
  personal.html
  proveedores.html
  ventas.html
/system
  main.html
/index.html
```