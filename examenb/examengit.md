# GITHUB

#### 1.  Crea una carpeta que será la carpeta de trabajo del examen. Llámala examen-b.

#### 2. Inicializa el repositorio.
Vamos a nuesto git y le damos a crear repositorio nuevo, le damos un nombre y si queremos una descripción, nos aseguramos de que este en público y lo creamos.

Una vez hecho esto vamos a la consola y ahí hasta el directorio donde queremos inicializar nuestro repositorio e inicializamos con el comando git init.

        git init

#### 3. Crea un archivo llamado examenb.html con el contenido.

#### 4. Crea una carpeta llamada contenidos y dentro de esta carpeta dos ficheros llamados html.txt y css.txt.

#### 5. Pasa los ficheros y directorios a preparado.

Esto lo realizamos con el comando de git add de la siguiente forma.

        git add --all

#### 6. Confirma los ficheros con un commit “Inicial commit”.

Realizamos el commit con el siguiente código.

        git commit -m "Inicial commit"

#### 7. Mira el estado del proyecto.

Podemos ver el estado del proyecto con el código:

        git status

El cual en este momento nos manda el siguiente mensaje:

        On branch master
        nothing to commit, working tree clean

#### 8. Modifica el texto del ultimo commit poniendo “Contenidos 1,2 e índice“.

Esto lo realizamos con el comando amend y el tiene que ser previo al push, si ya hemos realizado el push no podremos cambiar el nombre del commit.

        git commit --amend -m "Contenidos 1,2 e índice"

#### 9. Modifica el fichero html.txt eliminando todo su contenido.

#### 10. Pasa a preparado de nuevo el fichero html.txt.

Lo realizamos con add

        git add --all

#### 11. Realiza otra confirmación con comentario “Eliminado texto de contenido html”.

        git commit -m "Eliminando texto de contenido html"

#### 12. Visualiza el log de todo el proyecto.

        git log

#### 13. Vuelve atrás al commit inicial de “Contenidos 1,2 e índice”.

        gig log --oneline
        git checkout 1918fd7

#### 14. Vuelve al estado final del proyecto (antes de la vuelta atrás).

#### 15. Crea un repositorio público en tu GITHUB y haz un push de todo el proyecto.

    git push
    git branch -M main
    git remote add origin https://github.com/AzothShadow/examen-b.git
    git push -u origin main
    