# xtraWhisper — Releases

App de menubar para macOS que convierte tu voz en texto y lo pega donde estés escribiendo. Push-to-talk con OpenAI Realtime, glosario configurable y corrección contextual con LLM.

## Instalación

1. Descargá el `.zip` más reciente desde **[Releases](https://github.com/eigarrido/xtraWhisper-releases/releases/latest)**.
2. Descomprimí y movés `xtraWhisper.app` a `/Applications`.
3. La primera vez:
   - **Click derecho → Open** (no doble click) para saltarte el warning de "developer no identificado".
   - Aceptá los permisos de **Micrófono** y **Accesibilidad** cuando los pida.
4. Abrí Ajustes desde el ícono de la barra de menú, pegá tu API key de OpenAI y elegí la tecla push-to-talk.
5. Listo. Mantené apretada la tecla, hablá, soltala — el texto se pega solo.

## Actualizaciones automáticas

Desde v0.3.0 la app incluye **Sparkle**: chequea esta misma URL una vez por hora y, cuando hay versión nueva, te muestra un panel "Update Available" con descarga e instalación en un click. También podés disparar el chequeo manual desde el menú del ícono → **Buscar actualizaciones…**

## Notas

- La app es de código cerrado; este repo solo aloja los binarios firmados y el feed de Sparkle.
- Tu API key vive solo en tu Mac (`~/Library/Preferences/com.eigarrido.xtrawhisper.plist`), no la subimos a ningún lado.
- Si tras un update perdés el permiso de Accesibilidad, en la pantalla principal de la app hay un botón "Activar" que abre directamente System Settings al lugar correcto.
