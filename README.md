IMPORTANTE: El repositorio debe contener un archivo README.md con la descripción de lo qué se ha realizado en el laboratorio, si quieres puedes añadir capturas de pantalla para explicar cómo has realizado el laboratorio.

Requisitos
Tener instalado Git en tu computadora.
Tener una cuenta en GitHub.
Objetivos

1. Crear un repositorio en local

1.- Abro Gitbash
2.- Creo nuevo directorio para el repositorio: mkdir prueba
3.- cd prueba
4.- git init

2. Crea un nuevo repositorio en GitHub.

1.- Creo repositorio publico nombre prueba, el resto por defecto. copio URL. https://github.com/skcna2/prueba.git
2.- git remote add origin https://github.com/skcna2/prueba.git // Enlazo local con repositorio remoto
git remote -v // compruebo que se agrego
3.- touch README.md // creo le fichero en la carpeta repo local
git add README.md
git commit -m "primer commit"
git branch -M main
git push -u origin main
4.-Pruebas Stagging
touch stagging.html
git add stagging.html
git status // Compruebo que el fichero está en staging
git commit -m "subida hmtl"
git push

Añade el archivo al staging.
Crea un commit con un mensaje descriptivo.
Sube los cambios al repositorio en GitHub.

4. Crear una rama

Crea una rama nueva llamada "development".
Cambia a la nueva rama.
Realiza algunos cambios en el archivo que creaste.
Añade y haz un commit con los cambios en la rama "development".
Sube los cambios a Github. 5. Hacer un merge

Vuelve a la rama "main".
Haz un merge de la rama "development" a la rama "main".
Si no hay conflictos, los cambios realizados en la rama "development" se incorporarán a la rama "main".
Hax un push de los cambios al repositorio en GitHub.
La rama principal de nuestro repositorio puede ser "main" o "master" según la hayamos nombrado.
