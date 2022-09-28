# template-python-docker
A template repository for getting a project up and running with docker and python

## Usage:

1. Create a new repository using this as the template
2. Clone your new repository

`Dockerfile`: Contains build instructions... this is where you put pip packages you want installed
`Dockerfile.build`: a script for building and tagging the image
`Dockerfile.run`: an easy way to run 

Run `./Dockerfile.build` followed by `./Dockerfile.run`

The code is held in `main.py` though this can be adjusted in `Dockerfile`


