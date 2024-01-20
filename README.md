## Samuel Daniel Ciocan
## Lenguaje de Marcas y Sistemas de Gestión de Información
## IES Aguadulce 2023-2024
## Enlace a la web: [https://samutech-eu.github.io/BackPackGO/](https://samutech-eu.github.io/BackPackGO/)

1. Configuración de usuario:

    Configuro el nombre de usuario y el email.

    ```
    Samuel@Samuel MINGW64 /g/Mi unidad/Samuel/1º DAW/Lenguaje de Marcas y Sistemas de Gestión de Información/Sistemas de Gestión de Información/Git/BackPackGO (master)

    $ git config --global user.name "Samuel"

    Samuel@Samuel MINGW64 /g/Mi unidad/Samuel/1º DAW/Lenguaje de Marcas y Sistemas de Gestión de Información/Sistemas de Gestión de Información/Git/BackPackGO (master)

    $ git config --global user.email "business@samutech.eu"
    ```

2. Creación del repositorio en nuestro ordenador:

    Inicializo el repositorio y también lo creo al escribir el nombre del repositorio después del `git init`.

    ```
    git init BackPackGO
    cd BackPackGO
    ```

3. Creación de un commit inicial:

    Creo el archivo README.md, lo abro para editar y luego lo añado; a continuación, compruebo el estado del repositorio.

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

4. Creación del repositorio en GitHub:

    En GitHub, creo el repositorio como público.

    ![Repositorio en GitHub](/img/repositorio1.png)

5. Añadir el remoto al repositorio local:

    Añado el remoto con el siguiente comando para que el repositorio local esté conectado con el de GitHub.

    ```
    git remote add origin https://github.com/samutech-eu/BackPackGO.git
    ```

6. Subir el repositorio a GitHub:

    Subo el repositorio a GitHub con el comando `git push`.

    ```
    Samuel@Samuel MINGW64 /g/Mi unidad/Samuel/1º DAW/Lenguaje de Marcas y Sistemas de Gestión de Información/Sistemas de Gestión de Información/Git/BackPackGO (master)
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

    En esta captura, compruebo que se ha conectado correctamente el repositorio a GitHub.

    ![Repositorio en GitHub](/img/github1.png)

8. Modificar el repositorio para que sea público:

    Como al crear el repositorio directamente en público ya no tengo que modificarlo.

    ![Repositorio en GitHub](/img/github2.png)

9. Configurar el repositorio para que publique el directorio raíz en GitHub Pages:

    Muestro la configuración del repositorio para poder subir la web a GitHub Pages.

    ![Configuración en GitHub](/img/github3.png)

10. Mostrar los despliegues deployments:

    En esta captura, se muestra los despliegues más recientes.

    ![Despliegues en GitHub](/img/github4.png)

11. Mostrar la página web:

    Muestro la página web que está subida a GitHub Pages.

    ![Página web en GitHub Pages](/img/github5.png)

12. Creación de otro commit desde la interfaz de VSCode:

    Creo un commit desde la interfaz de VSCode.

    ![Commit en VSCode](/img/vscode1.png)

13. Subir el repositorio a GitHub desde la interfaz de VSCode:

    Aquí muestro cómo se hace el push desde la interfaz de VSCode.

    ![Push en VSCode](/img/vscode2.png)

14. Comprobar que está subido a GitHub:

    En esta captura, se comprueba que todo se ha subido correctamente a GitHub.

    ![Repositorio en GitHub](/img/github6.png)

15. Ver el listado de commit desde GitHub:

    Se muestra el listado de los últimos commit hechos.

    ![Commits en GitHub](/img/github7.png)