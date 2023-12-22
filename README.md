# Todos los repositorios de *Sistemas y Tecnologías Web: Cliente*

alu0101056944, Marcos Barrios Lorenzo

## Setup

Este repositorio utiliza submodulos git, por lo que es necesario ejecutar el siguiente comando para obtener el contenido de los submodulos:

```bash
git submodule update --init --recursive
```

El comando ejecuta un `git clone` para cada submodulo.

## Estructura del repositorio

```bash
├───sytwc-gatsby # Práctica 3 de introducción a Gatsby y Práctica 4: Gatsby
│   ├───docs
│   └───gatsby_page
│       ├───content
│       ├───src
│       │   ├───images
│       │   │   └───bienes
│       │   ├───pages
│       │   ├───styles
│       │   │   └───building
│       │   └───templates
│       │       └───building
|       ├───test
|       └───test-examples
├───sytwc-sass # práctica 1 de webcomponentes
│   ├───docs
│   └───public
│       ├───assets
│       ├───src
│       │   ├───controller
│       │   ├───model
│       │   └───view
│       └───styles
│           ├───components
│           └───exercises
│               └───modules
└───sytwc-tools # práctica 2 de gulp, parcel
    ├───gulp
    │   ├───app
    │   │   ├───images
    │   │   ├───scripts
    │   │   │   └───minified
    │   │   └───styles
    │   ├───docs
    │   └───test
    │       └───spec
    └───parcel
        ├───app
        │   ├───images
        │   ├───scripts
        │   │   └───minified
        │   └───styles
        ├───build
        └───test
            └───spec
```
