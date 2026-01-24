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

## Git Add

El git add sirve para seleccionar que cambios son los que vas a mandar en el próximo commit. Para seleccionar todos pones un punto al final:
```
git add .
git status
```
<img width="500" height="110" alt="image" src="https://github.com/user-attachments/assets/26dc661a-07ce-4188-9042-46a2d9688eeb" />

Haciendo el status otra vez observamos que el archive que estaba antes Untracked ahora sí que está preparado para el commit.

## Git Commit

El commando git commit sirve para mandar a tu repositorio local los cambios que estás haciendo en tu área de trabajo. Si no añades la extension -m te saldrá una pestaña en la que añadir un mensaje explicativo de los cambios que estás realizando. Puedes por tanto poner git commit -m “MENSAJE” para ahorrar esa Ventana.
```
git commit -m "cambios pract1"
```
<img width="500" height="80" alt="image" src="https://github.com/user-attachments/assets/34836852-021d-44ad-b255-9986004bcb1b" />

## Git Push

Utilizamos git push para subir tus commits locales al repositorio remoto del GitHub.
```
git push origin main
```
<img width="425" height="101" alt="image" src="https://github.com/user-attachments/assets/5598ee9d-78b2-4604-96c8-67805166824b" />

## Git Checkout

Te permite cambiar entre ramas. Con él puedes moverte a un commit específico o recuperar versions antiguas de archivos. Podrías hacer git checkout nombre_rama o git checkout main.
```
git checkout main
```
<img width="500" height="50" alt="image" src="https://github.com/user-attachments/assets/c9e8abb7-d7ea-4b0b-b320-0738660102eb" />

Como aquí solo teníamos una rama que era la main nos mantiene en ella.










