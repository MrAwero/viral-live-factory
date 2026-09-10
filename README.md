# 🚀 Viral Live Factory — Agencia Oficial TikTok LIVE

Sitio web oficial de **Viral Live Factory**, agencia especializada en el crecimiento, formación y monetización de creadores de TikTok LIVE en España. 

La web incluye una landing page de alta conversión, un panel de creador privado y un **panel de administración (CMS) integrado** para gestionar el contenido sin necesidad de tocar código.

🔗 [Ver sitio en vivo (https://mrawero.github.io/viral-live-factory/)]

---

## ✨ Características Principales

### 🌐 Landing Page Pública
* Diseño moderno en modo oscuro inspirado en la identidad visual de TikTok.
* Secciones de beneficios, ligas de competición, requisitos, roadmap de evolución y proceso de unión.
* Formulario de contacto y llamadas a la acción (CTA) optimizadas.
* Totalmente responsive (móvil, tablet y escritorio).

### 🔒 Panel de Creador (Privado)
* Sistema de login seguro (simulado con `localStorage`).
* Dashboard con pestañas: Formación, Campañas, Batallas, Calendario, Eventos y Sugerencias.
* Biblioteca de videos de YouTube integrados.
* Artículos expandibles con contenido técnico y estratégico.

### ⚙️ Panel de Administración (CMS Integrado)
* **Edición en vivo:** Modifica cualquier texto de la web haciendo clic sobre él.
* **Gestor de Videos:** Añade, edita o elimina videos de formación.
* **Gestor de Artículos:** Crea y edita artículos con soporte HTML.
* **Exportar/Importar:** Descarga el HTML modificado o haz backups en JSON.
* **Seguridad:** Acceso protegido por contraseña.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5** (Semántico y accesible)
* **CSS3** (Custom Properties, CSS Grid, Flexbox, Animaciones)
* **Vanilla JavaScript** (Sin frameworks, máximo rendimiento)
* **LocalStorage API** (Persistencia de datos del CMS y sesiones)

---

## 🚀 Despliegue en GitHub Pages

Para publicar esta web gratis en GitHub Pages, sigue estos pasos:

1. Crea un nuevo repositorio en GitHub (público).
2. Sube el archivo `index.html` a la rama principal (`main` o `master`).
3. Ve a la pestaña **Settings** (Configuración) de tu repositorio.
4. En el menú lateral izquierdo, haz clic en **Pages**.
5. En "Source", selecciona la rama `main` y la carpeta `/ (root)`.
6. Haz clic en **Save**. En unos minutos, GitHub te dará el enlace de tu web publicada.

---

## 🔐 Guía de Uso del Panel de Administración

El CMS está integrado directamente en la web para que puedas mantenerla actualizada sin depender de un desarrollador.

### 1. Acceder al Panel
* **Atajo de teclado:** Pulsa `Ctrl + Shift + A` (Windows) o `Cmd + Shift + A` (Mac).
* **Contraseña por defecto:** `` *(Se recomienda cambiarla desde el panel)*.

### 2. Editar Textos
1. Abre el panel admin.
2. Haz clic en **"✏️ Activar modo edición"**.
3. Verás un borde cyan alrededor de los textos editables. Haz clic en cualquiera y modifícalo.
4. Pulsa **"💾 Guardar cambios"** para persistir las ediciones.

### 3. Gestionar Videos y Artículos
* Usa los botones **"🎬 Gestionar videos"** y **"📄 Gestionar artículos"** para añadir nuevo contenido formativo.
* Para los videos de YouTube, solo necesitas el **ID del video** (la parte final de la URL, ej: `dQw4w9WgXcQ`).

### 4. Publicar los cambios
Los cambios se guardan en tu navegador. Para publicarlos en la web real:
1. Haz clic en **"📥 Descargar HTML"**.
2. Sube el nuevo archivo `index.html` a tu repositorio de GitHub reemplazando el anterior.

---

## 📂 Estructura del Proyecto
