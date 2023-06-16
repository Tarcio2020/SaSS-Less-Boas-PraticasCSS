# SaSS-Less-BoasPraticasCSS

Instalar a extensão Sass no VS Code.<br>

npm init<br>

npm i --save-dev sass<br>
//Cria node_modules<br><br><br>

Crie uma pasta .gitignore <br>
coloque o nome das pastas que deseja ignora no GIT dentro do arquivo ex: node_modules<br><br><br>

Vamos no arquvo >> package.json <<<br>
Na parte "scripts"<br>
"scripts": "sass",<br>

npm run sass<br><br>

Definir os arquivos de Entrada e Saída...<br>
npm run sass main.scss main.scss<br><br>

coloque link html-css<br><br><br>



OU<br><br>

Organização:<br><br>
Crie:<br>
uma Pasta build <br>
  main.css<br>
    main.css.map<br>
e<br>
Pasta source<br>
  main.scss<br><br>
  
Criando os arquivos da pasta build automaticamente.<br><br>

Vamos no arquvo >> package.json <<<br>
Na parte "scripts"<br>
"scripts": "sass source/main.scss build/main.css",<br>













