# python-virtual-env-notes

## Normal setup

`python3 -m venv rdkit-env`

`source rdkit-env/bin/activate`

`pip install -r requirements.txt`


## Conda
Conda is annoying, it defaults your terminal to being in a virtual environment, here are some commands I found useful

information about the current enviornemnts
`conda info --envs  `

remove one of those environments
`conda env remove -n rdkit-env`

and create the env back
`conda env create -f environment.yml`

or you can add manually
`conda install <package-name>`

and then update the yml file
`conda env export > environment.yml`

this is how you activate an environment
`conda activate rdkit-env`
