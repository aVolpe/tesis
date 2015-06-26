# Juegos serios como apoyo a la formación de profesionales: Una aplicación al área de  enfermería

## Autores

* Mirta Gonzalez
* Arturo Volpe


## Compilación

Se utiliza `latexmk` para la compilación

* Libro:
    
    latexmk main

* Resumen

    cd resumen && latexmk main

* Poster

    cd poster && latexmk poster_portrait.tex

* Presentación

    cd presentacion && latexmk main_linux.tex

## Utilización

La presentación se puede visualizar con [Okular](https://okular.kde.org/), si se
desea utilizar otro visualizador (como Acrobat Reader), se debe compilar
`main_windows`.
