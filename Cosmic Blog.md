# Cosmic Blog




Este es un blog personal con temática cósmica, diseñado para ofrecer una experiencia inmersiva y reflexiva. La página está construida utilizando HTML, CSS, JavaScript y Bootstrap, lo que garantiza un diseño moderno, responsivo y fácil de mantener.

## Características Principales

- **Diseño Cósmico Inmersivo:** Un fondo oscuro con estrellas animadas y una paleta de colores que evoca el universo, creando una atmósfera única.
- **Contenido Multilingüe:** La página está disponible en inglés y ofrece una opción de traducción instantánea al ruso, facilitando el acceso a una audiencia global.
- **Páginas Clave:**
    - **Home:** La página principal, con un mensaje de bienvenida personalizado y párrafos reflexivos acompañados de imágenes simbólicas.
    - **About Us:** Presenta la misión y visión del blog, ofreciendo una perspectiva sobre su propósito y aspiraciones.
    - **Your Luck:** Una sección interactiva con imágenes y mensajes inspiradores, diseñada para la reflexión personal.
    - **For You:** Una página dedicada a contenido personalizado, actualmente en construcción, pero lista para futuras actualizaciones.
- **Tecnologías Modernas:** Desarrollado con HTML5 para la estructura, CSS3 para estilos avanzados, JavaScript para interactividad y Bootstrap 5 para un diseño responsivo y eficiente.




## Configuración y Uso Local

Para configurar y ejecutar este proyecto en tu máquina local, sigue estos pasos:

1.  **Clonar el Repositorio:**
    ```bash
    git clone https://github.com/TU_USUARIO/cosmic-blog.git
    ```
    (Reemplaza `TU_USUARIO` con tu nombre de usuario de GitHub una vez que subas el proyecto)

2.  **Navegar al Directorio del Proyecto:**
    ```bash
    cd cosmic-blog
    ```

3.  **Abrir con un Servidor Local:**
    Este proyecto no requiere un servidor backend. Puedes abrir los archivos HTML directamente en tu navegador o usar una extensión de servidor local para Visual Studio Code (como `Live Server`) para una mejor experiencia de desarrollo.

    -   **Usando Live Server (Recomendado):**
        1.  Instala la extensión `Live Server` en Visual Studio Code.
        2.  Abre la carpeta `cosmic-blog` en VS Code (`File > Open Folder...`).
        3.  Haz clic derecho en `index.html` y selecciona `Open with Live Server`.

    -   **Abriendo Directamente:**
        1.  Navega a la carpeta `cosmic-blog` en tu explorador de archivos.
        2.  Haz doble clic en `index.html` para abrirlo en tu navegador predeterminado.





## Despliegue en GitHub Pages

Para que tu blog sea accesible públicamente a través de GitHub Pages, sigue estos pasos:

1.  **Crear un Repositorio en GitHub:**
    *   Ve a [GitHub](https://github.com/) e inicia sesión en tu cuenta.
    *   Haz clic en el botón `+` en la esquina superior derecha y selecciona `New repository`.
    *   Nombra tu repositorio (por ejemplo, `cosmic-blog` o `tu-usuario.github.io` si quieres que sea tu página personal de GitHub Pages).
    *   Asegúrate de que sea `Public`.
    *   **NO** marques la opción `Add a README file` (ya lo estamos creando nosotros).
    *   Haz clic en `Create repository`.

2.  **Subir el Proyecto a GitHub:**
    *   Abre tu terminal o Git Bash en la carpeta `cosmic-blog` (la que contiene `index.html`, `assets`, etc.).
    *   Inicializa un repositorio Git local:
        ```bash
        git init
        ```
    *   Añade todos los archivos al área de staging:
        ```bash
        git add .
        ```
    *   Realiza tu primer commit:
        ```bash
        git commit -m "Initial commit: Cosmic Blog project"
        ```
    *   Conecta tu repositorio local con el de GitHub (reemplaza `TU_USUARIO` y `NOMBRE_REPOSITORIO` con los tuyos):
        ```bash
        git remote add origin https://github.com/TU_USUARIO/NOMBRE_REPOSITORIO.git
        ```
    *   Sube tus archivos a GitHub:
        ```bash
        git push -u origin main
        ```
        (Si tu rama principal se llama `master`, usa `git push -u origin master`)

3.  **Configurar GitHub Pages:**
    *   En tu repositorio de GitHub, ve a la pestaña `Settings`.
    *   En el menú lateral izquierdo, haz clic en `Pages`.
    *   En la sección `Source`, selecciona la rama `main` (o `master`) y la carpeta `/ (root)`.
    *   Haz clic en `Save`.

4.  **Acceder a tu Página:**
    *   GitHub Pages tardará unos minutos en desplegar tu sitio.
    *   Una vez listo, verás un mensaje en la sección `Pages` indicando que tu sitio está publicado en `https://TU_USUARIO.github.io/NOMBRE_REPOSITORIO/` (o `https://TU_USUARIO.github.io/` si nombraste el repositorio `tu-usuario.github.io`).

¡Y listo! Tu blog cósmico estará en línea y accesible para todos.

