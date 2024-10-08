# Git Ramas (branches)
## git alias
```sh
 git config --global alias.st "status --short" (version corta de status)
 ```
## ver el contenido de cada commit
 ```sh
 git show <numero de hash (4 digitos)>

 (extencion para ver videos mas rapidos videospeed controler)
 ```
 ## ramas crea una rama
 ```sh
 git branch <nombre rama>
```

 ### crea una rama y me mueve a esa
```sh
 git switch -c <nombre de la rama>
```

 ### moverse entre ramas 
```sh
 git switch <nombre de la rama>
 git switch - (te moves a la rama anterior que estabas)
 ```
## ver ramas que estan locales remotas
```sh
git branch -a
```