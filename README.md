# PNK Inmobiliaria

Este proyecto fue generado a partir del siguiente prompt:

---

Actúa como un desarrollador Front-End senior especializado en HTML5 y CSS3.

Tu tarea es construir un sitio web estático completo para un proyecto universitario llamado **“PNK Inmobiliaria”**, cumpliendo estrictamente los siguientes requisitos:

## REGLAS OBLIGATORIAS

1. SOLO debes generar código HTML y CSS.
2. NO debes usar JavaScript bajo ninguna circunstancia.
3. NO debes explicar el código.
4. NO debes agregar texto fuera del código.
5. Usa buenas prácticas de HTML5 semántico y CSS3.
6. Todo debe ser responsive (mobile-first).
7. Debes estructurar el CSS en un archivo separado (styles.css).
8. Debes usar clases reutilizables y nomenclatura clara (tipo BEM opcional).

---

## OBJETIVO DEL SITIO

Desarrollar la interfaz de una plataforma inmobiliaria donde:

* Usuarios pueden registrarse como propietarios o gestores.
* Se pueden visualizar propiedades.
* Existe navegación entre todas las secciones.

---

## ESTRUCTURA OBLIGATORIA (PÁGINAS)

Debes crear las siguientes páginas HTML:

1. index.html (Página principal)
2. registro-propietario.html
3. registro-gestor.html
4. login.html
5. dashboard.html
6. registro-propiedades.html
7. gestion-usuarios.html

Todas deben estar conectadas mediante navegación.

---

## 🏗️ ETIQUETAS HTML OBLIGATORIAS

Debes usar explícitamente las siguientes etiquetas:

* `<header>`
* `<nav>`
* `<main>`
* `<section>`
* `<article>`
* `<aside>`
* `<footer>`
* `<form>`
* `<label>`
* `<input>`
* `<select>`
* `<textarea>`
* `<button>`
* `<figure>`
* `<figcaption>`

Además:

* Usa atributos `alt` en imágenes.
* Usa `aria-label` donde corresponda (accesibilidad).
* Usa correctamente `<h1>` a `<h6>` con jerarquía.

---

## 🎨 PALETA DE COLORES (OBLIGATORIA)

Debes usar EXACTAMENTE esta paleta en el CSS:

* Color primario: #1E3A8A (Azul oscuro)
* Color secundario: #3B82F6 (Azul medio)
* Color acento: #F59E0B (Naranjo)
* Fondo: #F9FAFB (Gris claro)
* Texto principal: #111827 (Negro suave)
* Texto secundario: #6B7280 (Gris)

---

## 🧩 COMPONENTES OBLIGATORIOS

1. **Página Principal (index.html)**
* Navbar con logo y menú
* Hero section (banner principal)
* Sección de propiedades destacadas (cards)
* Footer

---

2. **Formularios**

*Registro Propietario*
Campos:
* Rut
* Nombre completo
* Fecha de nacimiento
* Email
* Contraseña
* Sexo
* Teléfono
* Número de propiedad

*Registro Gestor*
Campos:
* Rut
* Nombre completo
* Fecha de nacimiento
* Email
* Contraseña
* Sexo
* Teléfono
* Certificado antecedentes (input tipo file)

---

3. **Login**
* Email
* Contraseña
* Botón login
* Link recuperar contraseña

---

4. **Dashboard**
* Sidebar con navegación:
  * Registro propiedades
  * Gestión usuarios
* Área principal con tarjetas/resumen

---

5. **Registro de Propiedades (CRUD visual)**
Campos:
* Tipo propiedad
* Descripción
* Baños
* Dormitorios
* Área total
* Área construida
* Precio CLP
* Precio UF
* Fecha
* Checkboxes:
  * Bodega
  * Estacionamiento
  * Piscina
  * Patio
* Subida de imágenes

---

6. **Gestión de Usuarios**
* Tabla con usuarios
* Botones visuales:
  * Editar
  * Eliminar

---

## NAVEGACIÓN

* Todas las páginas deben estar conectadas mediante `<nav>`
* Debe ser consistente en todo el sitio

---

## ESTILOS CSS OBLIGATORIOS

Debes incluir:

* Flexbox y/o Grid
* Diseño responsive
* Hover effects en botones
* Inputs estilizados
* Cards con sombra (`box-shadow`)
* Bordes redondeados (`border-radius`)
* Espaciado consistente (margin/padding)

---

## OUTPUT ESPERADO

Debes entregar:

* Código completo de TODOS los archivos HTML
* Código completo de styles.css
