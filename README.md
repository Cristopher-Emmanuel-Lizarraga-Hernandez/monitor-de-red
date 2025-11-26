# monitor-de-red

Modelo Híbrido PMBOK + Scrum para el Monitor de Actividad de Protocolos de Red
Justificación de la Elección Específica para el Proyecto
Análisis del Proyecto
El Monitor de Actividad de Protocolos de Red es un proyecto con características mixtas:

Componentes de infraestructura que requieren planificación rigurosa (base de datos, servicios Windows)

Componentes de desarrollo que necesitan iteración y adaptación (interfaz web, aplicación cliente)

PMBOK para Estructura y Control
¿Por qué PMBOK es esencial?

Gestión de riesgos de seguridad en protocolos de red

Control estricto de cambios en componentes críticos

Documentación formal para cumplimiento de estándares

Gestión de stakeholders (equipo de seguridad TI, usuarios)

Aportes específicos al proyecto:

Planificación detallada de la arquitectura de base de datos MySQL

Gestión de riesgos en clasificación de protocolos

Control de calidad en captura de información del sistema

Documentación de procedimientos de seguridad

Scrum para Desarrollo Iterativo
¿Por qué Scrum se adapta?

Desarrollo incremental de la interfaz web responsiva

Adaptación a cambios en requisitos de visualización

Retroalimentación continua en la experiencia de usuario

Desarrollo paralelo de componentes (cliente, servicio, web)

Aportes específicos al proyecto:

Iteraciones rápidas en la aplicación cliente (VB/C#)

Mejora continua basada en feedback del área de notificación

Desarrollo evolutivo de gráficas y reportes

Adaptación a nuevos protocolos de red

Aplicación Práctica en el Proyecto
Fase 1: Iniciación (PMBOK)
markdown
**Actividades Específicas:**
- Definir alcance del monitor de protocolos
- Identificar stakeholders: equipo de seguridad, administradores de red
- Análisis de riesgos de seguridad en captura de datos
- Establecer criterios de éxito para clasificación de protocolos

**Entregables:**
- Charter del proyecto de monitorización
- Matriz de stakeholders con roles específicos
- Análisis inicial de protocolos a monitorear
Fase 2: Planificación Detallada (PMBOK)
markdown
**Planificación Técnica:**
- Diseño detallado de base de datos MySQL para protocolos
- Arquitectura del servicio Windows
- Especificaciones de la API para integración
- Plan de implementación del system tray

**Plan de Calidad:**
- Criterios de validación para direcciones MAC/IP
- Estándares de clasificación de colores de seguridad
- Protocolos de prueba para captura de información
Fase 3: Desarrollo por Sprints (Scrum)
Sprint 1: Infraestructura Base
markdown
**Objetivo:** Captura básica de información del sistema
- Script PowerShell para obtener datos del sistema
- Estructura inicial de base de datos
- Validación básica de direcciones MAC/IP

**Entregables:**
- Script .ps1 funcional
- Tablas MySQL creadas
- Validación de unicidad de direcciones
Sprint 2: Servicio y Aplicación Cliente
markdown
**Objetivo:** Servicio Windows y aplicación VB/C#
- Servicio que se ejecuta al inicio
- Aplicación cliente con captura de puertos
- Lógica de evitación de duplicados (10 min)

**Entregables:**
- Servicio Windows instalable
- Aplicación cliente funcional
- Regla de no duplicación implementada
Sprint 3: Interfaz de Usuario
markdown
**Objetivo:** System Tray e Interfaz Web
- Ícono en system tray (no cerrable)
- Interfaz web responsiva básica
- Visualización de datos recopilados

**Entregables:**
- Aplicación con system tray
- Interfaz web inicial
- Conexión base de datos-web
Sprint 4: Clasificación y Reportes
markdown
**Objetivo:** Sistema de colores y gráficas
- Clasificación por colores de seguridad
- Gráficas de pastel para protocolos
- Reporte de actividad general de red

**Entregables:**
- Sistema de colores implementado
- Gráficas de protocolos seguros/inseguros
- Dashboard de actividad general
Fase 4: Implementación y Cierre (PMBOK)
markdown
**Actividades Finales:**
- Implementación en ambiente de producción
- Capacitación a administradores
- Documentación técnica completa
- Lecciones aprendidas específicas de seguridad

**Entregables Finales:**
- Sistema completamente funcional
- Manual de administración
- Documentación de API y base de datos
