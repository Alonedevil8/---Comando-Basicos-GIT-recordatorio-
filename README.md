%---------------------------Comando basicos de git

git init: Se utiliza para inicializar un nuevo repositorio de Git en el directorio actual.

git clone: Se utiliza para clonar un repositorio existente. Simplemente especifica la URL del repositorio que deseas clonar.

git add: Este comando se utiliza para agregar cambios al área de preparación (staging area). Es decir, para preparar los cambios para ser confirmados.

git commit: Se utiliza para confirmar los cambios que se han agregado al área de preparación. También puedes agregar un mensaje para describir los cambios que has realizado.

git push: Se utiliza para enviar los cambios confirmados a un repositorio remoto.

git pull: Este comando se utiliza para descargar los cambios de un repositorio remoto y fusionarlos con tu rama local.

git branch: Se utiliza para listar, crear o eliminar ramas.

git merge: Se utiliza para fusionar cambios entre diferentes ramas.

git status: Este comando se utiliza para obtener información sobre el estado actual del repositorio, como los archivos que han sido modificados, eliminados o agregados.

git log: Se utiliza para ver la historia de confirmaciones en el repositorio.

%----------------------------------------------------------------------------------------------

git clone: se utiliza para clonar un repositorio remoto en el repositorio local. Ejemplo: git clone https://github.com/usuario/repo.git

git add: se utiliza para agregar cambios a la zona de preparación (staging area) antes de hacer una confirmación (commit). Ejemplo: git add archivo.txt

git commit: se utiliza para confirmar los cambios en el repositorio local con un mensaje descriptivo. Ejemplo: git commit -m "Mensaje de confirmación"

git push: se utiliza para enviar los cambios confirmados al repositorio remoto. Ejemplo: git push origin master

git pull: se utiliza para actualizar el repositorio local con los cambios realizados en el repositorio remoto. Ejemplo: git pull origin master

git branch: se utiliza para crear una nueva rama o listar las ramas existentes. Ejemplo: git branch nueva_rama

git checkout: se utiliza para cambiar entre ramas o versiones anteriores del repositorio. Ejemplo: git checkout nueva_rama

git merge: se utiliza para combinar cambios de diferentes ramas en una sola rama. Ejemplo: git merge nueva_rama

git status: se utiliza para mostrar el estado actual del repositorio local y los cambios realizados. Ejemplo: git status

git log: se utiliza para ver el historial de confirmaciones realizadas en el repositorio. Ejemplo: git log

%----------------------------------------------------------------------------------------------

Configura tu nombre de usuario y correo electrónico con los siguientes comandos:

git config --global user.name "Tu nombre de usuario"
git config --global user.email "tu-correo-electronico@example.com"

Genera una clave SSH con el siguiente comando:
ssh-keygen -t rsa -b 4096 -C "tu-correo-electronico@example.com"






