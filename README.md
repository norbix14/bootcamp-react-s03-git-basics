# Ejercicios Git

* git init

* crear repo con su nombre

* agregar el repo a tu local

* crear 2 archivos: README.md, server.js - (PUSH)

* crear 3 carpetas / directorios vacíos. models, controllers, views y enviarlos - (push)

* agregar script en el archivo server.js. server > "echo server with deno.js" y enviar - (PUSH)

* nuevamente en server.js se va a agregar otro texto debajo del otro "echo deno.js is awesome" y enviamos - (PUSH)

* vamos a viajar a snapshot del punto 4 donde server.js estaba vacio - (PUSH)

* creamos a node_modules y lo enviamos - (PUSH)

* agregar .gitignore (ignorar a node_modules) y eliminamos a node_modules del repositorio pero no del local - (PUSH)

* se va a eliminar a README.md del local y del remoto - (PUSH)

## Ayudas

```
git commit -m "message"
git commit --amend -m "message"
git reset --
git reset -- file
git reset HEAD~1
git rm "name"
git rm -r --cached "name"
git push -u origin main
git remote add origin "url"
git log --oneline
```
