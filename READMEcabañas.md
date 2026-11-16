# 🌴 Baan Nam · Cabañas sobre el agua en Koh Tao

Web ficticia de un alquiler de cabañas sobre el agua en Koh Tao (Tailandia), creada como proyecto de portfolio. El foco está en la experiencia visual: animaciones ligadas al scroll, fotografía realista y un simulador de reservas funcional.

**🔗 [Ver la web en vivo](https://TU-USUARIO.github.io/baan-nam/)**

![Portada de Baan Nam](media/portada.jpg)

## ✨ Funcionalidades

- **Descenso en dron con el scroll**: el vídeo de portada avanza y retrocede al ritmo del scroll, con un altímetro que baja de 180 a 0 metros.
- **Cabañas en scroll horizontal**: la sección se fija en pantalla y las cuatro cabañas pasan de lado mientras haces scroll vertical.
- **Fichas de cabaña** con galería automática (exterior, interior y baño), características y precio.
- **Simulador de reservas**:
  - Calendario con días ocupados distintos para cada cabaña y selección de rango con vista previa.
  - Precio por temporada (alta +25 %, media, lluvias −15 %).
  - Ofertas con condiciones validadas (Luna de miel, Pack buceo, Larga estancia, Reserva anticipada).
  - Extras (desayuno, cena, traslado, bautismo de buceo), IVA y total animado.
- **Foto aérea interactiva** con puntos de información.
- **Mapa** de Google Maps en satélite con los lugares de interés de la isla.
- **Detalles de interfaz**: texto que se ilumina palabra a palabra, imágenes que se revelan al aparecer, parallax, cursor personalizado, botones magnéticos, franja de texto en movimiento y diseño responsive.

## 🛠️ Tecnologías

- HTML5, CSS3 (sticky, clip-path, backdrop-filter, animaciones) y JavaScript vanilla, sin frameworks ni librerías.
- `IntersectionObserver` para las animaciones de entrada.
- Vídeo recodificado con FFmpeg (todos los fotogramas clave) para que la reproducción ligada al scroll sea fluida.

## 🎨 Imágenes y vídeo

- Imágenes generadas con IA (Microsoft Copilot) a partir de prompts diseñados para mantener el mismo resort, la misma luz y el mismo estilo en todas las fotos.
- Vídeo del descenso en dron generado con Kling AI a partir de dos imágenes (fotograma inicial y final).

## 🚀 Cómo verla en local

1. Clona o descarga el repositorio.
2. Abre `index.html` en el navegador. La carpeta `media` tiene que estar junto al HTML.

---

Proyecto ficticio de portfolio · Diseño y desarrollo: **Sergio Pérez**
