[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/M1f6lxRo)
# :wave: GitHub: introducción

## 🤓 Idea general de este curso y aprendizaje que se obtendrá

 🚀
El objetivo de este curso es darte una introducción sencilla a GitHub. También se te proporcionan recursos para continuar el aprendizaje y unas pocas ideas para empezar a manejar esta plataforma.

## :octocat: Git y GitHub

Git es un **Sistema distribuido de Control de Versiones**, en inglés **distributed Version Control System (VCS)**, lo que significa que se usa para llevar control de los cambios que se van haciendo en tus programas, para hacerlo colaborativamente, y para compartir el código. Con Git puedes hacer seguimiento de los cambios que se hacen en un proyecto, de manera que siempre tenemos registro de en qué hemos trabajado, y se pueden deshacer estos cambios fácilmente, volviendo a una versión anterior si es necesario. También facilita trabajar con los demás. Grupos de colaboradores pueden trabajar juntos en el mismo proyecto y unir sus cambios en la versión final.

GitHub es una herramienta que proporciona la misma capacidad de Git, pero desde una web online, para que sea más fácil de usar. Se usa extensamente en todo el mundo, entre desarrolladores de software, para participar en proyectos y para conservar una copia "historica" de los mismos.

GitHub es el lugar donde se alojan algunas de las tecnologías más avanzadas del mundo. Ya sea que estés visualizando datos o creando un nuevo juego, habrá una comunidad y un conjunto de herramientas en GitHub que te pueden ayudar a avanzar en tu tarea. Este curso comienza con los aspectos básicos de GitHub, pero se profundizará más tarde en lo demás.

## :octocat: El flujo de trabajo de GitHub

El flujo de trabajo de GitHub es sencillo, y permite experimentar con los cambios y realizar colaboraciones con facilidad, sin riesgo de perder el trabajo previo.

### Repositorios

Un repositorio es el sitio que almacena un proyecto. Se puede pensar en él como si fuera el armario o el archivador de ese proyecto, la carpeta de ese proyecto. Contiene totos los archivos del proyecto y el historial de cambios. Se puede trabajar en un repositorio siendo una sola persona, o invitar a otros a colaborar para que modifiquen esos archivos.

### Clonar

Cuando se crea un repositorio con GitHub, el almacenamiento está en la nube ☁️. Puedes clonar ese repositorio para crear una copia local en tu ordenador, y después usar **git** para sincronizarlos. Así es más fácil reparar los errores, y añadir o borrar archivos, o hacer cambios múltiples de golpe. Además, también se puede usar la herramienta de edición que prefieras, al contrario que si editas desde la web de GitHub. Al clonar un repositorio, se obtienen todos los datos de control que hay en GitHub acerca de ese proyecto en ese momento, incluyendo todas las versiones de cada archivo y carpeta. Esto sirve de gran ayuda, ya que si experimentamos con el funcionamiento de una modificación podemos darnos cuenta de que alguna versión anterior era mejor que la actual.
Para aprender más sobre el clonado, leer ["Cloning a Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

### Commit y push
**Commit** y **push** son las instrucciones con las que se hacen efectivos los cambios de tus archivos y se suben desde tu máquina hacia el repositorio online "remoto" en GitHub. De esta manera, los compañeros de equipo y el dueño del repositorio pueden ver tus últimas modificaciones. Se hace un "commit" cuando has hecho una serie de modificaciones que quieres someter a la comprobación por parte de tus compañeros. En esta instrucción se agrega normalmente un mensaje, **commit message** para que sirva de recordatorio del trabajo que se ha modificado (Por ejemplo, "he añadido un archivo README con información de los objetivos de nuestro programa para los lectores externos").

Cuando ya hemos acumulado varios commit (o solo uno si no hacen falta más), se debe usar la instrucción **push** para guardar esos cambios en el repositorio de GitHub. Estas dos instrucciones pueden parecer raros al principio, pero os vais a acostumbrar muy pronto. 🙂

## 💻 vocabulario GitHub imprescindible

### Repositorio
Como se ha dicho antes, es donde se almacena el proyecto -archivos y carpetas, y también llevala cuenta de los cambios hechos-. Veámoslo en más detalle. Conforme vamos trabajando en GitHub cada vez tendremos más repositorios, y eso es confuso al principio. Afortunadamente, tu ["Escritorio GitHub"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) permite navegar fácilmente por tus repositorios y ver la información necesaria sobre cada uno. ¡Asegúrate de estar identificado para poder verlo!

Los repositorios suelen contener archivos **README**. Sirven para dejar escrita la explicación básica del proyecto, para que la gente que entra sepa para qué sirve este proyecto, qué pueden hacer con él, y cómo se manejan sus archivos. Esto que estás leyendo ahora es un archivo README. 😄 
Para aprender más acerca de los repositorios, leed ["Creating, Cloning, and Archiving Repositories](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) y ["About README's"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes). 

### Ramas ("Branches")
Las ramas guardan de manera separada los cambios que no queremos mezclar todavía en el proyecto final. cada "branch" te permite probar características nuevas en las que todavía no hemos combrobado el funcionamiento, corregir errores anteriores, o experimentar de manera segura con nuevas ideas en un área separada que no afecte a lo que ya funciona. De manera normal, uno debe crear una rama nueva desde la rama principal del repositorio para empezar a trabajar con cualquier retoque. En esa rama creamos los cambios.A continuación hacemos un "commit" y "push", para compartir esa nueva rama con un compañero para que la compruebe si funciona, nos dé sugerencias, y después, si se considera adecuado, mezclarla con la rama principal y borrar (o no) la que habíamos creado.
Para aprender más sobre ramas, leed ["About Branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### Bifurcaciones (Forks)
Una bifurcación o "fork" es otra manera de copiar un repositorio, pero se usa normalmente cuando uno quiere contribuir al proyecto de otra persona. Al hacer una copia bifurcada, se puede experimentar libremente con cambios sin que afecte en absoluto al proyecto original. De hecho, es una forma de actuar muy extendida.
Lee ["Fork a repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo) para aprender más acerca de fork.

### Pull requests (peticiones de agregación de cambios)
Al trabajar con ramas, uno debe usar las peticiones de "pull" para informar a los colaboradores acerca de los cambios que está creando para pedirles su opinión sobre los mismos, antes de sumar estos cambios a la rama en la que estamos trabajando. Una vez que se abre una petición, podemos discutir y revisar los cambios potenciales con nuestro equipo, y si las pruebas o comentarios lo aconsejan, añadir más cambios. Se pueden agregar personas concretas para que revisen nuestro trabajo, solicitud que ellos recibirán y decidirán si aceptar. Una vez que se han revisado estos cambios, podremos mezclarlos con la rama principal del proyecto.
para aprender más sobre este tema, leed ["About Pull Requests"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests). 


### Asuntos (Issues)
Las Issues son un mecanismo para llevar seguimiento de errores, tareas, o ideas de mejoras que hay que trabajar. Son idóneas para registrar y controlar todas las cosas que se tienen que ir haciendo, a la vez que mantienen informados a los demás de los trabajos en marcha o planificados. Se usan también para dar a conocer a los miembros de otros proyectos de que hemos encontrado un error en su proyecto, o para solicitarles una mejora que se nos ha ocurrido.
En proyectos mas grandes, se puede controlar una gran cantidad de tareas en un panel de proyecto. Un proyecto de GitHub permite organizar y priorizar tareas, tal y como se puede ver leyendo [in this "About Project boards document](https://docs.github.com/en/github/managing-your-work-on-github/about-project-boards). Lo más normal es que no necesitemos un tablero para nuestras tareas las primeras veces, pero una vez que se empieza con proyectos grandes, son muy útiles para organizar el trabajo del equipo.

Se pueden enlazar juntas las issues y las peticiones de agregación para hacer ver que una mejora del código del programa está en progreso, y que se cierre ese asunto cuando alguien mezcle la petición de cambio con los documentos del repositorio iniciales.
Para aprender más acerca de esto, leed ["About Issues"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues). 

### Perfil de usuario
Tu perfil le cuenta a la gente en qué trabajas y cuáles son tus intereses, mostrando los repositorios que te interesan, las contribuciones que has hecho, o las conversaciones en las que has participado. Puedes personalizar todavía más cómo los demás acceden a esta información gracias a un documento README que puede incluirse en el perfil. Es algo muy recomendable, sobre todo si deseamos abrirnos al mercado laboral.

Para aprender más, y para añadir y mantener actualizado un archivo README de nuestro perfil, leed ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme). 

### El lenguaje markdown en GitHub 
Seguramente ya te has dado cuenta de que se puede incluir algo de estilo agradable a las tareas o asuntos, a las peticiones de cambio y, en general, a los documentos. ["Markdown"](https://guides.github.com/features/mastering-markdown/) es la forma fácil de aplicar estilos, ya que su sintáxis es simple. Así la información queda perfectamente expuesta de cara a los lectores. Permite incluso insertar imágenes gif (o normales) que hagan más atractivas y útiles las explicaciones.
para aprender cómo se usa Markdown en GitHub, leed ["Basic Writing and Formatting Syntax"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax). 

### Engaging with the GitHub community
La comunidad de GitHub es muy grande. Hay personas de diverso perfil que lo usan a diario. Desde estudiantes, como tú, hasta programadores profesionales, pasando por aficionados a construir o participar en proyectos de código abierto, o exploradores de la red que se embarcan en el aprendizaje de la programación de manera autónoma. Hay muchas formas de participar, aunque estas tres son una buena opción para empezar:

#### Marcar con estrellas algunos repositorios
Si encuentras un repositorio que te parece interesante, o del que quieres estar al tanto de sus progresos, le puedes asignar una estrella, para indicar que lo sigues. GitHub usará estamarca para ofrecerte mejores recomendaciones en la pestaña github.com/explore. Si deseas revisar tus repositorios favoritos, basta con navegar hasta tu perfil.

Para saber más, ["Saving Repositories with Stars"](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with-stars). 

#### Seguir a usuarios
Puedes seguir a otros usuarios de GitHub, y recibir notificaciones con su actividad, descubriendo así proyectos en comunidades en las que participan. La actividad de estos usuarios aparece en tu escritorio ("dashboard").

Profundiza en esto leyendo ["Following People"](https://docs.github.com/en/github/getting-started-with-github/following-people).

#### Navegar por GitHub Explore 

GitHub Explore es el lugar perfecto para eso, explorar. :smile: Descubrirás nuevos proyectos, eventos y programadores con los que interactuar.

Compruébalo pinchando en [at github.com/explore](https://github.com/explore). Cuanto más te relaciones con la comunidad, mejores resultados obtendrás.

## 📝 Proximos pasos opcionales

* Abre una petición de pull para indicar a tu profesor que ya has terminado este cursillo de introducción.
* Crea un archivo markdown nuevo. Cuenta en él qué es lo que has aprendido y qué cosas no están claras todavía. Experimenta con estilos.
* Crea tu README en tu perfil. Déjanos conocerte un poco. ¿Qué es lo que quieres aprender? ¿En qué trabajas actualmente? ¿Cuál es tu hobby predilecto? Lee el documento ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme) si necesitas ayuda para crear este archivo.
* Id a vuestro escritorio y cread un repositorio nuevo. Experimentad con todo lo que tiene un repositorio, para familiarizaros con su manejo.
* [Let us know what you liked or didn’t like about the content of this course](https://support.github.com/contact/education). ¿Qué más consideras que conviene ampliar?  ¿Qué puede ser interesante para mejorar tu aprendizaje?

## 📚  Mas recursos
* [A short video explaining what GitHub is](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be) 
* [Git and GitHub learning resources](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources) 
* [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
* [How to use GitHub branches](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Interactive Git training materials](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Education community forum](https://education.github.community/)
* [GitHub community forum](https://github.community/)
