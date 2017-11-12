# React Redux Boilerplate
Simple ReactJS Boilerplate to kick start your new project with SASS support and webpack watch/build tasks

# Features
* SASS support
* webpack watch, build and local server tasks

## Download
```bash
git clone https://github.com/manikandan-ramar/react-redux-boilerplate.git
```

## 1. Setup
```bash
npm install
```
- install all npm dependencies

**Note:** Yarn also can be used, but not used here

## 2. Watch files
```bash
npm run dev
```

- all SCSS and JS files will be watched for changes in port 3000 (`http://localhost:3000/`)

## 3. Build production version
```bash
npm run build
```

- this will process following tasks:
* clean build folder
* compile SASS files to css
* build index.html
* show build folder size

## 3. Build & Run production version
```bash
npm start
```

- production build will be served in port 8080 (`http://localhost:8080/`).

## File Structure
 .
    ├── server                 # production sever setup
    ├── src                    # source files
    ├── static                 # static files to serve
    ├── .babelrc               # babel configuration
    ├── .gitignore             # files and folders to ignore in git
    ├── webpack.config.js      # webpack configuration
    └── ReadMe.md              # ReadMe file
    

## Contribution
 This boilerplate repo will be updated regularly by [me](http://github.com/manikandan-ramar) and also you can also contribute.
