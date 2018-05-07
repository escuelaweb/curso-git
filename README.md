# curso-git
## Repositorio para el curso de Git
## Recordar siempre al crear un proyecto en Git


# Command line instructions


### Git global setup


### git config --global user.name "Mi Usuario"


### git config --global user.email "miemail@email.com"


### Create a new repository


### git clone git@gitlab.com:curso-git/nuestro-proyecto.git


### cd nuestro-proyecto


### touch README.md


### git add README.md


### git commit -m "add README"


### git push -u origin master


## Existing folder


### cd existing_folder


### git init


### git remote add origin git@gitlab.com:curso-git/nuestro-proyecto.git


### git add .


### git commit -m "Initial commit"


### git push -u origin master


## Existing Git repository


### cd existing_repo


### git remote rename origin old-origin


### git remote add origin git@gitlab.com:curso-git/nuestro-proyecto.git


### git push -u origin --all


### git push -u origin --tags
