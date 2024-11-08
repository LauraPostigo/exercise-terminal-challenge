# Terminal Challenge - README

Este es un conjunto de instrucciones para interactuar con la línea de comandos y realizar varias tareas dentro de la carpeta `thecmdchallenge/`.

## Pasos:

1. **Accede al directorio `thecmdchallenge/` y lista los archivos**
    ```bash
    cd thecmdchallenge/
    ```

2. **Imprime la ruta del directorio actual**
    ```bash
    pwd
    ```

3. **Lista todos los archivos del directorio actual, incluyendo los ocultos**
    ```bash
    ls -lals
    ```

4. **Lista todos los archivos dentro del proyecto de manera recursiva**
    ```bash
    ls -laR
    ```

5. **Limpia todo el desorden de la línea de comandos**
    ```bash
    clear
    ```

6. **Ve al último nivel dentro de la carpeta `small-name` y muestra en la consola el contenido de `trophy.txt`**
    ```bash
    cd small-name
    ls
    cd bigger-name-than-before/
    ls
    cd omg-this-folder-has-a-huuuuuuge-name-and-i-tired-to-type/
    ls
    cd this-is-probably-the-longest-folder-name-you-have-ever-seen-but-believe--im-sure-there-are-other-folder-bigger-than-this-one-because-people-sometimes-like-to-assign-huge-names-to-their-personal-stuff-supercalifragilisticexpialidocious/
    ls
    cat trophy.txt
    ```

7. **Sube un nivel y ve al directorio `funcode` para listar todos los archivos con la extensión típica de JavaScript**
    ```bash
    cd ../..
    cd funcode
    ls *.js
    ```

8. **Crea una copia de `the-mostboring-text.txt` y renómbrala como `lol.txt`**
    ```bash
    cp boringfolder/the-mostboring-text.txt boringfolder/lol.txt
    ```

9. **Mueve el archivo `kids.jpg` a `images/hello/` dentro de `funcode`**
    ```bash
    mv kids.jpg funcode/images/hello/
    ```

10. **Elimina el directorio `small-name`**
    ```bash
    rm -r small-name
    ```

11. **Imprime el contenido del archivo `the-ultimate-joke.txt`**
    ```bash
    cat $(find . -name the-ultimate-joke.txt)
    ```

12. **Elimina todo el contenido de la carpeta `boringfolder`**
    ```bash
    rm -rf boringfolder
    ```

13. **Abre el archivo `dragon-ball-jokes.md` usando el editor de texto `vi`**
    ```bash
    vi kamehameha/dragon-ball-jokes.md
    ```

14. **Actualiza el archivo `dragon-ball-jokes.md` eliminando la primera broma y guarda los cambios**
    - Para borrar la línea:
    ```bash
    d
    ```
    - Para salir y guardar los cambios:
    ```bash
    :wq
    ```

