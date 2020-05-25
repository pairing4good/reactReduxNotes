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
  * `npm i bootstrap` to use Bootstrap https://getbootstrap.com
  * `npm i lodash` helper functions https://lodash.com/
  * `npm i @fortawesome/react-fontawesome` to use Font Awesome https://fontawesome.com/
  * `npm i @fortawesome/fontawesome-svg-core`to use Font Awesome icons https://fontawesome.com/
  * `npm i @fortawesome/free-regular-svg-icons`to use Font Awesome icons https://fontawesome.com/
  * `npm i @fortawesome/free-solid-svg-icons`to use Font Awesome icons https://fontawesome.com/
  * `npm i react-router-dom` routing https://reacttraining.com/react-router/
  * `npm i formik` simplified forms https://jaredpalmer.com/formik/
  * `npm i yup` simplified validation https://github.com/jquense/yup
  * `npm i @reduxjs/toolkit` simplify redux code https://redux-toolkit.js.org/
  * `npm i reselect` caches selectors https://github.com/reduxjs/reselect
  
  # Recepie
  * All `npm i bootstrap lodash @fortawesome/react-fontawesome @fortawesome/fontawesome-svg-core @fortawesome/free-regular-svg-icons @fortawesome/free-solid-svg-icons react-router-dom formik yup @reduxjs/toolkit reselect`
