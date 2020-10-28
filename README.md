# Almacenvsc001
# Iniciar proyecto Angular
Basado en:
https://angular.io/start

Una vez instalado nodejs y angular global con:

npm install -g @angular/cli

se ejecuta:

ng new <nombre>

en nuestro caso "almacenvsc001"

---

Crear un nuevo componente:
ng generate component <name> [options]

ng generate component top-bar

Borror el contenido original de app.component.html
y pongo el que tenemos ahora.
Lo mismo con el archivo top-bar.component.html
Lo mismo con el archivo styles.css que es el de estilos global

Al archivo Index.html añadir:
  <link
  href="https://fonts.googleapis.com/icon?family=Material+Icons"
  rel="stylesheet"
/>
Para que reconozca el icono del carrito en el archivo top-bar.components.html:

  <a class="button fancy-button"><i 
    class="material-icons">shopping_cart</i>Checkout</a>

Si ahora ejecutamos el servidor:

ng serve 

podemos ver el resultado.
---

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/asalsan790/almacenvsc001.git
git push -u origin main

Estamos estudiando las ramas con:
https://git-scm.com/book/es/v2
https://git-scm.com/book/es/v2/Ramificaciones-en-Git-%C2%BFQu%C3%A9-es-una-rama%3F




---

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
