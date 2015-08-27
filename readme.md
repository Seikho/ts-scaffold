### TS-Scaffold
An empty TypeScript repository with the basics

#### Installation
```
git clone https://github.com/seikho/ts-scaffold my-project
cd my-project
npm install
```

#### Configure
- Update the package.json, change the following properties:
 - `name`
 - `description`
 - `scripts.test` (optional)
 - `repository.url` 
 - `keywords` (optional)
 - `author`
 - `bugs.url`
 - "homepage`
- Update the git remote "origin"
 - `git remote set origin [new location]`
 - E.g.: `git remote set origin git@github.com:my-name/my-repo.git`
 - or `git remote set origin https://github.com/my-name/my-repo.git`
 
#### Building/Compiling
**In VSCode:** (As defined in .settings/tasks.json)  
`Ctrl+Shift+B`


**On the command line:**  
`npm run build`

#### Removing the commit history
The simplest way is to delete the `.git/` folder and re-initialise the repository:
```
rm -rf .git/
git init
git add --all
git commit -m "Initial commit"
git remote add origin https://github.com/my-username/my-repo.git
git push origin master
```


##### Note well:
This project uses a module called `ts-globber` to populate tsconfig.json prior to compiling.  
This will probably be made redundant in a future TypeScript version.