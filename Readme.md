- npm init -y, initialise package.json file
- create src directory where you will put all your source code.
- git init
- Create a .gitignore file, where you will put the things you want not to track by git
- emitting node modules helps in reduing the project size while sharing with others. They can be independently install by individual by looking at package.json
- .DS_Store - is a file hidden in mac os directory
- .cache, dist and .parcel-cache are all files create by parcel-runner

### Install prettier

`npm i -D prettier`

- open workspace setting
- enable format on save
- Set prettier as default formatter
- enable prettier require config
- create an empty .prettierrc file at root of dir

### Install linters###

`npm i -D eslint eslint-config-prettier eslint-plugin-import eslint-plugin-react eslint-plugin-jsx-a11y`

- create .eslintrc.json file, and add the configuration

### Install React and React Dom

`npm i react react-dom`

### Install parcel###

`npm i -D parcel`

- Add a script to your package.json that point your project index file. i.e. index.html

### Babel

- Because we are using parcel, there is not need to configure babel, in case of not using parcel, install babel
  `npm i -D @babel/core @babel/preset-react`
- add .babelrc file at root of the project
