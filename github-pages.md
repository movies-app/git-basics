# GitHub Pages 

1. Hacer un `fork` del repositorio:  
`https://github.com/sindresorhus/hi`

2. En el repositorio recientement creado (via fork), ir a la opción de Configuración -> "Settings"

3. Renombrar el repositorio a:  
`{username - organization}.github.io`

4. En la terminal realizar lo siguiente:
```
git checkout -b master
git update-ref HEAD master
git push --set-upstream origin master
```
Esto se hace porque en el repositorio `hi` el branch `master` es en realidad `gh-pages`. Vamos a crear un branch `master` porque GitHub sólo publica páginas que estan bajo `master`.


5. Modificar archivo `index.html`

6. Commit -> Push -> Revisar