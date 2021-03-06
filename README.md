React Quick Start [NPM+Webpack generate]
============================

:warning: Test or developed project.

<p align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/280px-React-icon.svg.png"></p>

This is React Quick Start by [Atlogex](https://www.atlogex.com/).
Generate build files with help NPM (Node.js) and Webpack. Read More about install react + babel + webpack in post [Run React app use NPM, Babel and Webpack 3](https://atlogex.com/firstrun-react-app/).


 Directory Structure
 -------------------

       src/                      - source files
       public_html/              - entry point
       public_html/build/        - generate React files

 Stack
 -------------------

- [React](https://reactjs.org/)
- [Webpack](https://webpack.js.org/)
- [LESS](http://lesscss.org/) / [SCSS](https://sass-scss.ru/)
- [Gulp](https://gulpjs.com/) `(maybe)`


 UI Design
 -------------------

Choise and add UI library in `package.json` block 'dependencies':

 - [Material UI](http://www.material-ui.com/)  <br/>
 ```"material-ui": "*",```
 - [React MD](https://react-md.mlaursen.com/)  <br/>
 ```"react-md": "*",```
 - [Ant Design](https://ant.design/)  <br/>
 ```"antd-ui": "*",```
 - [Microsoft Fabric](https://developer.microsoft.com/en-us/fabric)  <br/>
 ```"office-ui-fabric-react": "*"```


Sample for use Material UI:
```
"dependencies": {
    "material-ui": "*",
    "react": "*",
    "react-dom": "*"
  },
```

 Install
 -------------------

Clone repo in your directory

> git clone https://github.com/Atlogex/ReactAxQuickstart.git .

Install components (need NPM from Node.js)

> npm i