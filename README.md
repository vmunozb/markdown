<!--
  <<< Author notes: Header of the course >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses Creative Commons Attribution 4.0 International.
-->

# Comunicar usando Markdown

_Organiza tus ideas y colabora usando Markdown, un lenguaje ligero para formatear texto._

<!--
  <<< Author notes: Start of the course >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
  Each Paso should be wrapped in <details>/<summary>, with an `id` set.
  The start <details> should have `open` as well.
  Do not use quotes on the <details> tag attributes.
-->

<!--step0-->

GitHub es para algo más que solo código. Es una plataforma para la colaboración de software, y Markdown es una de las formas más importantes en que los desarrolladores pueden hacer su comunicación clara y organizada en las incidencias (o _issues_) y solicitudes de extracción (o _pull requests_). Este curso te guiará para la creación y uso de encabezados de manera más efectiva, la organización de pensamientos en listas con viñetas, y mostrar cuánto trabajo has completado con listas de control. Incluso puedes utilizar Markdown para añadir algo de profundidad a tu trabajo con la ayuda de emoji, imágenes y enlaces.

- **Para quién es esto**: Nuevos desarrolladores, nuevos usuarios de GitHub y estudiantes.
- **Qué aprenderás**: Usar Markdown para agregar listas, imágenes y enlaces en un comentario o archivo de texto.
- **Qué construirás**: Actualizaremos un archivo de texto plano y añadiremos formato Markdown, y podrás utilizar este archivo para iniciar tu propio sitio de GitHub Pages.
- **Requisitos**: En este curso trabajarás con pull requests así como con la edición de archivos. Si estas cosas no te resultan familiares, te recomendamos que primero tomes el curso [Introducción a GitHub](https://github.com/DeustoKom/introduccion-a-github).
- **Cuánto tiempo**: Este curso consta de cinco pasos y tardarás menos de una hora en completarlo.

## Cómo empezar este curso

1. Encima de estas instrucciones, haz clic con el botón derecho del ratón en **Use this template** y abre el enlace en una nueva pestaña.<br />
   ![Use this template](https://user-images.githubusercontent.com/1221423/169618716-fb17528d-f332-4fc5-a11a-eaa23562665e.png)
2. En la nueva pestaña, sigue las indicaciones para crear un nuevo repositorio.
   - En **Owner**, elije tu cuenta personal para alojar el repositorio.
   - Recomendamos crear un repositorio público - los repositorios privados [utilizarán minutos de Acciones](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   ![Create a new repository](https://user-images.githubusercontent.com/1221423/169618722-406dc508-add4-4074-83f0-c7a7ad87f6f3.png)
3. Una vez creado tu nuevo repositorio, espera unos 20 segundos y actualiza la página. Sigue las instrucciones paso a paso en el README del nuevo repositorio.

<!--endstep0-->

<!--
  <<< Author notes: Paso 1 >>>
  Choose 3-5 steps for your course.
  The first Paso is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

<details id=1>
<summary><h2>Paso 1: Añade encabezados</h2></summary>

_¡Bienvenida/o a "Comunicar usando Markdown"!_ :wave:

**¿Qué es _Markdown_?** Markdown es una [sintaxis ligera](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) para comunicarse en GitHub&mdash;y muchos otros sitios. Puedes formatear el texto para añadir títulos, listas, **negritas**, _cursivas_, tablas y muchos otros estilos. Puedes utilizar Markdown en la mayoría de los lugares de GitHub:

- Comentarios en [issues](https://docs.github.com/issues/tracking-your-work-with-issues/about-issues), [pull requests](https://docs.github.com/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests), y [discusiones](https://docs.github.com/discussions/collaborating-with-your-community-using-discussions/about-discussions)
- Archivos con la extensión `.md` o `.markdown`.
- Compartir fragmentos de texto en [Gists](https://docs.github.com/github/writing-on-github/editing-and-sharing-content-with-gists/creating-gists)

**¿Qué es un _encabezado_?** Un encabezado es un fragmento de texto más grande al principio de una sección. Existen seis tamaños.

### Ejemplo

```txt
# Esto es un encabezado <h1>, que es el más grande
## Esto es un encabezado <h2>
###### Esto es un encabezado <h6>, que es el más pequeño
```

#### Qué aspecto tiene

# Esto es un encabezado &lt;h1&gt;, que es el más grande
## Esto es un encabezado &lt;h2&gt;
###### Esto es un encabezado &lt;h6&gt;, que es el más pequeño

### :keyboard: Actividad: Edita tu archivo con encabezados

1. Abre una nueva pestaña del navegador, y trabaja en los pasos de tu segunda pestaña mientras lees las instrucciones en esta pestaña.
1. Abre la pestaña de **pull requests**.
1. Abre el pull request que hemos creado para ti.
1. En este pull request, ve a la pestaña **Files changed**.
1. Selecciona **Edit file** en el menú de tres puntos **...** en la esquina superior derecha de la vista del archivo en `index.md`.
1. En la pestaña **Edit file**, añade un `#`, seguido de un **espacio**, antes del contenido para convertirlo en un encabezado H1. Puedes añadir más encabezados utilizando de uno a seis caracteres `#` seguidos de un **espacio**.
1. Encima de tu nuevo contenido, haz clic en **Preview**.
1. En la parte inferior de la página, escribe un mensaje de confirmación breve y significativo que describa el cambio que has realizado en el archivo.
1. Haz clic en **Commit changes**.
1. Espera unos 20 segundos y luego actualiza esta página para el siguiente paso.

</details>

<!--
  <<< Author notes: Paso 2 >>>
  Start this Paso by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

<details id=2>
<summary><h2>Paso 2: Añade una imagen</h2></summary>

_Buen trabajo añadiendo esos encabezados_ :sparkles:

Vamos a añadir una imagen. Incluye un texto descriptivo entre los corchetes. Este texto se lee en voz alta para las personas que utilizan lectores de pantalla. También se muestra en los momentos en que tu imagen no se muestra, como cuando hay una mala conexión. Puedes ver la sintaxis de las imágenes a continuación:

### Ejemplo

```md
![Imagen del Yaktocat](https://octodex.github.com/images/yaktocat.png)
```

#### Qué aspecto tiene

<img alt="Image of Yaktocat" src=https://octodex.github.com/images/yaktocat.png width=400>

### :keyboard: Actividad: Añadiendo una imagen

1. Como hiciste antes, edita el archivo `index.md` de esta solicitud de extracción.
1. En el archivo, añade el Markdown correcto para la imagen de tu elección. No olvides incluir el texto alternativo.
1. Utiliza la pestaña **Preview** para comprobar el aspecto que tendá tu formato Markdown.
1. Confirma los cambios.
1. Espera unos 20 segundos y actualiza esta página para el siguiente paso.

</details>

<!--
  <<< Author notes: Paso 3 >>>
  Start this Paso by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

<details id=3>
<summary><h2>Paso 3: Añade un ejemplo de código</h2></summary>

_Buen trabajo añadiendo esa imagen_ :tada:

Además de los bloques de código, algunos bloques de código deben renderizarse de forma diferente según el lenguaje, como JavaScript o el texto de la línea de comandos.

### Ejemplo

<pre>
```
$ git init
Initialized empty Git repository in /Users/skills/Projects/recipe-repository/.git/
```
</pre>

#### Qué aspecto tiene

```
$ git init
Initialized empty Git repository in /Users/skills/Projects/recipe-repository/.git/
```

### :keyboard: Actividad: Añadiendo un ejemplo de código

1. Al igual que antes, edita el archivo de este pull request.
1. En el archivo, añade el Markdown correcto para un ejemplo de código de tu elección.
1. Utilice la pestaña **Preview** para comprobar el formato de Markdown.
1. Confirma los cambios.
1. Espera unos 20 segundos y actualiza esta página para el siguiente paso.

</details>

<!--
  <<< Author notes: Paso 4 >>>
  Start this Paso by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

<details id=4>
<summary><h2>Paso 4: Haz una lista de tareas</h2></summary>

_Gran trabajo añadiendo un ejemplo de código_ :partying_face:

**¿Qué es una _lista de tareas_?** Una lista de tareas crea casillas para marcar. Son muy útiles para el seguimiento de las incidencias (o _issues_) y pull requests. Si incluyes una lista de tareas en el cuerpo de una incidencia o pull request, verás un indicador de progreso en tu lista de incidencias. La sintaxis de las listas de tareas es muy específica. Asegúrate de incluir los espacios donde se requieren, o de lo contrario no se mostrarán.

### Ejemplo

```
- [x] Las listas requieren una sintaxis muy concreta
- [x] Este elemento está completado
- [ ] Este elemento está sin completar
```

#### Qué aspecto tiene

- [x] Las listas requieren una sintaxis muy concreta
- [x] Este elemento está completado
- [ ] Este elemento está sin completar

### :keyboard: Actividad: Añade una lista de tareas

Las acciones de GitHub se adelantaron y crearon una rama y un pull request para ti. Así que tendrás que añadir el contenido al archivo que hemos creado en la rama, y comprobaremos tu progreso a medida que trabajes en este curso.

1. Vuelve a tu pull request.
1. Usa Markdown para crear una lista de tareas. Aquí tienes un ejemplo:
  ```md
   - [ ] Activar GitHub Pages
   - [ ] Hacer un esbozo de mi portfolio
   - [ ] Pesentarme al mundo
   ```
  Recuerda, una lista de tareas comienza con la sintaxis `- [ ]` y luego el elemento de la lista de tareas. ¡El formato debe ser preciso!
1. Utiliza la pestaña **Preview** para comprobar el formato de Markdown.
1. Confirma los cambios en el archivo.
1. Espera unos 20 segundos y actualiza esta página para el siguiente paso.

</details>

<!--
  <<< Author notes: Paso 5 >>>
  Start this Paso by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

<details id=5>
<summary><h2>Paso 5: Fusiona tu pull request</h2></summary>

_Gran trabajo añadiendo una lista de tareas a tu archivo_ :heart:

Ya puedes [fusionar](https://docs.github.com/get-started/quickstart/github-glossary#merge) tu pull request!

### :keyboard: Actividad: Fusiona tu pull request

1. Haz clic en **Merge pull request**.
1. Espera unos 20 segundos y actualiza esta página para el siguiente paso.

</details>

<!--
  <<< Author notes: Finish >>>
  Review what we learned, ask for feedback, provide next steps.
-->

<details id=X>
<summary><h2>Finalización</h2></summary>

_¡Enhorabuena, has completado el curso!_

<img src=https://octodex.github.com/images/welcometocat.png alt=celebrate width=300 align=right>

Aquí tienes un recuento de todas las tareas que has realizado en tu repositorio:

1. Has aprendido sobre Markdown, encabezados, imágenes, ejemplos de código y listas de tareas.
1. Has creado y fusionado un archivo Markdown.
1. Aprendiste una habilidad esencial de GitHub. 🎉

### ¿Y ahora, qué?

- ¡Puedes habilitar GitHub Pages y ver tu archivo Markdown como un sitio web!
  1. Debajo del nombre de tu repositorio, en la parte superior derecha, haz clic en :gear: **Settings**.
  1. Luego, en la parte inferior izquierda, haz clic en **Pages**.
  1. En la sección **GitHub Pages**, utiliza el menú desplegable **Source** para seleccionar `main` como tu fuente de publicación de páginas de GitHub.
  1. Haz clic en el botón **Save**.
  1. Espera unos 30 segundos y luego actualiza la página. Cuando veas "Your site is published ad ..." puedes hacer clic en el enlace para ver tu sitio publicado.
- Más información sobre [Markdown](https://docs.github.com/github/writing-on-github).
- Nos encantaría saber qué te ha parecido este curso [en nuestro foro de debate](https://github.com/skills/.github/discussions)
- [Haz otro curso de GitHub Skills](https://github.com/skills).
- Lee los [documentos de inicio con GitHub](https://docs.github.com/get-started).
- Para encontrar proyectos a los que contribuir, consulta [GitHub Explore](https://github.com/explore).

</details>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/skills/.github/discussions) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2022 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [CC-BY-4.0 License](https://creativecommons.org/licenses/by/4.0/legalcode)
