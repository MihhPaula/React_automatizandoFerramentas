REACT PARA INICIANTES
Ferramentas de Automação


Bundler
Agrupa (bundle) o código do seu aplicativo

Permite definirmos os componentes em diferentes arquivos para melhor organização

Facilita a importação de código externo instalado via NPM

ESBuild, Rollup, Parcel, Turbopack, Webpack


Transpiler
Transforma JSX return <div></div> em funções de React React.createElement()

Transforma JavaScript novo const em JavaScript antigo var

Babel, SWC, ESBuild



ESBuild Mínimo
https://esbuild.github.io/


Iniciando pacote npm na pasta do aplicativo.
npm init -y



Instalar o ESBuild
npm install esbuild


Adicionar os scripts de desenvolvimento e build ao package.json

"scripts": {
  "start": "esbuild --bundle src/main.jsx --outfile=main.js --servedir=./ --watch",
  "build": "esbuild --bundle src/main.jsx --outfile=main.js"
},



React
npm install react react-dom
