<!DOCTYPE html>
<html lang="en-US">
  <head>
      <meta charset="UTF-8">
      <title><strong>Prácticas en HTML & CSS</strong></title>
      <link href="style.css" type="text/css" rel="stylesheet">
  </head>
  <main>
  <body>
    <header>
    <h1><strong>Prácticas en HTML & CSS</strong></h1>
    </header>
      <img class="imagen-cambios" src="https://www.htmlandcssbook.com/images/slideshow-home/triplicate.jpg" width="500" alt="HTML & CSS" practices>
      <article class="primer-parrafo">
      <p>Hoy 07 de abril mi progreso ha aumentado considerablemente en HTML & CSS, teniendo en cuenta que he terminado algunas lecciones en FreeCodeCamp & Codecademy</p>
      </article>
      <article class="segundo-parrafo">
      <p><strong>Algunas de las paginas que utilizo para aprender a programar por ahora son:</strong></p>
      </article>
      <nav>
        <ul>
          <li><a href="#freecodecamp" class="links"><strong>FreeCodeCamp</strong></a></li>
          <li><a href="#codecademy" class="links"><strong>Codecademy</strong></a></li>
          <li><a href="#ironhack" class="links"><strong>Ironhack</strong></a></li>
          <li><a href="#platzi" class="links"><strong>Platzi</strong></a></li>
        </ul>
      </nav>
      <hr>
      <section id="freecodecamp">
      <h2><strong>Freecodecamp</strong></h2>
      <article>
      <p>FreeCodeCamp es un sitio web gratuito que ofrece practicas en distintos lenguajes de programación, como HTML, CSS & JavaScript</p>
      </article>
      </section>
      <section id="codecademy">
        <h2><strong>Codecademy</strong></h2>
      <article>
        <p>Codecademy, por el contrario, ofrece alternativas y recursos gratuitos y pagos que permiten aprender programación</p>
      </article>
      </section>
      <section id="ironhack">
      <h2><strong>Ironhack</strong></h2>
      <article>
        <p>Ironhack es una escuela global enfocada en la metodologia Bootcamp de una manera muy inmersiva</p>
      </article>
      </section>
      <section id="platzi">
      <h2><strong>Platzi</strong></h2>
      <article>
        <p>Platzi es una escuela digital enfocada en distintas escuela de la tecnologia</p>
      </article>
      </section>
      <hr>
    <section class="tercer-parrafo">
      <figure>
    <figcaption><u>Recordatorio</u> de que quiero ser asi dentro de unos meses:</figcaption>
      </figure>
    </section>
      <a href="https://twitter.com/nateliason/status/1505207670789353472?s=20&t=wt18qsNwQRdKL4D2NXe9Ng" target="_blank"><img src="https://pbs.twimg.com/media/FOOSUsJXwAkvjGS?format=jpg&name=medium"></a>
      <article class="fondo-parrafo">
      <p>Para lo cual haré una lista de los recursos y notas necesarias para tenerlos a la mano en:</p>
      <nav>
      <ol>
        <li><a href="#github"><strong>GitHub</strong></a></li>
        <li><a href="#notion"><strong>Notion</strong></a></li>
        <li><a href="#obsidian"><strong>Obsidian</strong></a></li>
      </ol>
      </nav>
    </article>
      <section>
        <img src="https://kinsta.com/es/wp-content/uploads/sites/8/2018/05/qu%C3%A9-es-github-1.png" width="600">
      </section>
      <section>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSAa7Rm2qg6nqv-I18u0Kyk5Hu4yb9BWs-xixvf-X3sk-IFC1W4I9DIQJVbDpmM7CI4qLM&usqp=CAU" width="600">
      </section>
      <section>
        <img src="https://windows-cdn.softpedia.com/screenshots/Obsidian-app_1.png" width="600">
      </section>
      <hr>
    <article class="caja blue-box">
      <h3 class="snippet-text">Languages</h3>
      <h4 class="caja blanco-box">HTML</h4>
      <h4 class="caja yellow-box">CSS</h4>
      <h4 class="caja red-box">JavaScript</h4>
    </article>
        <article class="box white-box">
        <h4 class="snippet-text">Contacto</h4>
        <h5 class="box black-box">Load More</h5>
        <h5 class="box black-box">All Rights Reserved</h5>
      </article>
      <form>
        <p>Escribe tu correo para recibir las actualizaciones de mi perfil</p>
        <label>Email:</label>
        <input type="text" id="email" name="email">
        <input type="submit" id="submit" name="submit">
        <fieldset>
          <legend>Qué tipo de lenguaje de programción utilizas?</legend>
            <input id="js" type="radio" name="levels" value="js">
            <label for="js">JavaScript</label><br>
            <input id="html" type="radio" name="levels" value="html">
            <label for="html">HTML</label><br>
            <input id="css" type="radio" name="levels" value="css">
            <label for="css">CSS</label><br>
        </fieldset>
          <label for="pickdate">Fecha selecciona</label>
          <input type="date" id="pickdate" name="date">
      </form>
        <footer>&copy; 2022, Luis Eduado Díaz</footer>
      </body>
    </main>
  </html>
