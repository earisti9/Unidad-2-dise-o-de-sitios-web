# Unidad-2-dise-o-de-sitios-web
Fase de construccion diseño de sitios web Eduar Aristizabal- diana Enriquez

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box; }

.contenedor-primario {
  width: 90%;
  max-width: 1000px;
  margin: auto;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap; }

header {
  background-color: #02BCCD;
  width: 100%;
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-direction: row;
  flex-wrap: wrap; }
  header .titulo {
    font-size: 2em;
    color: #FFFFFF;
    font-family: "Chela One", cursive; }
  header nav {
    width: 50%;
    display: flex;
    flex-wrap: wrap;
    align-items: center; }
    header nav a {
      background-color: #017F8A;
      color: #FFFFFF;
      text-align: center;
      text-decoration: none;
      padding: 10px;
      flex-grow: 1; }

article {
  flex: 1 1 70%;
  padding: 20px; }
  article .article-1 {
    margin-bottom: 20px;
    padding-bottom: 20px;
    border-bottom: 1px solid; }
    article .article-1 h2 {
      font-family: "Kirang Haerang", cursive;
      font-size: 2em; }
    article .article-1 p {
      font-family: "Lato", sans-serif;
      font-size: 1em; }
  article .article-1:nth-last-child(1) {
    margin-bottom: 0;
    padding-bottom: 0;
    border-bottom: none; }

aside {
  background-color: #69DAE4;
  padding: 20px;
  flex: 1 1 30%;
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-start;
  flex-direction: column; }
  aside .widget-1 {
    background-color: #3DCEDC;
    height: 150px;
    margin: 10px; }

footer {
  background-color: #02BCCD;
  width: 100%;
  padding: 20px;
  display: flex;
  flex-wrap: wrap;
  justify-content: center; }
  footer a {
    background-color: #017F8A;
    color: #FFFFFF;
    text-align: center;
    text-decoration: none;
    padding: 20px;
    flex-grow: 1; }

@media screen and (max-width: 800px) {
  .contenedor {
    flex-direction: column; }

  header {
    flex-direction: column;
    padding: o; }
    header .titulo {
      margin: 20px; }
    header nav {
      width: 100%; }

  aside {
    flex-direction: row;
    flex: 0; }
    aside .widget-1 {
      flex-grow: 1; } }



