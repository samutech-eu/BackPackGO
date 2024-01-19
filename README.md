## Samuel Daniel Ciocan
## Lenguaje de Marcas y Sistemas de Gestión de Información
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


6. Subir el repositorio a GitHub:

    ```
    Samuel@Samuel MINGW64 /g/Mi unidad/Samuel/1º DAW/Lenguaje de Marcas y Sistemas de Gestión de Información/Sistemas de Gestión de Informacióon/Git/BackPackGO (master)
    $ git push -u origin master
    Enumerating objects: 8, done.
    Counting objects: 100% (8/8), done.
    Delta compression using up to 12 threads
    Compressing objects: 100% (5/5), done.
    Writing objects: 100% (5/5), 65.38 KiB | 16.34 MiB/s, done.
    Total 5 (delta 1), reused 0 (delta 0), pack-reused 0
    remote: Resolving deltas: 100% (1/1), completed with 1 local object.
    To https://github.com/samutech-eu/BackPackGO.git
    3417c6d..ed7d60c  master -> master
    branch 'master' set up to track 'origin/master'.
    ```


7. Comprobar que está subido a GitHub:

    ![](/img/github1.png)


8. Modificar el repositorio para que sea público:

    ![](/img/github2.png)


9. Configurar el repositorio para que publique el directorio raíz en GitHub Pages:

    ![](/img/github3.png)


10. Mostrar los despliegues deployments:

    ![](/img/github4.png)


11. Mostrar la página web:

    ![](/img/github5.png)


12. Creación de otro commit en la interfaz de VSCode:

    ![](/img/vscode1.png)