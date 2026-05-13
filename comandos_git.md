--verificar version de git--
git --version

--configuracion base--
git config --global user.name "Valentins Salina"
git config --global user.email "salinavalentina31@gmail.com"
--verificar configuracion--
git config --list

--inicializar repositorio local--
git init

--verificar estado del repo--
git status 

--agregar un archivo--
git add nombre_del_archivo
--agregar todos los archivos--
git add .
--realizar el comit--
git commit -m "Mi primer commit"

--ver los comit realizados--
git log
--para salir letra q--

--limpiar consola--
clear

--crear rama principal main
git branch -M main

--
git remote  add origin URL

echo "# laboratorio-2026" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/salinavalentina31-ship-it/laboratorio-2026.git
git push -u origin main
