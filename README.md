# Landing Page para StepAhead

## Integrantes:

### Ada Leal Parra

Mi compañero creo el repositorio en GitHub, y creo las carpetas correspondientes, luego yo realice la clonacion del repositorio y acepte la invitacion de colaborador 
Primeros comandos ->git touch index.html ->git touch readme.md ->git mkdir estilos ->cd estilos ->git touch styles.css ->cd .. ->git mkdir imagenes
PRIMER COMMIT ->git commit -m "Estructura inicial del proyecto" ->git push origin main 
RAMAS INDIVIDUALES ->git branch Ada ->git checkout Ada  

### Eimer Jesus Santiago Hernandez


#### Se creó inicialmente el repositorio en GitHub
https://github.com/ejsantiagoh/landing-page-calzado.git
git config --global user.name "ejsantiagoh"
git config --global user.email "eimerjesussh@hotmail.com"

#### Se enlaza de manera local
echo "# landing-page-calzado" >> README.md
mkdir StepAhead
cd StepAhead/
git init
git branch -m main
echo "# landing-page-calzado" >> README.md
git add README.md
git status
git commit -m "creación del readme"
git branch -M main
git remote add origin https://github.com/ejsantiagoh/landing-page-calzado.git
git push -u origin main
git pull
git branch eimer
git checkout eimer
vim readme.md
touch index.html
mkdir estilos
cd estilos
touch styles.css
touch imagenes
git add .
git status
git commit -m "Se crea la estructura"
