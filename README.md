# Práctica 1
### Explicación de comandos de git

Para comenzar la práctica hemos hecho un fork del repositorio p1. Al hacer un fork nos estamos haciendo una copia de un repositorio para trabajar sobre él sin afectar al original. Esta copia estará ubicada en nuestra nube de GitHub.

Para poder probar los diferentes comandos de git nos creamos un Codespace del repositorio. Además, nos creamos un directorio pract1 para trabajar en él.

<img width="500" height="100" alt="image" src="https://github.com/user-attachments/assets/f015dcf2-00e0-4796-acf3-524708aacfa6" />

Aplicamos los siguientes comandos:

## Git Clone

El git clone copia un repositorio remoto al ordenador local. Hacemos clone al fork anterior para traerlo desde la nube GitHub a nuestro Codespace y así poder trabajar con él en tu propio entorno, de manera local.
```
git clone https://github.com/bibidoradom/p1-fork
```
<img width="600" height="100" alt="image" src="https://github.com/user-attachments/assets/e0782110-8b82-47a2-9748-71f3835cd7c5" />

## Git Status

Como su nombre indica, git status nos sirve para ver el estado actual del repositorio. Podemos ver que archivos has cambiado pero todavía no has añadido al commit, los archivos que sí que has añadido, los archivos que existen pero git no sigue todavia (Untracked files) o si todo está limpio y no hay cambios pendientes. En este caso, todavía no hemos cambiado nada por lo que al hacer el git status obtenemos lo siguiente:
```
git status
```
<img width="500" height="90" alt="image" src="https://github.com/user-attachments/assets/e202a460-6680-4267-9fff-b9de77a5bcc6" />

Para probar el status major, creamos un archivo.html en el que escribimos algo. Volvemos a probar el git status:

<img width="500" height="120" alt="image" src="https://github.com/user-attachments/assets/a4e8bf75-f0b4-41a8-99f7-a46c9bc70bf0" />

Vemos como nos dice q no hay nada para hacer commit pero que sí que hay archivos que no están siendo rastreados que podríamos añadir al commit.




