# J.A.R.V.I.S. — Just A Rather Very Intelligent System

> Asistente IA de voz con personalidad británica, integración Claude API y visualizador holográfico de partículas.

![Version](https://img.shields.io/badge/version-3.2-00d4ff)
![Status](https://img.shields.io/badge/status-stable-00e676)
![License](https://img.shields.io/badge/license-personal-ff9933)

## ⚡ Características

- 🎙️ **Reconocimiento de voz** con wake word "Hey JARVIS" (Chrome/Edge)
- 🔊 **Síntesis de voz** con timbre británico configurable
- 🤖 **Integración Claude API** con memoria conversacional
- 🌌 **Visualizador holográfico** de partículas reactivo al audio
- 🎯 **Comandos locales** integrados (hora, fecha, abrir sitios, búsqueda web)
- 🛡️ **API key local** — nunca abandona su navegador
- 🔍 **Modo diagnóstico** con state machine y log detallado

## 🚀 Inicio Rápido

1. Abra la URL pública de GitHub Pages: `https://[su-usuario].github.io/[su-repo]/`
2. Configure su API key de Anthropic en el panel superior
3. Presione **INICIAR ESCUCHA** y autorice el micrófono
4. Diga su comando — JARVIS responderá con voz

## 🔑 Configuración API

Obtenga su API key en [console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys).
Requiere billing activo: [console.anthropic.com/settings/billing](https://console.anthropic.com/settings/billing).

## 🛠️ Tecnologías

- Web Speech API (SpeechRecognition + SpeechSynthesis)
- Canvas 2D para visualizador de partículas
- Claude API (Anthropic) via fetch directo
- LocalStorage para persistencia de configuración

## 📋 Comandos Locales (sin API)

| Comando | Acción |
|---------|--------|
| "¿Qué hora es?" | Hora actual |
| "¿Qué día es hoy?" | Fecha completa |
| "Abrir YouTube/Google/Gmail/Claude" | Lanza el sitio |
| "Buscar [tema]" | Búsqueda en Google |
| "Apagar sistema" | Cierra escucha |

## 🎨 Personalización de Voz

Para una experiencia auténtica JARVIS, instale voces británicas en su sistema:

- **Windows**: Configuración → Hora e idioma → Voz → Agregar voz → English (UK)
- **macOS**: Ajustes → Accesibilidad → Contenido leído → Voz del sistema → Daniel/Oliver/Arthur

## 🐛 Solución de Problemas

### "STT error: aborted"
Resuelto en v3.2 mediante state machine y cooldown. Si reaparece, es informativo y no afecta funcionamiento.

### Micrófono bloqueado
1. Clic en el candado de la URL
2. Permitir Micrófono
3. Recargar (F5)

### Error 401 invalid x-api-key
- Verifique billing activo en su cuenta Anthropic
- Regenere la API key
- Confirme que copió la key completa sin espacios

## 📜 Licencia

Proyecto personal inspirado en J.A.R.V.I.S. de Iron Man (Marvel Studios). Uso educativo y personal.

---

*"Sistemas en línea, Sir. A su servicio."*
