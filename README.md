[README.md](https://github.com/user-attachments/files/28020195/README.md)
# J.A.R.V.I.S. v3.3 — Enterprise Ready

> Asistente IA de voz con personalidad británica, Claude Sonnet 4.5, memoria persistente y comandos empresariales.

![Version](https://img.shields.io/badge/version-3.3-00d4ff)
![Status](https://img.shields.io/badge/status-production-00e676)

## 🆕 Novedades v3.3

- ✨ **Claude Sonnet 4.5** como modelo predeterminado (+80% capacidad de razonamiento)
- 💾 **Memoria persistente** con IndexedDB (recuerda entre sesiones)
- 🎯 **10 Comandos empresariales** para programación y control de gestión
- 🧠 **System prompt adaptativo** (respuestas cortas para comandos, largas para análisis)
- 🔄 **Continuous listening** (conversación fluida sin wake word)
- 📊 **Contexto expandido** (últimos 15 turnos vs 5 anteriores)

## ⚡ Características

- 🎙️ Reconocimiento de voz continuo (Chrome/Edge)
- 🔊 Síntesis de voz británica configurable
- 🤖 Integración Claude API con memoria conversacional
- 🌌 Visualizador holográfico reactivo al audio
- 💼 Comandos empresariales para programadores
- 🛡️ API key local — nunca abandona su navegador
- 📝 Memoria persistente entre sesiones

## 📋 Comandos Empresariales

| Comando de Voz | Acción |
|---|---|
| "JARVIS dashboard" | Abre tu dashboard configurado |
| "logs" / "últimos logs" | Abre sistema de logs |
| "git status" | Estado del repositorio (simulado en v3.3) |
| "incidentes activos" | Abre sistema de alertas |
| "anota [texto]" | Guarda nota en memoria persistente |
| "proyecto [nombre]" | Cambia contexto de proyecto |
| "resume sesión" | Genera resumen de lo conversado |
| "docs de [tema]" | Abre documentación (Python, JS, React, etc) |
| "busca en SO [query]" | Búsqueda directa en Stack Overflow |

## 🚀 Inicio Rápido

1. Abra: `https://[su-usuario].github.io/[su-repo]/`
2. Configure API key de Anthropic + URLs de herramientas empresariales
3. **INICIAR ESCUCHA** → autorice micrófono
4. Hable naturalmente — JARVIS responderá

## 💾 Memoria Persistente

JARVIS v3.3 recuerda:
- ✅ Últimas 50 sesiones conversacionales
- ✅ Proyectos activos con contexto
- ✅ Notas rápidas tomadas por voz
- ✅ Resúmenes automáticos de sesiones

**Ver memoria**: Click en "📖 Ver Memoria" en panel de API.

## 🔑 Configuración

### API Key
[console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys)

### URLs Empresariales
Configure en panel "Comandos Empresariales":
- URL Dashboard (ej: Grafana, Datadog, custom)
- URL Logs (ej: Kibana, Splunk, CloudWatch)
- URL Incidentes (ej: PagerDuty, Opsgenie)
- Proyecto Activo (contexto actual de trabajo)

## 🤖 Modelos Disponibles

| Modelo | Uso Recomendado | Velocidad |
|---|---|---|
| **Sonnet 4.5** ⭐ | Balance perfecto (default) | Media |
| Opus 4.5 | Razonamiento complejo | Lenta |
| Haiku 4.5 | Comandos rápidos | Muy rápida |

## 🎨 Personalización

### Voces Británicas (recomendado)
- **Windows**: Configuración → Voz → Agregar → English (UK)
- **macOS**: Ajustes → Contenido leído → Daniel/Oliver/Arthur

### System Prompt Adaptativo
JARVIS detecta automáticamente:
- **Comandos simples** → respuesta ≤25 palabras
- **Análisis técnico** → respuesta estructurada completa

## 🔮 Roadmap FASE 2 (Claude Enterprise)

Cuando tenga acceso a Claude Enterprise:
- 📸 **Visión de pantalla en vivo** (captura automática cada N segundos)
- 🖱️ **Control de mouse/teclado** (automatización completa del PC)
- ⚡ **Ejecución de comandos bash** reales
- 🔗 **Integración MCP** (GitHub, Jira, Slack, Databases)
- 🤖 **Agente autónomo** (diagnostica, propone, ejecuta con aprobación)

## 📜 Changelog

### v3.3 (2024-05-19)
- Upgrade a Claude Sonnet 4.5
- Memoria persistente IndexedDB
- 10 comandos empresariales
- System prompt adaptativo
- Continuous listening mejorado

### v3.2 (2024-05-18)
- Fix definitivo bucle "aborted"
- State machine de reconocimiento
- Deployment a GitHub Pages

### v3.1 (2024-05-18)
- Validador de API key en tiempo real
- Diagnóstico automático 401

---

*"Sistemas en línea, Sir. Listo para asistir."*
