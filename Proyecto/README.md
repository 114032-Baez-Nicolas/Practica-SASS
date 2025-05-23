# Proyecto: Moto Center - undefined (aún no se listo la nueva entrega)
**Autor:** Nicolás Báez  
**Carrera de Desarrollo Frontend - Coderhouse**

## 📌 Descripción
Este proyecto fue desarrollado como parte de la **undefined* del curso de Desarrollo Web en Coderhouse.  
Consiste en un sitio web institucional para **Moto Center**, una empresa ficticia dedicada a la venta de motos y asesoramiento personalizado.

En esta versión se incorporó el uso de **SASS/SCSS** con una estructura profesional, dividiendo estilos en componentes reutilizables, layouts y utilidades.

---

## 🎥 Vista previa en video

📺 Podés ver una demostración del proyecto en este video de YouTube:  
🔗 [https://www.youtube.com/watch?v=gk874tHHH2Q](https://www.youtube.com/watch?v=gk874tHHH2Q)

---

## 🛠️ Tecnologías utilizadas
- HTML con etiquetas semánticas
- SCSS (SASS) para estilos modularizados
- Bootstrap para grillas y componentes
- SweetAlert2 para interacción en formularios
- Git + GitHub para control de versiones
- GitHub Pages para el despliegue online

---

## 🧱 Estructura del Sitio Web

- **Inicio**: catálogo visual de motos con carrusel, tabla interactiva y alertas de stock.
- **Información**: fichas de modelos destacados con descripción e imágenes.
- **Financiación**: requisitos, beneficios y planes de pago con animaciones en tarjetas.
- **Nosotros**: misión, recorrido del usuario por el sitio y ubicación integrada con Google Maps.
- **Contacto**: formulario funcional con validaciones y alertas interactivas.

---

## 🎨 Estilo y diseño
- Diseño responsive mediante media queries personalizadas usando mixins reutilizables: `@mixin mobile`, `@mixin tablet`, `@mixin desktop-md`, `@mixin desktop-lg`
- Uso de grillas CSS, Flexbox y clases utilitarias de Bootstrap
- Paleta de colores y tipografías definidas en `_variables.scss`
- Efectos visuales con `hover`, `box-shadow` y transiciones suaves
- Personalización de componentes Bootstrap integrada en la arquitectura modular de SCSS

---

## ▶️ Cómo compilar SCSS

Usá el siguiente comando para que Sass genere automáticamente el archivo CSS final:

```bash
sass --watch scss/style.scss css/style.css
