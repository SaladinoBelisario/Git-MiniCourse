# **Welcome to the Git MiniCourse Notes**
## General Index
- Getting Started
    * Installing git

    Instalacion para macOs
    brew install git

    * What it's git?
    * Why git?
    * How it works? (A first approach)
    * Your first setup
- Git Basics
    * Getting a Git Repository
    git init
    * Recording Changes to the Repository
    git add nombrearchivo
    git commit -m "nombremensaje"
    git push
    git origin

    * Viewing the Commit History
    * Viewing the Commit History

    git status
    Información sobre mi repositorio

    Historial
    git log -3
    git log -grep "nombremensaje"
    git log --author "Quecky"

    * Undoing Things
    git --amend
    * Working with Remotes
    * Tagging
    nivel de parche (ultimo numero no affecta funcionalidad )
    Etiqueta es un apuntador con informacion

    git show todo lo que he hecho junto con basura

    git tag para ver etiquetas
    etiqueta apuntador a commit
    git push origin --tags para enviar todas las etiquetas

    etiquetas sirven para guiarte

    git checkout o git switch
     cambiamos de rama a etiqueta, brinca el apuntador

    git switch -c //creamos y cambiamos a una rama el HEAD
- Git workflows
    * Why workflows matters

    git trabaja como una serie de instantaneas




- Git Branching
    * Branching and Merging
    * Branch Management
    * Remote Branches

    una rama es el historial de un commit

    el apuntador mas importante es HEAD por que me dice donde esta trabajando

    para saber donde esta la cabeza
    git log --oneline --decorate

    por default HEAD esta en master


- Git on the Server
    * Protocols
    *
    *
    *
- Git Tools
    *
- Git Internals
    *
    *
- Git and Other Systems
- The Git LFS (Large File System)
