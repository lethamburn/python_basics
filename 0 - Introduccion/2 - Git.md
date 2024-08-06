<div style="text-align: center; width: 200px;" >
  <img src="https://github.com/Hack-io-Data/Imagenes/blob/main/01-LogosHackio/logo_celeste@4x.png?raw=true" alt="logo hack(io)" />
</div>

---

# Git

### Crea una nueva carpeta llamada *ejercicios_git* y completa los siguientes ejercicios dentro de ella para organizar los ficheros correctamente.

### Para estos ejercicios puedes utilizar Visual Studio Code y la terminal integrada o externa a tu elección.

---

#### Git básico

- **1. En la carpeta *ejercicios_git* ejecuta el comando git correspondiente para crear un nuevo repositorio local en ella, no hace falta que crees una subcarpeta.**
- **2. A continuación, desde GitHub, crea un nuevo repositorio llamado *ejercicios_git* con visibilidad pública, sin ningún archivo adicional (.gitignore, README, etc...).**
- **3. Enlaza la carpeta *ejercicios_git* local a este nuevo repositorio mediante el comando git correspondiente.**
- **4. Crea un nuevo fichero en la carpeta local llamado *hola.txt* con el contenido en texto llamado "Hola".**
- **5. Añade al staging solamente este fichero hola.txt mediante el comando git correspondiente y sube los cambios mediante un commit llamado *"feat hola.txt"* a la rama main.**
- **6. A continuación, modifica el archivo *hola.txt* y sustituye su contenido por *"Esta es una modificación"*. Vuelve a subir estos cambios señalando solamente el archivo *hola.txt* con un commit llamado *"refactor hola.txt"*.**
- **7. Vuelve a modificar el archivo *hola.txt* y vuelve a sustituir su contenido por *"Hola"*. De momento no hagas ningún movimiento más.**
- **8. Y ahora crea un nuevo fichero llamado *adios.txt* con un el contenido *"Adios"*. Añade mediante el comando correspondiente de git *todos* los archivos modificados de una sola vez y haz un commit llamado *"feat adios.txt & refactor hola.txt"*.**

#### Git con ramas

- **9. En este punto del repositorio, crea una nueva rama llamada *develop* con una copia de la rama main en este momento. Es decir, esta rama deberá tener los mismos archivos *hola.txt* y *adios.txt*.**
- **10. Con el comando correspondiente, viaja hasta esta rama *develop*.**
- **11. En esta nueva rama, crea un nuevo archivo llamado *main.txt* con el contenido *"Este es el fichero main"* y sube los cambios a la rama develop mediante un commit llamado *"feat main.txt"*.**
- **12. Una vez subidos los cambios a nuestra rama *develop*, mergea esta rama con la rama *main* mediante los comandos de git correspondientes.**
- **13. Comprueba en GitHub que la rama *main* es exactamente igual que la rama *develop* para tener los cambios al día.**
 
#### Pull requests
- **14. Viaja de nuevo a la rama *main* y trae los cambios con el comando git correspondiente para actualizar localmente esta rama.**
- **15. Una vez en la rama *main* actualizada, crea una nueva rama llamada *test*, viaja a ella y crea un nuevo fichero llamado test.txt sin contenido.**
- **16. Sube los cambios a la rama *test* y vuelve a *GitHub* para crear una nueva *Pull Request*.**
- **17. Asegurate que la Pull Request va a mergear la rama *test* en la rama *main*, creala, comprueba la solicitud y acepta los cambios revisando que todos los ficheros estan correctos.**
- **18. Una vez aprobada la *Pull Request*, vuelve a la rama *main* mediante git, trae los cambios y comprueba que tienes todos los ficheros de este flujo actualizados, incluyendo el nuevo fichero *test.txt*.**