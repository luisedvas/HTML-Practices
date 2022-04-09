<!DOCTYPE html>
<html lang="en-US">
  <head>
      <meta charset="UTF-8">
      <title><strong>Practices in HTML & CSS</strong></title>
      <link href="style.css" type="text/css" rel="stylesheet">
  </head>
  <main>
    <body>
      <header>
        <h1><strong>Practices in HTML & CSS</strong></h1>
      </header>
        <img class="imagen-cambios" src="https://www.htmlandcssbook.com/images/slideshow-home/triplicate.jpg"  width="500" alt="HTML & CSS">
      <section class="primer-parrafo">
        <article>
          <p>Hoy 08 de abril mi progreso ha aumentado considerablemente en <strong>HTML & CSS</strong>, teniendo en cuenta que he terminado algunas lecciones en <strong>Freecodecamp & Codecademy</strong></p>
        </article>
      </section>
      <section class="segundo-parrafo">
        <article>
          <p>Algunas de las páginas que utilizo para aprender a programar por ahora son:</p>
        </article>
      </section>
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
            <p><a href="https://www.freecodecamp.org/" target="_blank">Freecodecamp</a> es un sitio web gratuito que ofrece prácticas  en distintos lenguajes de programación, como <strong>HTML, CSS & JavaScript</strong>.</p>
          </article>
      </section>
      <section id="codecademy">
        <h2><strong>Codecademy</strong></h2>
          <article>
            <p><a href="https://www.codecademy.com/" target="_blank">Codecademy</a>, por el contrario, ofrece alternativas entre recursos gratuitos y pagos, mediante <strong>suscripciones mensuales y anuales</strong> que permiten aprender programación</p>
          </article>
      </section>
      <section id="ironhack">
        <h2><strong>Ironhack</strong></h2>
          <article>
            <p><a href="https://www.ironhack.com/en" target="_black">Ironhack</a> es una escuela global enfocada en la metodologia Bootcamp de una manera muy intensiva y la cual ofrece cursos en <strong>Web Development</strong></p>
          </article>
      </section>
      <section id="platzi">
        <h2><strong>Platzi</strong></h2>
          <article>
            <p><a href="https://platzi.com/" target="_blank"><strong>Platzi</strong></a> ofrece miles de cursos de marketing, inglés, programación, y una variedad de cursos efectivos impartidos por líderes de la industria de la tecnología.
a</p>
          </article>
      </section>
      <hr>
    <section class="tercer-parrafo">
      <figure>
        <figcaption><u>Recordatorio</u> de que quiero ser asi dentro de unos meses a patir de ahora, por lo cual, practicaré todos los días lo aprendido:</figcaption>
      </figure>
    </section>
      <a href="https://twitter.com/nateliason/status/1505207670789353472?s=20&t=wt18qsNwQRdKL4D2NXe9Ng" target="_blank"><img src="https://pbs.twimg.com/media/FOOSUsJXwAkvjGS?format=jpg&name=medium"></a>
        <article class="fondo-parrafo">
          <p>Además de eso haré una lista de los recursos necesarios para tenerlos a la mano en las siguientes aplicaciones y repositorios:</p>
    <nav>
      <ol>
        <li><a href="#github" class="links"><strong>GitHub</strong></a></li>
        <li><a href="#notion" class="links"><strong>Notion</strong></a></li>
        <li><a href="#obsidian" class="links"><strong>Obsidian</strong></a></li>
      </ol>
    </nav>
    </article>
      <section>
        <img id="github" src="https://kinsta.com/es/wp-content/uploads/sites/8/2018/05/qu%C3%A9-es-github-1.png" width="600">
      </section>
      <section>
        <img id="notion" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSAa7Rm2qg6nqv-I18u0Kyk5Hu4yb9BWs-xixvf-X3sk-IFC1W4I9DIQJVbDpmM7CI4qLM&usqp=CAU" width="600">
      </section>
      <section>
        <img id="obsidian" src="https://windows-cdn.softpedia.com/screenshots/Obsidian-app_1.png" width="600">
      </section>
      <hr>
    <article class="caja">
      <h3 class="snippet-text"><strong>Languages</strong></h3>
      <h4 class="caja yellow-box"><strong>HTML</strong></h4>
      <h4 class="caja blanco-box"><strong>CSS</strong></h4>
      <h4 class="caja red-box"><strong>JavaScript</strong></h4>
      <h4 class="caja green-box"><strong>Python</strong></h4>
    </article>
    <article class="box white-box">
      <h4 class="snippet-text">Links</h4>
      <h5 class="box black-box">Load More</h5>
      <h5 class="box black-box">All Rights Reserved</h5>
    </article>
    <br>
          <fieldset>
            <legend>Qué tipo de lenguaje de programción utilizas?</legend>
              <input id="js" type="radio" name="levels" value="js">
              <label for="js">JavaScript</label><br>
              <input id="java" type="radio" name="levels" value="java">
              <label for="java">Java</label><br>
              <input id="python" type="radio" name="levels" value="python">
              <label for="python">Python</label><br>
          </fieldset>
      <form>
        <p><strong>Write your email below to receive more updates about me</strong></p>
        <label>Email:</label>
          <input type="text" id="email" name="email">
          <input type="submit" id="submit" name="submit">
        <label for="pickdate">Selecciona fecha </label>
          <input type="date" id="pickdate" name="date">
      </form>
        <br>
        <footer><strong>&copy; 2022, Luis Eduado Díaz</strong></footer>
      </body>
    </main>
  </html>
