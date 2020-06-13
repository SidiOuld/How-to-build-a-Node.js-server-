# <p align="center">How-to-build-a-Node.js-server</p>

## Create a Git Repository & Add Dependencies

### Create a directory for your server to live

- `mkdir < server-directory-name >`
- `git init`
- `npx gitignore node` //creates git.ignore for node
- `npm init -y` //creates package.json

### Add your dependencies

- `npm i express helmet cors`
- `npm i nodemon -D`

- Update package.json scripts to include server (and start) script(s):

```
"scripts": {
	"server": "nodemon",  //defaults to index.js
	"start": "node index.js" (for production)
}
```
