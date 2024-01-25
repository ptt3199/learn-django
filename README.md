### Create a readme file 
`touch README.md`
### Set python version
- `pyenv versions` to get python versions installed.

- `pyenv local 3.11.7` set python for project to version 3.11.7.

### Setup Poetry
- Create a poetry config file `poetry.toml` -> Keep .venv in project folder.

``````
[virtualenvs]
in-project = true
path = ".venv"
``````
- `poetry init`

### Setup git
* `git init` 
* Create repo
`gh repo create my-new-repo -y`.

```
git remote add origin https://github.com/username/my-new-repo.git
git branch -M main
git push -u origin main
``````

`git pull origin main`

Commit changes

``````
git add .
git commit -m "Merged .gitignore and added project files"
git push origin main
``````
