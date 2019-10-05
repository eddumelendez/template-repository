# Guía para contribuir

Existen varias formas de contribuir a este proyecto. Puede ser mediante `issues` o `pull requests`.

## Fork del proyecto

1. Hacer un `fork` del proyecto
2. Clonar el repositorio `tu_usuario/template-repository`

```
git clone 
```

3. Acceder al proyecto clonado

```
cd template_repository
```

4. Agregar el repositorio remoto original

```
git remote add upstream <url del proyecto>
```

5. Validar que existan los repositorios remotos `origin` y `upstream`

```
git remote -v
```

## Pull Request

Si quieres contribuir con un Pull Request a este proyecto, sigue los siguientes pasos:

1. Crea un branch desde `master`

```
git branch master new_branch
git checkout new_branch
````

También puedes ejecutar:

```
git checkout -b new_branch
```

2. Realiza los cambios

3. Realiza el commit

```
git commit -m "Título del commit"
```

4. Envia tus cambios a tu repositorio remoto

```
git push origin new branch
```

5. La consola mostrará un mensaje similar a

```
Total 0 (delta 0), reused 0 (delta 0)
remote:
remote: Create a pull request for 'new_branch' on GitHub by visiting:
remote:      https://github.com/eddumelendez/spring-boot/pull/new/new_branch
remote:
To github.com:eddumelendez/spring-boot.git
 * [new branch]            new_branch -> new_branch
```

6. Abrir el enlace que se me muestra en el mensaje anterior y dar clic en `Create Pull Request`

NOTE: Para mayor información revisar el siguiente [enlace](https://help.github.com/en/articles/creating-a-pull-request)