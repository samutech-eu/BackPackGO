## Samuel Daniel Ciocan
## Lenguaje de Marcas
## IES Aguadulce 2023-2024
## Enlace a la web (Ver más abajo):

### Uso de Git mediante la terminal git bash. Las instrucciones y sus resultados deben mostrar como bloques de código markdown:

1. Configuración de usuario

    ```
    Samuel@Samuel MINGW64 /g/Mi unidad/Samuel/1º DAW/Lenguaje de Marcas y Sistemas de Gestión de Información/Sistemas de Gestión de Informacióon/Git/BackPackGO (master)

    $ git config --global user.name "Samuel Ciocan"

    Samuel@Samuel MINGW64 /g/Mi unidad/Samuel/1º DAW/Lenguaje de Marcas y Sistemas de Gestión de Información/Sistemas de Gestión de Informacióon/Git/BackPackGO (master)

    $ git config --global user.email "samuciocan@gmail.com"
    ```

2. Creación del repositorio en nuestro ordenador (init)

    ```
    git init BackPackGO
    cd BackPackGO
    ```

3.  Creación de un commit inicial (add, status, commit, log)
    ```
    touch README.md
    code . &
    git add README.md
    ```

    ```
    $ git status
    On branch master

    No commits yet

    Changes to be committed:
    (use "git rm --cached <file>..." to unstage)
            new file:   README.md
    ```

4.  Creación del repositorio en Github
    ![](/img/imagen1.png)