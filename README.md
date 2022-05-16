# GitFlow-en-Github
GitFlow en Github

## Cambia y crea la rama develop
git checkout -b develop
git checkout develop
git checkout main
## Checkeamos en que rama estamos
git branch

## Subimos a la rama develop
git push -u origin develop
git push -u origin feature/login-con-facebook
git push -u origin feature/exportar-reporte-drive
git push -u origin hotfix/login-linkedin
git push -u origin v1.1.0
git push -u origin release/v1.2.0
git push -u origin v1.2.0
## Baja lo ultimo de la rama develop
git pull origin develop

## Cambia y crea la rama feature/login-con-facebook
git checkout -b feature/login-con-facebook
git checkout -b feature/exportar-reporte-drive
git checkout -b hotfix/login-linkedin
git checkout -b release/v1.2.0
## Crear un archivo
touch login-con-facebook.txt
touch exportar-reporte-drive.txt
touch login-linkedin.txt
touch ajustes-release-v1-2-0.txt
## Agregamos el archivo
git add

##
git commit -m "Se Implemento el inicio Sesion con Facebook"
git commit -m "Soporte para exportar reportes de usuarioos a Google Drive"
git commit -m "Se soluciono el error al iniciar sesion con Linkedin"
git commit -m "Ultimo ajuste"

## Pull Request
Repositorio > Pull Requests > New pull request
base: develop
compare: feature/login-con-facebook

# Etiqueta
git tag -a v1.1.0 -m "version 1.1.0"
git tag -a v1.2.0 -m "version 1.2.0"