# portofolio

[voir l'index](https://lahuts.github.io/)

## html de l'index du portofolio
```html
<!DOCTYPE html>
<html lang="fr">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./css/style.css" />
    <link rel="icon" type="image/x-icon" href="/asset/FAVICON.ico" />
    <meta name="author" content="Alexis Huet">
    <meta name="description" content="Portofolio developpeur web  hmtl css Alexis Huet">
    <title>Huet Alexis Dev</title>
  </head>
  <body>
    <header>
      
      <div class="wrapper">
        <a href="index.html"><img src="asset/logo_white.svg" alt="logo AH" /></a>
        <div class="text">
        <h1>> Portfolio Alexis Huet</h1>
        </div>
      </div>
    </header>
    <nav>
      <ol>
        <li><a href="#competence"><img src="asset/logo_comp.svg" alt="logo competence" />Compétences</a></li>
        <li><a href="#ide"><img src="asset/logo_logiciel.svg" alt="logo Logiciel" />Logiciel</a></li>
        <li><a href="#experience"><img src="asset/logo_pro.svg" alt="logo competence" />Expériences</a></li>
        <li><a href="#etude"><img src="asset/logo_etude.svg" alt="logo étude" />Études</a></li>
        <li><a href="#loisirs"><img src="asset/logo_sport.svg" alt="logo competence" />Loisirs</a></li>
      </ol>
    </nav>

    <main>
      <section id="competence">
        <h2>Compétences</h2>
        <ul>
          <li> - Conception et développement de site web</li>
          <li> - Comprehension des contraintes de projet (délais, budget, attentes)</li>
          <li> - Créatif et imaginatif pour trouver de nouvelles solutions et innover</li>
          <li> - Bonne culture générale en informatique</li>
        </ul>
      </section>
      <section id="ide">
        <h2>Logiciel / IDE</h2>
        <div id="grid-ide">
          <figure>
            <img src="asset/CSHARP.png" alt="Logo C Sharp">
            <figcaption>C#</figcaption>
          </figure>
        <figure>
          <img src="asset/CSS.png" alt="Logo Css">
          <figcaption>CSS</figcaption>
      </figure>
        <figure>
          <img src="asset/HTML5.png" alt="Logo html">
          <figcaption>HTML</figcaption></figure>
        <figure>
          <img src="asset/JAVA.png" alt="Logo JAVA">
          <figcaption>JAVA</figcaption>
        </figure>
      </div>
      </section>
      <section>
        <h2> Expériences professionelle </h2>
        <div id="experience">
          <p>
            2014 <br>
            Ac Nego : Assisant sérigraphe <br>
            - Création de logotype <br>
            - impression sur textile <br>
            - Réalisation de présentation corporate et à destination des commerciaux <br>
          </p>
          <p>
            2015 <br>
             Bignon S.A : Assistant maquettiste <br>
            - Conception de different support d'édition (flyers,plaquette,..) <br>
            - gestion de l'impressionet de la fabrication <br>
            <br>
            <p>
            2016  <br> HITMEDIA : Assistant infographiste <br>
            - Retouche photographique <br>
            - Création de charte Visuelle <br>
            - Mise en situation de projet client <br>
          </p>
        </div>
        </section>
        <section>
          <h2 id="etude">Études</h2>
          <ul>
            <li>2021 :  BTS Services informatiques aux organisations ,Itic Paris</li>
            <li>2018 : Licence Histoire de l'art - La Sorbonne , Paris</li>
            <li>2017 : FCIL Scénographie de la communication - Alfred Costes , Bobigny </li>
            <li>2016 : Bac Pro Communication Visuelle - Alfred Costes , Bobigny </li>
          </ul>
        </section>
        <section>
          <h2 id="loisirs">Loisirs</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti voluptas similique pariatur, fugit repellat culpa!</p>

        
      </section>
    </main>
    <footer>
      <p>
        &copy; -Portfolio - <a href="mailto:alexis.huet.m@gmail.com" >Alexis Huet</a> - 2021
      </p>
    </footer>
  </body>
</html>

```

## css style pour l'index
```css
/* 
reset css
*/
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@700&display=swap');
html {
  font-size: 62.5%;
}
body {
  font: 1.6rem sans-serif;
  margin: 0;
}

h1,h2,h3,h4,p,ul,ol,main,
nav {
  margin: 0;
  padding: 0;
  list-style-type: none;
  font-weight: normal;
}
h1,h2 {
  font-weight: 100;
}
a {
  text-decoration: none;
}

/*theme*/



:root{
  --primary--color:#1d1d1d;
  --secondary--color:rgb(92,128,228);
  --font-color-primary:#000;
  --font-color-secondary:#fff;
}
body{
  background-color: var(--primary--color);
  color: #fff;
}

header {
  padding-top: 1rem;
  padding: 1em;
  background-color: var(--primary--color);
  color: var(--font-color-secondary);
  overflow: hidden;
}
main {
  font-family: 'Open Sans'sans-serif;
  
  
}
header>div>a>img {
  width: 10rem;
  height: 10rem;
}

h1 {
  text-align: center;
}
nav {
  text-align: center;

}
nav > ol {
  padding: 1.5rem;
}

nav > ol > li {
  display: inline-block;
}
nav>ol>li>a{
  display: flex;
  flex-direction: column;

}
li > a {
  border: #fff 0px ;
  padding: 1.5rem;
  color: var(--font-color-secondary);
}
li>a>img{
  height: 10rem;
  width: 10rem;
}
section > h2 {
  margin-top: 2rem;
  background-color: var(--secondary--color);
  color:var(--font-color-secondary);
  padding: 0.7rem;

  text-align: center;
  padding-left: 5rem;
}
section:nth-child(2)>div{
  padding: 1.0rem;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-gap: 1rem;
}
figure{
  width: 100px;
  margin-left: 3rem;
  margin-right: 3rem;
  margin-top: 2rem;
}
figure>img{
  display: block;
  width: 10rem;
  height: 10rem;
  margin-left: 2rem;
}

figcaption{
  padding-top: 1em;
  padding-left: 2.2em;
  text-align: center;
}
section > ol {
  margin-top: 0.5em;
}
section > p {
  margin-top: 1em;
  padding: 2em;
}
section>ul{
  margin-top: 1em;
  padding: 2em;
  line-height: 1.4em;
}


footer {
  margin-top: 10rem;
  text-align: center;
  margin-bottom: 4rem;
}
footer {
  color: var(--font-color-secondary);
  font-weight: bold;
}
footer > p > a {
  color: var(--font-color-secondary);
}


#experience{
  padding: 4.0rem;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 1rem;
}
#experience>p{
  text-align: center;
  line-height: 1.6em;
}

/* Test css Animation*/


.wrapper {
  height: 75vh;
  /*This part is important for centering*/
  display: flex;
  align-items: center;
  flex-flow: column;
  justify-content: flex-start;
}

.text {
  width: 46ch;
  animation: typing 2s steps(32), blink .5s step-end infinite alternate;
  white-space: nowrap;
  overflow: hidden;
  border-right: 3px solid;
  font-family: monospace;
  font-size: 2em;
  justify-self: center;
}
header>div>a{
  margin-bottom: 10rem;
  margin-top: 18rem;
}

nav>ol>li>a:hover{

  filter: invert(48%) sepia(21%) saturate(1365%) hue-rotate(187deg) brightness(100%) contrast(100%);
  color:var(--secondary--color);
}



/*Test  animation */
@media screen and (max-width: 800px) {

  main{
    padding: 0px;
    
  }
  header>div>a{
    margin-bottom: 5rem;
    margin-top: 0rem;
  }
  section>h2{
    padding-left: 1rem;
    padding-top: 1rem;
    padding-bottom: 1rem;
    text-align: center;
  }
  section>p{
    text-align: center;
    padding: 1.5rem;
  }
  section>ul{
    margin-top: 1em;
    padding: 1em;
    line-height: 1.4em;
  }

  section:nth-child(2)>div{
    margin: 0;
    width: 100%;
    padding: 0.25rem;
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      grid-gap: 0.25rem;
      overflow: hidden;
  }
  nav{
    display: none;
  }

  #grid-ide{
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(2, 1fr);
    grid-gap: 1rem;
  }

  #experience{
    margin: 0px;
    display: grid;
    grid-template-columns: repeat(1, 1fr);
    grid-gap: 1rem;
  }

  .wrapper {
    height: 70vh;
    /*This part is important for centering*/
    display: flex;
    justify-content:center;
    flex-flow: column;
    align-items: center;
  }

  .text {
    width: 46ch;
    animation: typing 1s steps(22), blink .5s step-end infinite alternate;
    white-space: nowrap;
    overflow: hidden;
    border-right: 3px solid;
    font-family: monospace;
    font-size: 0.7em;
  }
/* L' animation d'ecriture */
@keyframes typing {
  from {
    width: 0px;
  }
}
/* La barre */
@keyframes blink {
  50% {
    border-color: transparent
  }
  
}

#competence,#ide,#experience:target{
  display: block;
  animation: scroll;
  transition: 2s;
}
}
```
