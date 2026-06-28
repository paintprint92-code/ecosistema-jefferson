# SISTEMAS

> Infraestructura digital, tecnológica y de información del Ecosistema Jefferson.

## Propósito

Gestionar toda la infraestructura tecnológica del ecosistema: dominios, hosting, cuentas de servicios, herramientas digitales, seguridad y backups, asegurando operación continua y escalable.

## Responsables

| Rol | Nombre |
|---|---|
| Administrador de Sistemas | Jefferson |
| Soporte técnico externo | (por definir) |

## Inventario de Sistemas Activos

### Dominios y Web

| Activo | Empresa | Estado | Vencimiento |
|---|---|---|---|
| (dominio Paint Print) | Paint Print | Definir | — |
| (dominio ImpulsaMia) | ImpulsaMia | Definir | — |
| (dominio Darkpolers) | Darkpolers | Definir | — |

### Hosting y Deploy

| Servicio | Empresa / Uso | Plan | Estado |
|---|---|---|---|
| Netlify | Oruga Products | Free/Pro | Activo |
| (por definir) | Paint Print web | — | Pendiente |
| (por definir) | ImpulsaMia web | — | Pendiente |

### Herramientas y Suscripciones

| Herramienta | Uso | Costo/mes | Renovación |
|---|---|---|---|
| Adobe Creative Cloud | Diseño gráfico | — | — |
| Claude (Anthropic) | IA estratégica | — | — |
| (agregar según aplique) | — | — | — |

### Cuentas de Redes Sociales

| Red | Empresa | Usuario | Estado |
|---|---|---|---|
| Instagram | Paint Print | — | — |
| Instagram | ImpulsaMia | — | — |
| Instagram | Darkpolers | — | — |

## Indicadores (KPIs)

| Indicador | Frecuencia | Meta |
|---|---|---|
| Uptime de sitios web | Mensual | ≥ 99.5% |
| Backups ejecutados correctamente | Semanal | 100% |
| Costo total de infraestructura | Mensual | Optimización continua |
| Suscripciones sin uso activo | Trimestral | 0 |
| Incidentes de seguridad | Mensual | 0 |

## Procesos

### Backup de Archivos Críticos
- **Frecuencia:** Semanal (automatizar con Fase 1 de IA)
- **Qué respaldar:** Archivos de diseño, contratos, base de datos de clientes, configuraciones
- **Dónde:** Google Drive + disco externo físico
- **Verificación:** Mensual, abrir y confirmar integridad

### Alta de Nueva Herramienta Digital
1. Evaluar necesidad real y alternativas gratuitas
2. Probar versión gratuita/trial
3. Si aprueba: contratar y registrar en inventario de sistemas
4. Documentar credenciales en gestor de contraseñas (nunca en texto plano)
5. Definir responsable de uso y renovación

### Seguridad Digital
- Contraseñas únicas y largas por servicio (gestor de contraseñas obligatorio)
- 2FA activado en todas las cuentas críticas
- Revisión trimestral de accesos activos
- Revocar accesos de ex-colaboradores inmediatamente

### Vencimientos y Renovaciones
- Revisar dominios y suscripciones mensualmente
- Renovar con 15 días de anticipación
- Registrar toda renovación en inventario

## Estructura de Archivos Sugerida

```
SISTEMAS/
├── INVENTARIO/
│   ├── DOMINIOS.md
│   ├── HOSTING.md
│   ├── SUSCRIPCIONES.md
│   └── CUENTAS-REDES.md
├── BACKUPS/
│   └── REGISTRO-BACKUPS.md
├── SEGURIDAD/
│   └── POLITICA-SEGURIDAD.md
├── INCIDENTES/
└── DOCUMENTACION-TECNICA/
```

> CRITICO: Las contraseñas y claves de acceso NUNCA deben almacenarse en esta carpeta en texto plano. Usar exclusivamente un gestor de contraseñas (Bitwarden, 1Password, etc.).

---
*Área: Sistemas — Ecosistema Jefferson*
