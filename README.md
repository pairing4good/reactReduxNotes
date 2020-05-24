# Node Version Manager (nvm)
* https://github.com/nvm-sh/nvm
* `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash`
* `nvm i stable`
* `nvm use stable`

# VS Code
* https://code.visualstudio.com/download

# Create React App
* `npx create-react-app my-app`
* `cd my-app`
* Install Extensions
  * nucllear.vscode-extension-auto-import
  * esbenp.prettier-vscode
  * burkeholland.simple-react-snippets

# Custom Snippets
* Code > Preferences > User Snippets > javascript.json
```
"test": {
  "prefix": "tst",
  "body": [
    "test('should $1', () => {",
    "	$2"
  "});",
  ],
"description": "Creates new test"
  },
  "rocket": {
  "prefix": "rocket",
  "body": [
    "($1) => {$2}",
    ],
  "description": "Creates a rocket function"
  }
  ```
  
  # Libraries
  * `npm i bootstrap`
  * `npm i lodash`
  * `npm i @fortawesome/fontawesome-svg-core`
  * `npm i @fortawesome/free-regular-svg-icons`
  * `npm i @fortawesome/free-solid-svg-icons`
  * `npm i @fortawesome/react-fontawesome`
  * `npm i react-router-dom`
  * `npm i @reduxjs/toolkit`
  * `npm i reselect`
