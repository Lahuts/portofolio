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
      <h1>Développeur</h1>
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
        <ol>
          <li>Html</li>
          <li>Css</li>
          <li>Java</li>
          <li>C#</li>
        </ol>
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
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Deserunt iure
          laudantium, quod iusto quis amet. Aperiam aut dicta, nemo provident
          ipsam velit cum tempore explicabo.
        </p>
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
        &copy; -<a href="mailto:alexis.huet.m@gmail.com">Alexis Huet</a> - 2021
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

header {
  padding: 1em;
  background-color: rgb(137, 35, 233);
  color: #fff;
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
  background-color: rgb(59, 106, 235);
}
nav > ol {
  padding: 1.5rem;
}

nav > ol > li {
  display: inline-block;
  padding-left: 4rem;
}
li > a {
  color: #fff;
}
section > h2 {
  margin-top: 2rem;
  padding-left: 2rem;
  background-color: rgb(103, 51, 155);
  color: #fff;
  padding: 0.7rem;
}
section > ol {
  margin-top: 0.5em;
}
section > p {
  border: black solid 3px;
  margin-top: 1em;
  padding: 2em;
}

footer {
  margin-top: 4rem;
  text-align: center;
  margin-bottom: 4rem;
}
footer {
  color: black;
  font-weight: bold;
}
footer > p > a {
  color: black;
}

```
