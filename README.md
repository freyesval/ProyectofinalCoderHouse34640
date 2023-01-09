# Proyecto Final - Coderhouse Python Comisión 34640


El proyecto se considera un proyecto MVT debido al patrón de diseño de software para el desarrollo de aplicaciones web en el que django se basa: arquitectura MVT (Model-View-Template). 
Para ejecutar este proyecto, solo tendrás que tener instalado Python, Django y Pillow.
Para instalar Django escriba en el terminal:
• Pip install Django
Para instalar Pillow  en el terminal:
• Pip install Pillow

Los directorios que necesitaremos están configurados en settings.py para que funcionen sin problemas en tu ordenador, ya que solo se utilizaron rutas relativas.
El Blog tiene:

<li> Una página principal con información breve sobre las publicaciones y URL que redirigen al usuario a las publicaciones.</li>
<li> Una sesión sobre con introducción al autor.</li>
<li> Una sesión de perfil.</li>
<li> Una sesión de mensajes.</li>

El Blog también cuenta con 2 ciclos completos de CRUD (Crear, Leer, Actualizar y Borrar), uno para cuentas y otro para páginas.

1. Cuentas

- En la barra de navegación puedes encontrar dos opciones relacionadas con las cuentas si no has iniciado sesión: registrarte e iniciar sesión.
- Al registrarse puede registrar una nueva cuenta. Cuando finalice este paso, el sistema generará automáticamente un perfil vacío relacionado con esa cuenta que se puede rellenar más adelante en el perfil de edición. 
- El usuario es redirigido a la página de inicio de sesión para iniciar la sesión.
- Después de que comienza la sesión, el usuario es redirigido a la página de inicio y la barra de navegación cambia: las opciones de registro e inicio de sesión desaparecen y puede encontrar el nombre de usuario para acceder al perfil del usuario.
- El perfil del usuario se genera con una imagen por defecto y tiene información del formulario de registro y del formulario de perfil que siguen en blanco hasta que el usuario lo edite.
- Las otras opciones que se encuentran en la página de perfil son: Editar perfil, Eliminar cuenta y Cerrar sesión.


2. Paginas
- la página principal tiene una lista con una visión general de todas las publicaciones y el usuario puede seleccionar una para leer la publicación completa.
- La descripción general de las páginas contiene: Foto, Título, Subtítulo, Autor, Fecha y los primeros 200 caracteres de la publicación.
- En la vista detallada de la página elegida encontrarás opciones para editar el post, eliminar el post o crear uno nuevo.
- Las páginas se pueden crear utilizando un editor de texto.

3. Portal de administración
- El portal de administración contiene el módulo de autorización, que es una función incorporada de Django, y los dos modelos: Páginas y Cuentas.
- Puede utilizar el portal de administración para crear, editar o eliminar cualquiera de las instancias.

4. Mensajes


