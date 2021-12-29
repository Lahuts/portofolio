# portofolio

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
      <a href="#"><img src="asset/FAVICON.ico" alt="logo AH" /></a>
      <h1>Développeur Front & Back</h1>
    </header>
    <nav>
      <ol>
        <li><a href="#">Compétences</a></li>
        <li><a href="#">Logiciel</a></li>
        <li><a href="#">Expériences</a></li>
      </ol>
    </nav>

    <main>
      <section>
        <h2>Compétences</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quas,
          dignissimos. Cupiditate soluta odio et nisi distinctio quod dolores
          aut optio, officiis magni vitae voluptate. Saepe!
        </p>
      </section>
      <section>
        <h2>Logiciel / IDE</h2>
        <div>
          <figure><img src="asset/CSHARP.png" alt="Logo C Sharp"></figure>
        <figure><img src="asset/CSS.png" alt="Logo Css"></figure>
        <figure><img src="asset/HTML5.png" alt="Logo html"></figure>
        <figure><img src="asset/JAVA.png" alt="Logo JAVA"></figure>
      </div>
      </section>
      <section>
        <h2>Experiences</h2>
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nihil
          molestiae laudantium nostrum voluptas ipsam nisi, libero esse enim
          inventore iste? Eum eligendi optio in iusto?
        </p>
      </section>
      <section>
        <h2>Études</h2>
        <ul>
          <li>2019 : Lorem ipsum dolor sit.</li>
          <li>2018 : Lorem ipsum dolor sit.</li>
          <li>2017 : Lorem ipsum dolor sit.</li>
          <li>2016: Lorem ipsum dolor sit.</li>
        </ul>
      </section>
      <section>
        <h2>Loisirs</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Magni fuga
          molestiae, dignissimos voluptatum sapiente tempora quia corporis quas
          similique expedita repudiandae id sit est architecto?
        </p>
      </section>
    </main>
    <footer>
      <p>
        &copy; - Portofolio -<a href="mailto:alexis.huet.m@gmail.com" >Alexis Huet</a> - 2021
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
html {
  font-size: 62.5%;
}
body {
  font: 1.6rem sans-serif;
  margin: 0;
}

h1,
h2,
h3,
h4,
p,
ul,
ol,
main,
figure,
nav {
  margin: 0;
  padding: 0;
  list-style-type: none;
}
h1,
h2 {
  font-weight: normal;
}
a {
  text-decoration: none;
}

/*theme*/

:root{
  --primary--color:rgb(3, 33, 129);
  --secondary--color:rgb(59, 106, 235);
  --font-color-primary:#000;
  --font-color-secondary:#fff;
}

header {
  padding: 1em;
  background-color: var(--primary--color);
  color: var(--font-color-secondary)
}
main {
  padding-left: 6rem;
  padding-right: 6rem;
}
header>a>img {
  width: 5rem;
  height: 5rem;
  float: left;
}

h1 {
  text-align: center;
}
nav {
  background-color: var(--secondary--color);
}
nav > ol {
  padding: 1.5rem;
}

nav > ol > li {
  display: inline-block;
  padding-left: 4rem;
}
li > a {
  color: var(--font-color-secondary)
}
section > h2 {
  margin-top: 2rem;
  padding-left: 2rem;
  background-color: var(--secondary--color);
  color:var(--font-color-secondary);
  padding: 0.7rem;
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
section > ol {
  margin-top: 0.5em;
}
section > p {
  border: #000 solid 3px;
  margin-top: 1em;
  padding: 2em;
}
section>ul{
  border: solid var(--font-color-primary) 3px;
  margin-top: 1em;
  padding: 2em;
}

footer {
  margin-top: 10rem;
  text-align: center;
  margin-bottom: 4rem;
}
footer {
  color: var(--font-color-primary);
  font-weight: bold;
}
footer > p > a {
  color: var(--font-color-primary);
}

```
