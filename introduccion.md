---
description: >-
  el api de factuemision te proporciona acceso a todos los catálogos vigentes
  disponibles tanto para la generación de CFDI como de los complementos
  disponibles.
---

# 📖 Introduccion

Los catálogos públicos del SAT son engorrosos y su formato requiere mucho trabajo previo para su utilización, con nuestra api pretendemos hacer esa actividad menos complicada, pues te entregamos cada catalogo en formatos ya digeridos para su integración, además de algunos servicios que te permiten hacer algunas validaciones y asegurar que los datos que estas colocando cumplen con las reglas fiscales que se requieren en un CFDI.&#x20;

{% hint style="warning" %}
**IMPORTANTE:** estos servicios no son de timbrado, son de apoyo a tu aplicación, nosotros aseguramos que todo esté listo previo a que utilices un proveedor de timbrado, sea intermediario o autorizado.&#x20;
{% endhint %}

## Características soportadas en esta API

* **Versión vigente de CFDI** (Actualmente 4.0 vigente a partir de enero de 2022)
* **Catálogos vigentes de CFDI disponibles**&#x20;
* **Complementos vigentes disponibles.**
* **Listado de receptores en el archivo 69-B** (Lista negra del SAT)
* Catálogos de **RETENCIONES**
* Catálogos de **COMERCIO EXTERIOR**
* Catálogos de **CARTA PORTE**
* Catálogos de **NOMINA**
* Catálogos de **complementos de conceptos y generales** especiales
* Búsqueda de domicilio por CODIGO POSTAL **(CFDI y CARTA PORTE)**
* Validación de domicilio a utilizar en los documentos **(CFDI y CARTA PORTE)**
* Generacion de estructura XML partiendo de LAYOUT, CSV o de JSON&#x20;
* Generacion de estructura XML partiendo de una estructura personalizada
* Generacion de estructura XML de adendas
* Validación de estructura de XML
* Validación de estado de XML ante el SAT
* Generación de correos (**Entrega de CFDI, Acuse de CANCELACION, Resultado VALIDACION**)
* Generación de PDF (**CFDI, CANCELACION, VALIDACION**)
* Impresión remota de comprobantes (**CFDI, CANCELACION, VALIDACION**)
* **Repositorio de comprobantes de ventas para su futura generación de factura GLOBAL**&#x20;
