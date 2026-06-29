INVITACIÓN MOBILE-FIRST PARA WHATSAPP
====================================

Esta versión está optimizada para enviarse como enlace por WhatsApp y abrirse en teléfonos móviles.

IMPORTANTE
----------
WhatsApp no ejecuta archivos HTML interactivos dentro del chat.
Lo correcto es subir esta invitación a una URL pública y enviar ese enlace por WhatsApp.

Opciones fáciles para publicarla:
- Netlify
- Vercel
- GitHub Pages
- Servidor propio / hosting de la empresa

ARCHIVOS RECOMENDADOS
---------------------
Crea una carpeta llamada `assets` junto al archivo `index.html` y añade:

- preview-whatsapp.jpg     Imagen de vista previa al compartir el enlace.
- foto-1.jpg               Foto principal.
- foto-2.jpg               Foto secundaria.
- foto-3.jpg               Foto secundaria.
- poster.jpg               Imagen de portada del vídeo.
- video-invitacion.mp4     Vídeo de invitación.

RECOMENDACIONES PARA MÓVIL
--------------------------
Fotos:
- Formato JPG o WebP.
- Peso recomendado: menos de 300 KB por imagen.
- Tamaño recomendado: 1200 px de ancho como máximo.

Vídeo:
- Formato MP4.
- Mejor vertical 9:16 o cuadrado 1:1.
- Duración recomendada: 10-25 segundos.
- Peso ideal: menos de 8-10 MB.
- Usar `playsinline` para que funcione bien en iPhone y Android.

EDITAR TEXTOS
-------------
Abre `index.html` y busca:

const CONFIG = {
  empresa: "Fiesta de empresa",
  titulo: "¿Te apuntas?",
  subtitulo: "...",
  fecha: "22 de julio",
  hora: "A partir de las 16:00 h",
  urlPublica: "",
}

Cuando tengas la URL final publicada, pégala en:

urlPublica: "https://tu-url.com"

FORMULARIO REAL
---------------
Ahora mismo el formulario confirma visualmente y guarda datos en la consola del navegador.

Para recoger respuestas reales puedes conectarlo a:
- Formspree
- Google Forms
- Airtable
- Supabase
- Backend propio

Para empresa y rapidez, la opción más simple suele ser Formspree.
