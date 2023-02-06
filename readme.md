Beispiele aus https://learn.microsoft.com/de-de/training/modules/github-actions-automate-tasks

neues Repo erstellt: https://github.com/schuerstedt/2-github-actions-automate-development-tasks

und diese readme.md angelegt :)

Beispiel

name: "Hello Actions"
description: "Greet someone"
author: "octocat@github.com"

inputs:
    MY_NAME:
    description: "Who to greet"
    required: true
    default: "World"

runs:
    uses: "docker"
    image: "Dockerfile"

branding:
    icon: "mic"
    color: "purple"
    
als action-a.yml ins Workflow Verzeichnis angelegt. 

