# SISTEMA DE GESTIÓN Y CONTROL DE COSTOS - CHOCLOS Y ASADOS LA FINCA S.A.S.

Sistema de auditoría, registro, control analítico de costos, gastos e insumos para el restaurante **Choclos y Asados La Finca S.A.S.**

---

## 📁 Estructura del Proyecto por Meses

El repositorio contiene el histórico mensual y las carpetas operativas organizadas cronológicamente:

- 📂 **MAYO 2026/** - Hojas de costos y compras de Mayo 2026.
- 📂 **JUNIO 2026/** - Hojas de costos y compras de Junio 2026.
- 📂 **JULIO 2026/** - Hojas de costos, compras y comprobantes/fotos de Julio 2026.
- 📂 **AGOSTO 2026/** - Planillas maestras de compras, inventario de cierre y dashboard de costos de Agosto 2026.
- 📂 **SEPTIEMBRE 2026/** - Mes operativo activo:
  - 📊 COMPRAS-SEPTIEMBRE-26.xlsx: Base de compras con categorización y pestañas maestras.
  - 📊 COSTOS_GASTOS_SEPTIEMBRE_2026.xlsx: Cuadro de mando integral con:
    - **Dashboard**: Consolidado ejecutivo de todas las categorías y métricas diarias.
    - **Dashboard Carnes**: Control analítico detallado de cortes, kilos, costos unitarios y participación de carnes.
    - **Dashboard Bebidas**: Monitoreo exclusivo de bebidas de tomar (cervezas, gaseosas, aguas, energizantes, hidratantes).
    - **Detalle Compras Septiembre 2026**: Base transaccional sincronizada.
  - 📂 POR PROCESAR/: Bandeja de entrada para nuevas facturas en PDF / imágenes escaneadas.
  - 📂 COMPROBANTES/: Archivo histórico de comprobantes y facturas ya procesadas y conciliadas.

---

## ⚙️ Flujo Operativo de Facturación

1. **Recepción**: Colocar facturas o comprobantes escaneados en PDF en SEPTIEMBRE 2026/POR PROCESAR.
2. **Procesamiento y Conciliación**: Extracción línea por línea de insumos, verificación de subtotales, impuestos (IVA, Impoconsumo, IBUA) y descuentos/notas crédito.
3. **Registro y Sincronización**: Carga en COMPRAS-SEPTIEMBRE-26.xlsx (Hoja1) y sincronización automática en COSTOS_GASTOS_SEPTIEMBRE_2026.xlsx (Detalle Compras).
4. **Archivo**: Traslado de la factura procesada a SEPTIEMBRE 2026/COMPROBANTES.
