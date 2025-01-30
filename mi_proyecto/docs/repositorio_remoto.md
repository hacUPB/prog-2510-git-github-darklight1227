#### Repositorio Remoto
Los repositorios remotos, son bastante parecidos a los locales, de hecho usaremos varios de los comandos que usamos en los locales
con la diferencia de que debemos tener una cuenta de github enlazada con gitbash para poder subir los archivos a la nube.

Si contamos con la aplicación ***github cli*** podemos usar el comando
```
gh auth login
```
Luego de que tenemos enlazada la cuenta debemos tener en cuenta que ahora tenemos un nuevo comando 
```
git push origin main
```
con el cual realizaremos el envio de los archivos a la nube.

Recordando un poco de la ruta para subir los archivos a la nube tenemos los siguientes comandos:

```
git status
```
```
git commit -m
```
```
git rm --cached
```

Por ultimo la ruta a seguir para subir los archivos a la nube será primero usar el comando
```
git add ( archivo )
```
De esta forma añadiremos el archivo, luego debemos realizar un commit con el siguiente comando:
```
git commit -m "Descripcion"
```
Ya teniendo el commit hecho solo queda subir el archivo con el comando

```
git push origin main
```
Y de esta forma tendremos los archivos en la nube.



