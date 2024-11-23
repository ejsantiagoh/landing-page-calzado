# Landing Page para StepAhead

## Integrantes:

### Ada Leal Parra

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
