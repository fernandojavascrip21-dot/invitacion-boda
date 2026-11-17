# 💍 Invitación digital de boda — Valeria & Santiago

Invitación de boda interactiva hecha **solo con HTML, CSS y JavaScript** (sin librerías). Funciona en celular y computadora. Los nombres, fechas y lugares son de ejemplo.

## Experiencia

- **Apertura con sello de lacre:** la invitación aparece cerrada como un portafolio, con hilo dorado, un ramito de flores y un sello con las iniciales. Al tocar el sello **dos veces** se rompe y se activa el sonido. Después caen el hilo y el ramito, se abren las solapas en 3D y llueven pétalos.
- **Música automática:** el Canon de Pachelbel en versión caja musical, generado en el navegador con Web Audio API. Se pausa sola si el invitado cambia de pestaña.
- **Portada:** los nombres en caligrafía con brillo dorado, ramas de eucalipto que se dibujan solas y la fecha.
- **Pase personalizado:** con un enlace como `…/#familia-lopez-perez-4`, la invitación saluda al invitado, muestra un boleto con sus pases y limita los asistentes en la confirmación.
- **Secciones:** cuenta regresiva, padres y padrinos, nuestra historia (una línea de tiempo que se dibuja al bajar), ceremonia y recepción (con Google Maps y Google Calendar), itinerario, código de vestimenta con paleta de colores, mesa de regalos, hashtag para fotos y confirmación por WhatsApp con mensaje para los novios.

## Personalizar

Abre `index.html` y edita el bloque `CONFIG` al inicio del `<script>`: nombres, fecha, padres, padrinos, historia, lugares, itinerario, vestimenta, regalos, hashtag y fecha límite para confirmar.

**Temas de color:** cambia `tema` por `"salvia"` (verde y dorado), `"lavanda"` (lila y cobre) o `"marino"` (azul marino y dorado).

## Enviar pases personalizados

1. Publica la invitación con GitHub Pages (abajo).
2. Abre `https://fernandojavascrip21-dot.github.io/invitacion-boda/#generar-pases`.
3. Escribe el nombre del invitado o familia y sus pases. La página genera su enlace y un botón para enviarlo por WhatsApp.

También puedes armar el enlace a mano: `…/invitacion-boda/#nombre-del-invitado-2`. Usa minúsculas y guiones, sin acentos, y pon al final el número de pases.

## Publicar con GitHub Pages

1. Entra a **Settings → Pages**.
2. En **Source** elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. En uno o dos minutos quedará en `https://fernandojavascrip21-dot.github.io/invitacion-boda/`.
