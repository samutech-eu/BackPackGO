## Samuel Daniel Ciocan
## Lenguaje de Marcas
## IES Aguadulce 2023-2024
## Enlace a la web: (poner aquí)

1. Configuración de usuario

    ```
    Samuel@Samuel MINGW64 /g/Mi unidad/Samuel/1º DAW/Lenguaje de Marcas y Sistemas de Gestión de Información/Sistemas de Gestión de Informacióon/Git/BackPackGO (master)

    $ git config --global user.name "Samuel Ciocan"

    Samuel@Samuel MINGW64 /g/Mi unidad/Samuel/1º DAW/Lenguaje de Marcas y Sistemas de Gestión de Información/Sistemas de Gestión de Informacióon/Git/BackPackGO (master)

    $ git config --global user.email "samuciocan@gmail.com"
    ```

2. Creación del repositorio en nuestro ordenador:

    ```
    git init BackPackGO
    cd BackPackGO
    ```


3.  Creación de un commit inicial:

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


4.  Creación del repositorio en GitHub:

    ![](/img/repositorio1.png)


5. Añadir el remoto al repositorio local:

    ```
    git remote add origin https://github.com/samutech-eu/BackPackGO.git
    ```

    