<p align="center">
<img src="http://codeandomexico.org/resources/img/codeandomexico.png" width="500" alt="Codeando México"><br>
<a href="http://www.codeandomexico.org/" target="_blank"><img src="https://img.shields.io/badge/website-CodeandoMexico-00D88E.svg"></a>
<a href="http://slack.codeandomexico.org/" target="_blank"><img src="https://img.shields.io/badge/slack-CodeandoMexico-EC0E4F.svg"></a>
</p>


# Recursos sobre Datos Abiertos

**tl;dr:** Una lista curada de recursos para estrategia, gobernanza y apertura de datos.


## Tabla de contenidos

- [Acerca del proyecto](#acerca-del-proyecto)
- [Contribuye](#contribuye)
- [Atribuciones](#atribuciones)


## Acerca del proyecto

Este es un proyecto de la comunidad que busca centralizar recursos, herramientas, metodologías y más sobre datos abiertos a nivel nacional e internacional para impulsar la apertura de datos.

Si te interesa contribuir al proyecto, echa un vistazo a la siguiente sección.


## Contribuye

¡Cualquier sugerencia o contribución a este repositorio es bien recibida!

Si necesita ayuda, escribe directamente a <equipo@codeandomexico.org> o en nuestro [Slack](http://slack.codeandomexico.org/).

### Añade un evento

1. Crea un fork del repositorio a tu cuenta de GitHub.

2. Clona tu fork del repo:
   ```bash
   git clone https://github.com/<TU-USUARIO>/eventos-globales.git
   cd awesome-open-data/
   ```

3. Crea una rama con el nombre del recurso que deseas agregar, en este ejemplo supongamos que agregaré la [plantilla](https://github.com/CodeandoMexico/awesome-open-data/blob/master/_posts/2020-01-22-plantilla.md) del sitio:
   ```bash
   git checkout -b plantilla  # esto creará una nueva rama de nombre 'plantilla' y se moverá a ella
   ```

4. Crea el archivo que contenga la información del recurso. El archivo deberá ser guardado en la carpeta [`_posts`](https://github.com/CodeandoMexico/awesome-open-data/tree/master/_posts) con el formato `AAAA-MM-DD-nombre-del-recurso.md`, donde `AAAA`, `MM` y `DD` corresponden al año, mes y día en que se agrega el recurso al directorio, respectivamente. Puedes tomar como referencia justamente el archivo [plantilla](https://github.com/CodeandoMexico/awesome-open-data/blob/master/_posts/2020-01-22-plantilla.md).

5. Crea un Pull Request (PR) de la rama que has creado a la rama `master` del repositorio original y solicita una revisión a **@ricardomiron**.

**NOTA:** Por favor realiza un PR por recurso que desees agregar.


### Modifica el sitio

Por favor abre un issue donde menciones los cambios que te gustaría agregar y menciona a **@ricarodmiron**. En dado caso, se te asignaría el issue y esperaremos tu PR donde te pediremos solicites una revisión a **@ricarodmiron** para revisar y aceptar tus cambios al sitio.

Si deseas correr el sitio de manera local, ejecuta los siguientes pasos:

1. Instala los requerimientos:
   ```bash
   bundle install
   ```

2. Corre el servidor:
   ```bash
   bundle exec jekyll serve
   ```

3. Abre <http://localhost:4000/awesome-open-data> en tu navegador.

El comando del paso 2 te permite hacer modificaciones y visualizar los cambios en tiempo real dentro de tu localhost.


## Atribuciones

- Sitio web basado en [Pintereso Jekyll Theme](https://www.wowthemes.net/pintereso-free-bootstrap-jekyll-theme/)
- Gracias a [Ricardo](https://github.com/ricardomiron) y [Lalo](https://github.com/fullmakeralchemist) por las contribuciones iniciales
- `{}` y contenidos con ❤️ por la [comunidad de Codeando México](http://slack.codeandomexico.org/)

---

Este sitio cuenta con una licencia MIT.
