### TS-Scaffold
An empty TypeScript repository with the basics

#### Installation
```
git clone https://github.com/seikho/ts-scaffold
```

#### Configure
- Update the package.json, change the following properties:
 - "name"
 - "description"
 - "scripts"."test" (optional)
 - "repository"."url" 
 - "keywords" (optional)
 - "author"
 - "bugs"."url"
 - "homepage"
- Update the git remote "origin"
 - `git remote set origin [new location]`
 - E.g.: `git remote set origin git@github.com:my-name/my-repo.git`
 - or `git remote set origin https://github.com/my-name/my-repo.git`
 
#### Building/Compiling
**In VSCode:** (As defined in .settings/tasks.json)  
`Ctrl+Shift+B`


**On the command line:**
`npm run build`