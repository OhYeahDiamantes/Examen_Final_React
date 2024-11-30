IMPORTANTE: Entrar al siguiente link de Drive para descargar el archivo: https://drive.google.com/file/d/1T-lvml1aeOO9bgMOOOiwPY-6Yrh1SoXg/view?usp=drive_link

Virtual Art Gallery - Karol Bolívar.

Virtual Art Gallery es una aplicación web interactiva desarrollada con React, Three.js y Material-UI. La aplicación simula una galería de arte virtual donde los usuarios pueden explorar piezas de arte 3D, interactuar con ellas y dejar comentarios. Además, cuenta con una sección de contacto para enviar mensajes y una página de inicio animada.

---

-- Características

-Página de Inicio/Galería: Incluye animaciones con Framer Motion y un diseño atractivo.
-Galería 3D: Explora piezas de arte 3D con rotación interactiva, detalles en un modal y funcionalidad para dejar comentarios.
-Sección de Contacto: Un formulario simple y funcional para enviar mensajes.
-Diseño Responsivo: Totalmente adaptable a diferentes tamaños de pantalla.
-Navbar Interactivo: Menú estilizado con Material-UI para navegar entre secciones.

---

-- Tecnologías y librerías utilizadas

-React: Biblioteca principal para construir la interfaz de usuario.
-React Router: Para gestionar la navegación entre páginas.
-Three.js y React Three Fiber: Para renderizar y manipular las piezas de arte 3D.
-Material-UI: Componentes estilizados para el diseño de la interfaz.
-Framer Motion: Animaciones fluidas en la página de inicio.
-Bootstrap: Para los estilos de los modales en la galería.
-CSS personalizado: Para personalizar el diseño en cada sección.

---

-- Estructura del proyecto

src│ 
     ├── components/ │
       ├── ArtPiece.tsx │ 
       ├── ArtPiece2.tsx │ 
       ├── ArtPiece3.tsx │ 
       ├── CommentModal.tsx │ 
       ├── Contact.tsx │ 
       ├── Gallery.tsx │ 
       ├── Home.tsx │ 
       ├── Navbar.tsx │ 
       ├── ArtPiece.css │ 
       ├── Contact.css │ 
       ├── Gallery.css │ 
       ├── Home.css │ 
       ├── Navbar.css │ 
       ├──App.tsx

---

-- Instrucciones

1. Requisitos previos
Asegurarse de tener instalados en el sistema:
- [Node.js](https://nodejs.org/) (versión más actual)
- [npm](https://www.npmjs.com/)
- [react] (https://es.react.dev/learn/installation)

2. Descargar los archivos que están en el repositorio.
3. Abrir el símbolo del sistema, escribir cd + (directorio del archivo) y luego npm run dev o npm start, le aparecerá un link localhost, cópielo y péguelo en su navegador.
--Para instalar librerías, poner npm install + (nombre de la librería)

---

-- Personalización
Si desea modificar la aplicación, tenga en cuenta que:

-Los estilos personalizados están en la carpeta components.
-Las piezas de arte 3D utilizan archivos .glb. Puede reemplazarlos en public/ y actualizarlos en los archivos ArtPiece.
-Los comentarios se almacenan temporalmente en localStorage.
