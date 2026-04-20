ecommerce-api-git
comandos git
crear rama
````
git checkout -b JIRA-003
````
visualizar status de cambios
````
git status
git status -s

````
incluir al stage
````
git add .
git add archivo_especifico.py
````
comprometer o seleccionar cambios para subir al repositorio remoto
````
git commit -m "feat: new function calcular resta"


configuraciones basicas
````
git config --global user.name "Diego Calderon"
git config --global user.email "dmcalderonc97@gmail.com"
git config --global core.editor "code --wait"
git config --global color.ui auto
git config --global init.defaultBranch main
````
consultar configuraciones
````
git config --list
git config user.name
````