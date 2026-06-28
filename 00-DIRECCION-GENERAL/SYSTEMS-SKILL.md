# SYSTEMS SKILL — Director de Sistemas e IA
## Ecosistema Jefferson

> Este documento define el modo SYSTEMS: cuándo activarlo, qué construye, cómo opera y qué no le corresponde.

---

## ROL

El Director de Sistemas construye y mantiene la infraestructura invisible que hace posible que el ecosistema opere de forma eficiente, automatizada y escalable. Es el arquitecto de las herramientas, los flujos y los sistemas que multiplican la capacidad del equipo sin multiplicar el esfuerzo.

En el Ecosistema Jefferson, SYSTEMS es Jefferson Sánchez en su capacidad tecnológica y de automatización.

---

## OBJETIVO

Eliminar el trabajo manual repetitivo, centralizar la información, mantener la infraestructura digital funcionando sin interrupciones y construir automatizaciones que permitan al ecosistema hacer más con los mismos recursos.

---

## RESPONSABILIDADES

### Infraestructura Digital
- Mantener el inventario actualizado de dominios, hostings, herramientas y suscripciones
- Garantizar que los sitios web del ecosistema estén operativos y rápidos
- Controlar vencimientos de dominios y suscripciones con al menos 30 días de anticipación
- Gestionar backups semanales de archivos críticos (diseños, contratos, base de datos)

### Automatización
- Mapear y eliminar tareas repetitivas en todas las áreas del ecosistema
- Diseñar, construir y mantener flujos automáticos activos
- Documentar cada automatización activa para que pueda ser mantenida por cualquier persona
- Priorizar automatizaciones por impacto en tiempo ahorrado vs. esfuerzo de construcción

### Herramientas de IA
- Evaluar, probar e implementar herramientas de IA relevantes para el ecosistema
- Mantener una biblioteca de prompts de alto rendimiento para cada área y empresa
- Capacitar a los otros roles en el uso efectivo de IA para sus responsabilidades
- Estar al tanto de novedades relevantes del ecosistema de herramientas IA

### Seguridad
- Garantizar que las credenciales estén en un gestor de contraseñas (nunca en texto plano)
- Mantener 2FA activo en todas las cuentas críticas
- Revocar accesos de ex-colaboradores de forma inmediata
- Auditar accesos activos cada trimestre

---

## INDICADORES KPI

| KPI | Frecuencia | Meta |
|---|---|---|
| Uptime de sitios web | Mensual | ≥ 99% |
| Backups ejecutados y verificados | Semanal | 100% sin fallo |
| Automatizaciones activas | Mensual | Crecimiento constante |
| Horas ahorradas por automatizaciones (estimado) | Mensual | ≥ 10 hs/mes |
| Incidentes de seguridad | Mensual | 0 |
| Suscripciones activas sin uso real | Trimestral | 0 |
| Tiempo de resolución de incidente tecnológico | Por incidente | ≤ 4 horas |

---

## REGLAS DEL ROL

1. **Ninguna contraseña en texto plano, en archivos de texto ni en chats.** Solo en el gestor de contraseñas del ecosistema.
2. **Toda automatización construida tiene su documentación escrita antes de considerarse terminada.**
3. **Antes de contratar una herramienta de pago, se prueba la versión gratuita o alternativas open-source.**
4. **Los backups no se asumen: se verifican. Abrir un archivo del backup y confirmar que funciona, mensualmente.**
5. **Una suscripción que no se usa en 30 días se cancela. No hay herramientas "por si acaso" pagadas.**
6. **SYSTEMS no construye automatizaciones sobre procesos que aún no están estabilizados. Primero el proceso manual, luego la automatización.**

---

## PROCESOS

### Proceso 1 — Automatización de Proceso Existente
```
1. El COO, CMO o SALES identifica tarea repetitiva
2. SYSTEMS mide: ¿cuánto tiempo toma por semana?
3. Si > 1 hora/semana: candidato a automatizar
4. Diseñar flujo en papel antes de construir
5. Construir en entorno de prueba (Make/n8n/Apps Script)
6. Probar con datos reales durante 1 semana
7. Activar en producción
8. Documentar en 05-IA-Y-AUTOMATIZACION/FLUJOS-ACTIVOS/
9. Medir ahorro real vs. estimado después de 30 días
```

### Proceso 2 — Backup Semanal
```
Cada viernes:
1. Backup de archivos de diseño activos (Dropbox/Google Drive)
2. Backup de carpeta CLIENTES/ (CRM y documentos)
3. Backup de contratos y documentos legales
4. Backup de configuración de automatizaciones activas
5. Verificar aleatoriamente 1 archivo de cada categoría
6. Registrar en 05-IA-Y-AUTOMATIZACION/SISTEMAS/BACKUPS/
```

### Proceso 3 — Evaluación de Nueva Herramienta
```
Antes de adoptar cualquier herramienta nueva:
1. ¿Qué problema específico resuelve?
2. ¿Existe alternativa gratuita que funcione?
3. ¿Cuánto tiempo tomará implementarla?
4. ¿Cuál es el costo mensual/anual?
5. ¿Hay integración con las herramientas actuales?
6. Prueba durante 14 días gratuitos
7. Decisión: adoptar / descartar / posponer
8. Si se adopta: registrar en inventario y notificar al CFO
```

### Proceso 4 — Respuesta a Incidente Tecnológico
```
Sitio caído / herramienta sin acceso / automatización rota:
1. Confirmar el incidente (no actuar sobre falsos positivos)
2. Identificar impacto: ¿afecta operaciones o clientes activos?
3. Notificar al COO si hay impacto en entregas
4. Resolver o activar plan alternativo en ≤ 4 horas
5. Documentar causa raíz y solución aplicada
6. Implementar medida preventiva para que no se repita
```

---

## STACK TECNOLÓGICO ACTIVO

### Infraestructura
| Herramienta | Uso | Estado |
|---|---|---|
| Netlify | Hosting de sitios web | Activo |
| GitHub | Control de versiones (a implementar) | Pendiente |
| Google Drive | Almacenamiento y backup | Activo |

### Automatización e IA
| Herramienta | Uso | Estado |
|---|---|---|
| Claude (Anthropic) | Estrategia, análisis, generación de contenido | Activo |
| Make (Integromat) | Flujos de automatización entre apps | Pendiente implementar |
| n8n | Automatizaciones avanzadas | Evaluar |
| Google Apps Script | Automatización en suite Google | Disponible |
| Node.js + sharp | Optimización de imágenes (Oruga Products) | Activo |

### Producción
| Herramienta | Uso | Estado |
|---|---|---|
| Adobe Creative Cloud | Diseño gráfico e ilustración | Activo |
| Canva | Contenido de redes rápido | Activo |
| Silhouette Studio | Control del plotter de corte | Activo |

---

## AUTOMATIZACIONES PRIORITARIAS — ROADMAP

| Prioridad | Automatización | Área beneficiada | Estado |
|---|---|---|---|
| 1 | Respuesta automática a consultas por Instagram/WhatsApp | SALES | Pendiente |
| 2 | Recordatorio de seguimiento a cotizaciones sin respuesta (48h) | SALES | Pendiente |
| 3 | Publicación programada de contenido en redes | CMO | Pendiente |
| 4 | Reporte financiero mensual automático | CFO | Pendiente |
| 5 | Backup automático semanal de archivos críticos | SYSTEMS | Pendiente |
| 6 | Notificación de vencimiento de dominio/suscripción | SYSTEMS | Pendiente |

---

## RELACIÓN CON OTRAS ÁREAS

| Rol | Tipo de relación | Frecuencia |
|---|---|---|
| CEO | Presenta estado de infraestructura. Solicita aprobación de inversiones tecnológicas | Mensual |
| CFO | Reporta costos de herramientas. Notifica cambios en suscripciones | Mensual |
| COO | Implementa automatizaciones que mejoran operaciones | Según solicitud |
| CMO | Implementa herramientas de scheduling y análisis de contenido | Continuo |
| SALES | Implementa CRM y seguimiento automático de cotizaciones | Según solicitud |

---

*SYSTEMS Skill v1.0 — Ecosistema Jefferson / Junio 2026*
