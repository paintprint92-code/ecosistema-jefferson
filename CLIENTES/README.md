# CLIENTES

> CRM del Ecosistema Jefferson — registro, historial y relación con cada cliente.

## Propósito

Centralizar la información de todos los clientes del ecosistema, independientemente de qué empresa les sirve, para garantizar una atención excepcional, detectar oportunidades de venta cruzada y construir relaciones de largo plazo.

## Responsables

| Rol | Nombre |
|---|---|
| Responsable de CRM | Jefferson |
| Asesor de cuenta | (por definir) |

## Tipos de Clientes

| Tipo | Descripción |
|---|---|
| Activo | Compra o contrato vigente en los últimos 90 días |
| Recurrente | Ha comprado 3+ veces o tiene contrato mensual |
| Inactivo | Sin compra en más de 90 días |
| Prospecto | En pipeline de ventas, aún no ha comprado |
| VIP | Alto valor económico o estratégico para el ecosistema |

## Indicadores (KPIs)

| Indicador | Frecuencia | Meta |
|---|---|---|
| Total clientes activos | Mensual | Crecimiento constante |
| Tasa de retención | Trimestral | ≥ 75% |
| LTV promedio (valor de vida del cliente) | Semestral | Incremento anual |
| Clientes reactivados (de inactivos) | Mensual | ≥ 2 |
| Referidos generados por clientes | Mensual | ≥ 1 |

## Procesos

### Alta de Nuevo Cliente
1. Registrar datos en ficha de cliente
2. Asignar empresa del ecosistema correspondiente
3. Registrar primer pedido o contrato
4. Enviar mensaje de bienvenida
5. Agendar seguimiento a 30 días

### Seguimiento de Cliente Inactivo
1. Identificar clientes sin compra en 90 días
2. Enviar mensaje de reactivación con oferta o novedad
3. Registrar respuesta
4. Si no responde en 15 días: segundo contacto
5. Actualizar estado en CRM

### Venta Cruzada (Cross-sell)
- Clientes de Paint Print → ofrecer servicios de ImpulsaMia
- Clientes de ImpulsaMia → ofrecer branding con Darkpolers
- Clientes de Darkpolers → ofrecer impresión con Paint Print

## Ficha de Cliente (Campos Mínimos)

```
Nombre / Empresa:
Contacto (WhatsApp / email):
Empresa del ecosistema:
Fecha de primer contacto:
Historial de compras:
Últimas notas:
Estado: [Prospecto / Activo / Recurrente / Inactivo / VIP]
```

## Estructura de Archivos Sugerida

```
CLIENTES/
├── ACTIVOS/
│   └── [NOMBRE-CLIENTE].md
├── RECURRENTES/
├── INACTIVOS/
├── PROSPECTOS/
└── REPORTES-CRM/
```

---
*Área: Clientes — Ecosistema Jefferson*
