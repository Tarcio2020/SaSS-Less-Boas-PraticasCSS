# Sass

Instalar a extensão Sass no VS Code.

  npm init

  npm i --save-dev sass

//Cria node_modules

Crie uma pasta 
  
  .gitignore

coloque o nome das pastas que deseja ignora no GIT dentro do arquivo ex: node_modules

Vamos no arquvo >> package.json

  Na parte "scripts"
  "scripts": "sass",

  npm run sass

Definir os arquivos de Entrada e Saída...
  npm run sass main.scss main.scss

coloque link html-css



ou

Organização:

Crie:

uma Pasta build

    main.css
    main.css.map

e

Pasta source
  main.scss
  
Criando os arquivos da pasta build automaticamente.

Vamos no arquvo >> package.json 
  Na parte "scripts"
  "scripts": "sass source/main.scss build/main.css",













