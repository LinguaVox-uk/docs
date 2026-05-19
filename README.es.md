<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — Extensión Chrome de dictado por voz con IA" />
</p>

<h3 align="center">LinguaVox — Habla tu idioma. Escribe en 21+ idiomas.</h3>

<p align="center">
  Mantén presionado el atajo · habla · suelta · el texto aparece en cualquier campo en 3 segundos<br>
  OpenAI Whisper · 21+ idiomas de salida · 6 modos IA · Sin clave API · Slack, Gmail, Notion, Jira
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/licencia-MIT-blue.svg" alt="Licencia" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/web-linguavox-brightgreen" alt="Sitio web" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-Instalar%20gratis-blue?logo=googlechrome" alt="Chrome Web Store" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/panel-abrir-orange" alt="Panel" /></a>
  <a href="https://github.com/LinguaVox-uk/docs/releases/latest"><img src="https://img.shields.io/badge/versión-3.0.0-green" alt="Versión" /></a>
</p>

---

## ¿Qué es LinguaVox?

LinguaVox es una extensión Chrome para dictado por voz y traducción con IA. Mantén presionado Ctrl+Space, habla, suelta — y el texto transcrito aparece instantáneamente en cualquier campo de texto activo: chats, redactores de correo, campos de búsqueda, formularios CRM y editores de código. La extensión usa OpenAI Whisper para una precisión del 95%+ y GPT-4o-mini para mejora opcional del texto: corrección gramatical, cambio de estilo, traducción.

A diferencia de la mayoría de las herramientas de dictado, LinguaVox no requiere clave propia de la API de OpenAI. Los usuarios gratuitos obtienen 100 solicitudes al día desde un grupo compartido sin ninguna configuración. Los usuarios avanzados y equipos pueden conectar su propia clave para uso ilimitado.

## Cómo funciona

**Antes de LinguaVox:** abrir otra app → grabar → copiar → cambiar de pestaña → pegar  
**Con LinguaVox:**

```
1. Haz clic en cualquier campo (Slack, Gmail, Notion, Jira…)
2. Mantén  Ctrl+Space  →  habla
3. Suelta  →  el texto aparece en ~3 segundos  ✓
```

Sin copiar y pegar. Sin cambiar de aplicación. En cualquier sitio web.

## Dónde funciona

| Plataforma | Estado | Notas |
|------------|--------|-------|
| Slack (navegador) | ✅ | Atajo a nivel de navegador, bypasea la captura de teclas de Slack |
| Gmail | ✅ | Campos de redacción y respuesta |
| Notion | ✅ | Todos los bloques `contenteditable` |
| Jira | ✅ | Campos de tareas, comentarios, descripciones |
| Asana | ✅ | Campos de tareas y comentarios |
| Salesforce | ✅ | Campos de entrada CRM |
| Cualquier `<input>` / `<textarea>` | ✅ | Universal — cualquier sitio web |
| Cualquier `contenteditable` | ✅ | Compatible con React, Draft.js, Quill |
| Google Docs | ⚠️ | Limitado — editor de lienzo personalizado |

## Características principales

- **Sin clave API** — 100 solicitudes/día gratis desde grupo compartido, sin configuración
- **Trae tu propia clave (BYOK)** — uso ilimitado al coste de OpenAI (~$0.50/mes)
- **Cuentas de organización** — grupo de claves compartido, gestión de miembros, análisis
- **21+ idiomas** — transcripción y traducción en un solo paso
- **6 modos de mejora con IA** — corrección gramatical, estilo empresarial, académico, informal, creativo, pulido inteligente
- **Privacidad total** — el audio nunca se almacena, se procesa en tiempo real
- **Menos de 3 segundos** — de extremo a extremo desde el habla al texto insertado
- **Precisión del 95%+** — OpenAI Whisper large-v2

## Modos de mejora con IA

| Modo | Qué hace |
|------|----------|
| Pulido inteligente | Corregir gramática, mejorar claridad, conservar significado |
| Estilo empresarial | Reescribir para comunicación profesional |
| Corrección gramatical | Solo gramática y ortografía |
| Estilo creativo | Texto vívido y atractivo |
| Estilo informal | Tono amigable y conversacional |
| Estilo académico | Lenguaje académico formal |

## Precios

| Plan | Solicitudes | Configuración |
|------|-------------|---------------|
| Gratis | 100/día | Solo inicio de sesión con Google |
| Tu propia clave | Ilimitado | Tu clave API de OpenAI |
| Organización | Ilimitado | Clave compartida del equipo + análisis |

## Preguntas frecuentes

### ¿Funciona LinguaVox en Slack?
Sí. Slack intercepta eventos de teclado a nivel de página. LinguaVox registra el atajo a nivel de navegador mediante `chrome.commands.onCommand`, bypaseando la captura de Slack. Funciona en todos los campos de mensaje de Slack.

### ¿Necesito una clave API de OpenAI?
No. Los usuarios gratuitos obtienen 100 solicitudes/día del grupo compartido. Añade tu propia clave en el panel para uso ilimitado.

### ¿Se graba o almacena mi voz?
No. El audio es procesado por Whisper en tiempo real y descartado inmediatamente. No se retienen datos de voz en ningún lugar.

### ¿Qué idiomas se admiten?
21+ idiomas: inglés, ucraniano, ruso, español, francés, alemán, japonés, coreano, chino, árabe, portugués, italiano, polaco, holandés, turco, sueco, rumano, griego y más.

## Enlazos

| | |
|--|--|
| 🌐 Sitio web | https://linguavox.uk |
| 📊 Panel | https://linguavox.uk/login |
| 🎤 Traducción de voz | https://linguavox.uk/voice-translation |
| ✨ Mejora de voz con IA | https://linguavox.uk/ai-voice-enhancement |
| 🌍 Hablantes no nativos | https://linguavox.uk/for-non-native-speakers |
| 👤 Sobre el autor | https://linguavox.uk/about |
| 🔒 Política de privacidad | https://linguavox.uk/privacy/ |
| 💬 Soporte | https://linguavox.uk/support/ |

## Licencia

MIT — ver [LICENSE](LICENSE)