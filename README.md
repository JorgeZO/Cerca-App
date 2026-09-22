# Cerca

Prototipo visual e interactivo de acompañamiento de personas mayores. Nombre inspirado en la cercanía y el cuidado a distancia. Incluye una identidad propia y diseño adaptable a móvil y escritorio.

## Demostración

- Acceso Face ID simulado con animación y confirmación.
- Acceso alternativo: código **123456**.
- Inicio, alertas y sus detalles, monitoreo, historial con filtros, perfil con pestañas, asistente con respuestas predefinidas y ajustes del dispositivo.
- El botón de rostro en la barra superior permite repetir el acceso para la presentación.
- El monitoreo se puede ampliar. Pulsa Escape o el botón de ampliar para cerrarlo.

No usa una cámara real, reconocimiento facial, llamadas, IA remota ni conexión con dispositivos. Datos e imágenes de ejemplo. Las preferencias y conversaciones se reinician al recargar. El acceso es una simulación visual, no una barrera de seguridad.

## Vista previa local

Desde esta carpeta:

```sh
python3 -m http.server 4173 --directory dist
```

Abre http://localhost:4173.

## GitHub y Vercel

Sube el contenido de esta carpeta a un repositorio de GitHub e impórtalo en Vercel. La configuración está en `vercel.json`:

- Framework: Other.
- Directorio de salida: `dist`.
- No requiere compilación, instalación ni variables de entorno.

No incluir `.openai`, `.vercel`, credenciales ni archivos temporales. Las fuentes web usan Google Fonts con alternativas del sistema. Las imágenes están incluidas localmente.

## Identidad y recursos

Logo e imagen de sala generados con la herramienta integrada ImageGen. El símbolo representa cercanía y cuidado en verde profundo.

Prompt del logo: Square minimal refined teal #12645c symbol combining embracing arcs and a small central person/heart. Flat geometric clean logo, precise balanced silhouette. Centered symbol on ivory #f6f7f4 background, generous clear margin. No text, gradients, mockup or watermark.

Prompt de la escena: Wide 3:2 realistic photo of a fictional elderly silver-haired woman seated on a sofa reading a book in a bright beautiful living room, plants and sunlight. Natural candid photography, elevated indoor camera position, calm and dignified atmosphere. No UI, overlay, timestamp, text or watermark.
