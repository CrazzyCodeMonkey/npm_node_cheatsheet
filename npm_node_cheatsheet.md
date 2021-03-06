﻿# NPM

| Useful Websites ||
| --- | --- |
| NPM Homepage/Search | https://www.npmjs.com |
| NPM Documentation | https://docs.npmjs.com/ |

| Useful Commands ||
| --- | --- |
| Version | `npm –v` |
| Update npm | `npm i –g npm` |
| Project quick-start | `npm init -y` |
| Docs | `npm -h` |
| Command Docs | `npm {command} -h` |

| Package Management ||
| --- | --- |
| Install Global Package | `npm i –g {package}` |
| List Outdate Globals | `npm outdated -g` |
| Delete Global | `npm un –g {package}` |
| Update Global | `npm up -g` |
| Install Dependency | `npm i {packageNane}` |
| Install Development Dep. | `npm i –D {package}` |
| Install Optional Dep. | `npm i –O {package}` |
| Install package version | `npm i {package}@{version}` |
| Search for a package | `npm s {term}` |

| Project Functions ||
| --- | --- |
| Install Dep and Dev Dep | `npm i` |
| Install only Dep | `npm i --production` |

| Running Package Scripts ||
| --- | --- |
| Run scripts.start | `npm start` |
| Run scripts.test | `npm test` |
| Run scripts.stop | `npm stop` |
| Run scripts.{myScript} | `npm run {myScript}` |

| Useful Packages ||
| --- | --- |
| `nodemon` | Development file watching tool |
| `express.js` | Server routing |
| `pm2` | Process Manager |
| `socket.io` | Socket functionality |
| `gulp` | Task Runner |
| `webpack` | Module Bundler |
| `babel` | ES Transpiler |
| `mocha` | Test Framework |
| `passport` | User Authentication |
| `nodemailer` | Email sending |
| `karma` | Test Runner |
| `eslint` | Code Quality |
| `nsp` | Node Security Platform |
| `nequalize` | SQL DB access |
| `mongoose` | Mongo Access |


# Node.js

| Useful Websites ||
| --- | --- |
| Node.js Homepage/Download | https://nodejs.org/en/ |
| Node.js Documentation | https://nodejs.org/api/ |

| Useful Commands ||
| --- | --- |
| Version | `node -v` |
| Node shell | `node` |
| Run a file | `node {myFile}.js` |

**package.json Example**
```json
{
  “name”:”npm_node_reference_sheet”,
  “version”:”1.0.0”,
  “description”:NPM/Node cheat sheet”,
  “main”:”index.js”,
  “scripts”:{
    “test”:”echo \”Unspecified\” && exit 1”
  },
  “keywords”:[”npm”,”node”,”cheat sheet”],
  “author”:”Trace Sinclair”,
  “license”:”MIT”
}
```

| package.json Attributes ||
| --- | --- |
| `name` | Unique name, no upper case |
| `version` | Semantic Version |
| `description` | Package description |
| `keywords` | Array of terms for search engines |
| `homepage` | The URL to the project homepage |
| `bugs` | The URL to the projects issue tracker |
| `license` | Licensing and restrictions |
| `author` | Name/email/URL of author |
| `contributor` | Array of contributors(Name/email/URL) |
| `files` | Array of file patterns for installing |
| `main` | The main entry point of the package |
| `bin` | Path to executables for PATH inclusion |
| `man` | Single or multiple Man pages |
| `directories` | Indicate the structure of your package |
| `repository` | Specify the place where your code lives |
| `scripts` | Dictionary of defined scripts to run |
| `config` | Set of parameters available in scripts |
| `dependencies` | Packages required for production and development use |
| `devDependencies` | Packages used during development ie: compiling, testing, documentation |
| `peerDependencies` | Compatibility related packages/version, usually used for plugins |
| `optionalDependencies` | Optional dependencies, install will not fail if unable to download, and code should handle the missing package |
| `engines` | Specify the Node version compatibility |
| `os` | Specify OS compatibility |
| `cpu` | Specify CPU architecture compatibility |
| `private` | Flag to indicate if NPM can publish |
| `publishConfig` | Config overrides when publishing |





