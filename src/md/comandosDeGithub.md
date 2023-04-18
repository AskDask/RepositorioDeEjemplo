### comandos de github
1. git add .
    >* sirve para guardar lo que hiciste para posteriormente guardarlo en un commit, el punto indica que guarde todo lo nuevo, pero tambien se puede poner el nombre de cualquier archivo para guardar unicamente ese
2. git commit -m "first commit"
    >* sirve para hacer un nuevo commit y el texto entre comillas es para poner el nombre del commit
3. git push -u origin main
    >* sirve para subir el commit a la pagina de github
4. git remote add origin https://github.com/AskDask/RepositorioDeEjemplo.git
    >* sirve para cuando inicias un nuevo repositorio en github lo enlaces con una carpeta de tu pc
5. git init
    >* inicializa el repositorio en la carpeta seleccionada
6. git version
    >* te dice la version de git que utilizas
7. git status
    >* te dice el estado de tu repositorio, por ejemplo si hace falta añadir cambios a un repositorio
8. git log
    >* te da la lista de los commits que has hecho con un codigo para poder regresar a alguno de los commits anteriores
9. git checkout c61d131747469a5360854c1cb92aeaa8aaef2c4c
    >* te devuelve al commit de donde hayas sacado el codigo que va despues de "checkout", este codigo se consigue con el comando anterior (git log)