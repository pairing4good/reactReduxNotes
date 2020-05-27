# Node Version Manager (nvm)
* https://github.com/nvm-sh/nvm
* `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash`
* `nvm i stable`
* `nvm use stable`

# VS Code
* Download: https://code.visualstudio.com/download
* Cheat Sheet: https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf

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
  },
	"middleware": {
		"prefix": "sna",
		"body": [
			"(store) => (next) => (action) => {$1};",
		],
		"description": "Creates a middleware function"
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
  * `npm i axios` makes api calls https://github.com/axios/axios
  
  # Recipes
  * All `npm i bootstrap lodash @fortawesome/react-fontawesome @fortawesome/fontawesome-svg-core @fortawesome/free-regular-svg-icons @fortawesome/free-solid-svg-icons react-router-dom formik yup @reduxjs/toolkit reselect`
  
  # Debugging
  * redux-devtools https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en
  
  # Redux Notes
  * Three Principles https://redux.js.org/introduction/three-principles
    1. **Single source of truth**: The global state of your application is stored in an object tree within a single store.
    1. **State is read-only**: The only way to change the state is to emit an action, an object describing what happened.
    1. **Changes are made with pure functions**: To specify how the state tree is transformed by actions, you write pure reducers.  Reducers should be pure functions with no side effects.
  * Actions should be serializable.  As with state, serializable actions enable several of Redux's defining features, such as time travel debugging, and recording and replaying actions. Note that it is okay to use Symbols, Promises, or other non-serializable values in an action if the action is intended for use by middleware. Actions only need to be serializable by the time they actually reach the store and are passed to the reducers. https://bit.ly/3c49PGe
