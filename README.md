# 🎵 LyricSnap — by Nolodigas

**Busca la frase de una canción · Recorta el momento exacto · Envíala como audio en WhatsApp**

🔗 **[➡️ Usar LyricSnap ahora](https://Nolodigas.github.io/lyricsnap)**

---

## ¿Qué es LyricSnap?

LyricSnap es una app web gratuita para encontrar el momento exacto en el que se escucha una frase de una canción, recortarlo como clip de audio y enviarlo directamente a WhatsApp — como si fuera un meme de audio musical.

**Sin instalación. Se abre directamente en el navegador del móvil o del ordenador.**

---

## 🚀 Cómo usarla — 4 pasos

| Paso | Qué hacer |
|------|-----------|
| 🔍 **1. Buscar** | Escribe el título de la canción y el artista. Ej: *"Resistiré Dúo Dinámico"* |
| 🎵 **2. Escuchar** | Selecciona una canción. El audio arranca justo antes de donde está la frase |
| 📍 **3. Marcar** | Cuando oigas la frase exacta, pulsa el botón naranja **📍 Marcar aquí** y ajusta los handles dorados |
| 💬 **4. Compartir** | Pulsa el botón verde de WhatsApp. En el móvil se abre WhatsApp directamente con el audio listo para enviar |

> 💾 **Guarda tus clips favoritos** con el botón 🔖 — se quedan guardados en tu dispositivo para usarlos en cualquier momento sin tener que buscar de nuevo.

---

## ✨ Características principales

- 📱 **Diseño mobile-first accesible** — letras grandes, alto contraste, fácil de usar
- 🎯 **Localización exacta de la frase** — busca en qué segundo exacto aparece la frase en la canción
- ✂️ **Recortador de audio** — handles arrastrables para seleccionar hasta 15 segundos
- 🎵 **Exporta en MP3** — formato compatible con WhatsApp en PC, móvil y web
- 💬 **WhatsApp directo** — en móvil abre el selector nativo con el audio listo para enviar como nota de voz
- 🗂 **Biblioteca de clips** — guarda todos tus clips en el dispositivo para reutilizarlos
- 🆓 **Completamente gratuita** — sin registro, sin anuncios, funciona en cualquier navegador

---

## 📲 Compatible con

| Dispositivo / Navegador | Estado |
|------------------------|--------|
| Android — Chrome | ✅ Completo. WhatsApp se abre directamente |
| iPhone / iPad — Safari (iOS 15+) | ✅ Completo. WhatsApp se abre directamente |
| PC — Chrome o Edge | ✅ Descarga el MP3 y lo adjuntas en WhatsApp Web |
| PC — Firefox | ✅ Descarga el audio y lo adjuntas en WhatsApp Web |

---

## ❓ Preguntas frecuentes

**¿Por qué el audio no arranca justo en la frase?**
El preview de Apple Music solo dura 30 segundos y puede empezar en cualquier punto de la canción. Si la frase no suena donde toca, pulsa el botón naranja **📍 Marcar aquí** exactamente cuando la oigas — los handles se posicionarán en ese segundo.

**¿Cómo envío el audio en WhatsApp desde el PC?**
En el PC se descarga el archivo MP3. Luego abre [WhatsApp Web](https://web.whatsapp.com), elige la conversación, pulsa el icono 📎 y adjunta el archivo descargado.

**¿Los clips guardados se borran si cierro el navegador?**
No. Los clips se guardan de forma permanente en tu dispositivo usando IndexedDB. Solo se borran si los eliminas tú manualmente o si limpias los datos del navegador.

**¿Qué pasa si la canción no tiene letra disponible?**
Algunas canciones, especialmente las menos conocidas o en español, pueden no tener letra sincronizada en nuestra base de datos. En ese caso escucha el preview y usa el botón 📍 para marcar el momento manualmente.

---

## 🛠 Cómo funciona por dentro

| Tecnología | Para qué se usa |
|-----------|----------------|
| iTunes Search API | Búsqueda de canciones y previews de audio gratuitos (30s) |
| lrclib.net API | Base de datos gratuita de letras con timestamps por línea |
| Web Audio API | Análisis de forma de onda del audio en el navegador |
| lamejs | Codificación de MP3 directamente en el navegador |
| Web Share API | Compartir el archivo de audio nativamente en el móvil |
| IndexedDB | Guardar los clips de audio en el dispositivo del usuario |

---

## 💬 Reportar un problema o sugerir mejora

Si encuentras un bug o tienes una idea para mejorar la app:

1. Ve a [Issues](https://github.com/Nolodigas/lyricsnap/issues) → **New issue**
2. Describe qué falla o qué te gustaría que tuviera
3. Si es un bug, indica la canción y frase con la que ocurre

---

<div align="center">

Hecho con ♥ para **María Carmen Caro** y todos los que disfrutan de la música

**[Nolodigas](https://github.com/Nolodigas)** · Apps que conectan personas a través de momentos culturales

</div>
