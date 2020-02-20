# Doe
Projeto desenvolvido durante a Maratonadev da Rocketseat, que é uma base de dados para pessoas interessadas em doar sangue, onde ela pode realizar seu cadastro e ser inserida numa base de dados.

![](C:\Users\GUTO\Pictures\Doe\1.png)
![](C:\Users\GUTO\Pictures\Doe\2.png)

# Instalação
1) Necessário ter instalado na máquina o [Node](https://nodejs.org/en/) e um gerenciador de pacotes como [Yarn](https://yarnpkg.com/) ou [NPM](https://www.npmjs.com/).
2) Se você tem instalado o [Git](https://git-scm.com/) na máquina, pode clonar o repositório clicando em **Clone or download**.
3) Instalar o [Postgres](https://www.enterprisedb.com/).
4) Após ter feito a instalação necessária, poderá utilizar o projeto em um editor de sua preferência, mas recomendo o [VSCode](https://code.visualstudio.com/), pois já faz uma boa integração com as ferramentas que foram instaladas.

# Como usar
Para utilizar o projeto, poderá seguir as seguintes etapas, já dentro do seu editor.
![](C:\Users\GUTO\Pictures\Doe\3.png)

1) Após, ir até o arquivo **server.js** e alterar a opção de 
```
const db = new Pool({
    user: '',
    password: '',
    host: '',
    port: ,
    database: ''
})
```
de acordo com as informações que você cadastrou no BD.

Ex: 
```const db = new Pool({
    user: 'postgres',
    password: 'postgre',
    host: 'localhost',
    port: 5432,
    database: 'doe'
})
```
2) Ir até o arquivo **database.sql**, copiar e executar isso no seu BD, para poder criar sua tabela.

3) Abrir o terminal e realizar os seguintes comandos para instalar todas as dependências do projeto. Podendo ser o yarn ou npm, fica a seu critério
```
yarn ou npm install
```
## Como executar
No terminal executar os seguintes comandos e seu projeto já estará em execução.
```
yarn start ou npm start
```
Após, abrir o browser e colocar o seguinte caminho: **[nome do host que definiu no método new Pull]:3000** .