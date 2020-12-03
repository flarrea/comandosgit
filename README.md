# comandosgit
Comandos básicos para trabajar con Git, Github y Ionic.

___________________________________________________________________________________________________
COMANDOS BÁSICOS PARA GIT Y GITHUB CON IONIC

Primero, debes instalar Git, luego crear tu cuenta en Github.

Ingresas a Github y creas un repositorio.

Luego, recuerda que estos comandos se utilizan desde dentro del directorio de la APP.

C:\ionicApps\cursoIonicApps\midemoapp


1. Publicar

git init
git add .
git commit -m "#01 NombreApp Texto descriptivo de lo que hiciste y subirás"
git remote add origin git@github.com:usuario/nombrerepositorio.git
git push -u origin master

2. para actualizar

git add .
git commit -m "#01 NombreApp Texto descriptivo de lo que hiciste y subirás"
git pull
git push -u origin master

3. Revisar

git status

git diff

4. Si te pide logearte.

4.1. Configurar Git

git config --global user.name "name"
git config --global user.email name@dominio.com

Si en un proyecto concreto queremos utilizar otro usuario o email, lo que debemos hacer es no añadir la opción --global

Estos dos parámetros son importantes porque las confirmaciones de cambios utilizan esta información.

4.2. Ver configuración

git config --list


5. Clonar repositorio que quieras usar en tu equipo

git clone https://github.com/usuario/ejemplo01.git

Esto creará un directorio ejemplo01 donde hayas ejecutado la orden anterior. Dentro de ese directorio encontrarás además del directorio .git comentado en el apartado anterior (con toda la información del repositorio), una copia de trabajo de la última versión.

6. Instalar App.

Desde el directorio donde clonaste: npm install


