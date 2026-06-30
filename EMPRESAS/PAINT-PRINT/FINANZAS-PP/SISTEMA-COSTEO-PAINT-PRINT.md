# SISTEMA DE COSTEO — Paint Print
**Versión:** 1.0
**Fundador:** Jefferson Sánchez
**Moneda:** CLP (Pesos chilenos)
**Inicio:** Junio 2026
**Próxima revisión:** Diciembre 2026

> Fuente única de verdad para precios, costos y márgenes de Paint Print.
> Antes de cotizar: consultar Sección 3.
> Antes de aceptar un precio: verificar el semáforo.

---

## 1. CONFIGURACIÓN GENERAL

| Parámetro | Valor |
|---|---|
| Margen mínimo aceptable | 50% |
| Margen objetivo | 65% |
| Margen de alerta roja | < 35% |
| Anticipo clientes nuevos | 100% |
| Anticipo clientes recurrentes | 50% |
| Tiempo máximo de respuesta a cotización | 2 horas |
| Tiempo estándar de entrega | 24–72 horas según producto |
| Rondas de revisión incluidas en diseño | 2 |

### Fórmula oficial de precios

```
COSTO TOTAL    = Materiales + Mano de Obra + Energía/Desgaste

PRECIO MÍNIMO  = Costo Total ÷ (1 − 0,50)   → margen 50%
PRECIO OBJETIVO = Costo Total ÷ (1 − 0,65)   → margen 65%

Mano de Obra   = Horas trabajadas × Tarifa horaria oficial
```

**Regla absoluta:** Si el precio que pide el cliente da margen < 35%, no se acepta.
Se puede reducir el alcance del pedido. El precio unitario no baja.

---

## 2. TARIFA HORARIA

### Cálculo base

| Escenario | Horas/semana | Horas/mes | Meta mensual | Tarifa/hora |
|---|---|---|---|---|
| Conservador — base operativa | 20 h | 80 h | 1.000.000 CLP | **12.500 CLP** |
| Estándar | 22 h | 90 h | 1.000.000 CLP | 11.111 CLP |
| Optimista | 25 h | 100 h | 1.000.000 CLP | 10.000 CLP |

**→ Tarifa oficial vigente: 12.500 CLP/hora**
*(Escenario conservador: si trabajas más horas de las 80, el margen mejora solo)*

### Historial de tarifas

| Periodo | Tarifa | Meta mensual | Horas base |
|---|---|---|---|
| Jun 2026 → Dic 2026 | 12.500 CLP/h | 1.000.000 CLP | 80 h/mes |
| 2027 en adelante | PENDIENTE DE REVISIÓN | PENDIENTE | PENDIENTE |

### Situación actual vs. metas

| Estado | Ingresos/mes | Horas/mes | Valor hora efectivo | Brecha |
|---|---|---|---|---|
| Hoy (jun 2026) | ~300.000 CLP | ~80 h | ~3.750 CLP/h | −8.750 CLP/h |
| Meta Objetivo 1 | 1.000.000 CLP | 80 h | 12.500 CLP/h | — |
| Meta Objetivo 2 | 2.000.000 CLP | 80 h | 25.000 CLP/h | — |

> La brecha de 8.750 CLP/hora no se cierra trabajando más horas.
> Se cierra cobrando precios correctos y aumentando el volumen de pedidos.

---

## 3. PRODUCTOS Y PRECIOS MÍNIMOS

> Cada fila se completa al registrar el primer pedido del producto.
> Cuando un producto acumula 3 pedidos → se marca como ✓ Validado.

### Cómo calcular cada fila

```
MO (CLP)        = Tiempo estándar (h) × 12.500
Costo total     = Mat. + MO + Extra (energía/desgaste estimado)
Precio mínimo   = Costo total ÷ 0,50
Precio objetivo = Costo total ÷ 0,35
```

### Catálogo de productos

| Producto | Estado | Tiempo estándar | Mat. (CLP) | MO (CLP) | Extra (CLP) | Costo total | Precio mínimo | Precio objetivo |
|---|---|---|---|---|---|---|---|---|
| **Topper set — primera vez** | ⚠️ Referencia | 7 h | 2.000 | 87.500 | 1.500 | **91.000** | **182.000** | **260.000** |
| **Topper set — proceso dominado** | ⚠️ 1 pedido | ~1 h | 2.000 | 12.500 | 500 | **15.000** | **30.000** | **42.857** |
| Tarjetas de presentación (50 pcs) | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — |
| Etiquetas adhesivas (20 pcs) | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — |
| Stickers personalizados (20 pcs) | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — |
| Taza sublimada (unidad) | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — |
| Polera/polerón sublimado (unidad) | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — |
| Vinilo decorativo | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — |
| Flyer A5 (100 pcs) | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — |
| Pendón | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — |

> Cada vez que se registra un pedido nuevo en Sección 4,
> actualizar aquí el tiempo estándar y el costo de materiales.

---

## 4. REGISTRO DE PEDIDOS

### Parámetros del mes activo

| Campo | Valor |
|---|---|
| Mes activo | Junio 2026 |
| Tarifa horaria aplicada | 12.500 CLP/hora |
| Pedidos estimados del mes | 8–12 (PENDIENTE DE CONFIRMAR) |
| Ingresos estimados del mes | ~300.000 CLP |

### Tabla de pedidos — Junio 2026

| # | Fecha | Cliente | Producto | Cant. | Mat. (CLP) | Horas | MO (CLP) | Costo total | Precio (CLP) | Margen % | Pago | Semáforo | Notas |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| PP-REF-001 | Jun 2026 | PENDIENTE | Topper set personalizado | 1 set | 2.000 | 7 | 87.500 | 91.000 | 7.000 | −1.200% | Pagado | 🔴 | Primera vez: búsqueda imagen + diseño + corte + armado. No repetir a este precio. |
| PP-002 | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — | — | — | — | — | Completar con pedidos reales de junio |
| PP-003 | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — | — | — | — | — | |
| PP-004 | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — | — | — | — | — | |
| PP-005 | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — | — | — | — | — | |
| PP-006 | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — | — | — | — | — | |
| PP-007 | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — | — | — | — | — | |
| PP-008 | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — | — | — | — | — | |
| PP-009 | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — | — | — | — | — | |
| PP-010 | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — | — | — | — | — | |
| PP-011 | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — | — | — | — | — | |
| PP-012 | PENDIENTE | PENDIENTE | PENDIENTE | — | — | — | — | — | — | — | — | — | |

### Reglas de registro

1. Registrar el pedido al recibirlo — antes de cotizar
2. Completar `Horas` y `Costo total` al terminar la producción
3. No dejar `Margen %` vacío antes de cobrar
4. Si el margen calculado es rojo: ajustar precio o documentar excepción en Sección 7
5. Al iniciar el mes siguiente: mover esta tabla completa a Sección 6 como historial

---

## 5. MATERIALES

> Se actualiza cuando cambia proveedor, precio o lote de compra.
> Fuente para calcular la columna `Mat.` en la tabla de pedidos.

### Insumos — PENDIENTE DE CONFIRMAR

| Insumo | Presentación | Costo por unidad (CLP) | Proveedor | Actualizado |
|---|---|---|---|---|
| Papel fotográfico brillante A4 | Paquete x ___ hojas | PENDIENTE | PENDIENTE | — |
| Papel fotográfico mate A4 | Paquete x ___ hojas | PENDIENTE | PENDIENTE | — |
| Papel adhesivo brillante A4 | Paquete x ___ hojas | PENDIENTE | PENDIENTE | — |
| Papel adhesivo mate A4 | Paquete x ___ hojas | PENDIENTE | PENDIENTE | — |
| Tinta Epson (set completo) | Set por colores | PENDIENTE | PENDIENTE | — |
| Cartulina 300g A4 | Paquete x ___ hojas | PENDIENTE | PENDIENTE | — |
| Palitos de madera para toppers | Paquete x ___ unidades | PENDIENTE | PENDIENTE | — |
| Sustrato sublimación — taza blanca | Por unidad | PENDIENTE | PENDIENTE | — |
| Sustrato sublimación — polera blanca | Por unidad | PENDIENTE | PENDIENTE | — |
| Papel de sublimación | Paquete x ___ hojas | PENDIENTE | PENDIENTE | — |
| Vinilo de corte | Por metro lineal | PENDIENTE | PENDIENTE | — |
| Bolsas de empaque | Paquete x ___ unidades | PENDIENTE | PENDIENTE | — |

### Insumo con dato confirmado

| Insumo | Costo por uso | Fuente del dato |
|---|---|---|
| Materiales set de toppers (completo) | ~2.000 CLP por pedido | PP-REF-001, jun 2026 |

### Alertas de inventario

| Situación | Criterio de alerta |
|---|---|
| Stock crítico | Menos del 20% del stock normal de cualquier insumo |
| Precio desactualizado | Más de 3 meses sin verificar precio con proveedor |
| Sin proveedor alternativo | Un insumo depende de un solo proveedor conocido |

---

## 6. RESUMEN MENSUAL

### Junio 2026 — Primer mes de registro

| Métrica | Valor actual | Meta | Semáforo |
|---|---|---|---|
| Ingresos brutos | ~300.000 CLP | 1.000.000 CLP | 🔴 30% de la meta |
| Pedidos registrados | PENDIENTE (est. 8–12) | ≥ 15 | 🟡 |
| Costo total real | PENDIENTE | — | — |
| Utilidad real | PENDIENTE | — | — |
| Margen promedio real | PENDIENTE | ≥ 55% | — |
| Pedidos en rojo | Al menos 1 confirmado | 0 | 🔴 |
| Ticket promedio estimado | ~25.000–37.500 CLP | Crecimiento | 🟡 |
| Horas trabajadas | ~80 h (estimado) | — | — |
| Valor hora efectivo | ~3.750 CLP/h | 12.500 CLP/h | 🔴 |
| Clientes nuevos | PENDIENTE | ≥ 5 | — |
| Clientes recurrentes (%) | PENDIENTE | ≥ 30% | — |

### Historial de cierres

| Mes | Ingresos (CLP) | Pedidos | Margen prom. | Clientes nuevos | Ticket prom. | Valor hora ef. |
|---|---|---|---|---|---|---|
| Junio 2026 | ~300.000 | PENDIENTE | PENDIENTE | PENDIENTE | PENDIENTE | ~3.750 CLP/h |
| Julio 2026 | — | — | — | — | — | — |
| Agosto 2026 | — | — | — | — | — | — |
| Septiembre 2026 | — | — | — | — | — | — |
| Octubre 2026 | — | — | — | — | — | — |
| Noviembre 2026 | — | — | — | — | — | — |
| Diciembre 2026 | — | — | — | — | — | — |

---

## 7. ALERTAS Y OBSERVACIONES

### Alertas activas

| # | Tipo | Descripción | Acción | Prioridad |
|---|---|---|---|---|
| A-001 | 🔴 Precio crítico | Topper set cobrado a 7.000 CLP. Costo real: ~91.000 CLP. Pérdida estimada: ~84.000 CLP | Próximo pedido similar: cobrar 43.000–50.000 CLP mínimo | INMEDIATA |
| A-002 | 🟡 Datos faltantes | Pedidos de junio sin registrar. Margen real del mes desconocido | Completar filas PP-002 a PP-012 antes del cierre de junio | ESTA SEMANA |
| A-003 | 🟡 Materiales | Costos de insumos sin confirmar. Sección 5 incompleta | Registrar precios reales de papel, tinta y sustratos | PRÓXIMOS 15 DÍAS |
| A-004 | 🟡 Catálogo | 8 de 10 productos sin precio calculado | Completar Sección 3 con cada nuevo pedido | EN CURSO |

### Criterio del semáforo

| Color | Margen | Significado | Acción |
|---|---|---|---|
| 🟢 Verde | ≥ 55% | Rentable — adelante | Ninguna |
| 🟡 Amarillo | 35–54% | Aceptable con justificación | Revisar si hay forma de mejorar |
| 🔴 Rojo | < 35% o negativo | Pérdida — no repetir | Acción inmediata sobre precio |

### Decisiones de precio documentadas

| Fecha | Producto | Precio anterior | Precio nuevo | Razón |
|---|---|---|---|---|
| Jun 2026 | Topper set | 7.000 CLP | 43.000–50.000 CLP (próximo pedido) | Primer cálculo real reveló pérdida de ~84.000 CLP |

### Registro de excepciones

> Una excepción es cualquier pedido cobrado por debajo del precio mínimo.
> Toda excepción debe tener justificación escrita. Sin documento, es un error.

| # Pedido | Cobrado (CLP) | Precio mínimo (CLP) | Diferencia | Justificación |
|---|---|---|---|---|
| PP-REF-001 | 7.000 | 182.000 | −175.000 | Primera vez: horas incluyen aprendizaje y diseño inicial no recurrente. Costo real no se repetirá en pedidos siguientes. |

### Tributario

> **PENDIENTE DE REVISIÓN FORMAL**
> País de operación: Chile.
> Obligaciones tributarias específicas: no documentadas en este sistema.
> Acción requerida: consultar con contador o revisar normativa SII cuando corresponda.

---

*Sistema de Costeo Paint Print v1.0 — Ecosistema Jefferson*
*Fundador: Jefferson Sánchez — Junio 2026*
*Próxima revisión: Diciembre 2026*
