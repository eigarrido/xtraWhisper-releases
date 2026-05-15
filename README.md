# xtraWhisper — Releases

App de menubar para macOS que convierte tu voz en texto y lo pega donde estés escribiendo. Push-to-talk con OpenAI Realtime, glosario configurable y corrección contextual con LLM.

## Instalación

1. Descargá el `.zip` más reciente desde **[Releases](../../releases/latest)**.
2. Descomprimí y mové `xtraWhisper.app` a `/Applications`.
3. La primera vez:
   - **Click derecho → Open** (no doble click) para saltarte el aviso de "developer no identificado".
   - Aceptá los permisos de **Micrófono** y **Accesibilidad** cuando los pida.
4. Abrí Ajustes desde el ícono de la barra de menú, pegá tu API key de OpenAI y elegí la tecla push-to-talk.
5. Listo. Mantené apretada la tecla, hablá, soltala — el texto se pega solo.

## Actualizaciones automáticas

La app chequea esta misma URL cada hora. Cuando hay versión nueva te aparece un panel "Update Available" para descargarla e instalarla en un click. También podés disparar el chequeo manual desde el menú del ícono → **Buscar actualizaciones…**

## Notas

- Este repo solo aloja los binarios firmados y el feed de actualizaciones.
- Tu API key se guarda localmente en tu Mac, no se sube a ningún servidor.
- Si tras una actualización el permiso de Accesibilidad queda inactivo, en la pantalla principal de la app hay un botón "Activar" que abre directamente la configuración correcta en System Settings.
