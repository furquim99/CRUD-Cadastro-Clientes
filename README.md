# CRUD-Cadastro-Clientes
Operação de cadastro de clientes

Objetivo completo desta operação, é Utilizar as linguagens Css, Javascript e Html para montar um CRUD que faça as quatro operações basicas criação, consulta, atualização e destruição de dados) utilizadas em bases de dados relacionais (RDBMS) fornecidas aos utilizadores do sistema.

Para isso ser possível são necessárias as páginas que interagem com o CRUD da forma como o sistema deve reagir, e isso depende do sistema (afinal existem n formas de desenvolvimento, e a que tem tomado mais força ultimamente é o SPA - Single Page Aplication graças a ferramentas como ReactJs ou VueJs), e nesse caso as páginas intermediárias tomam conta.

Por exemplo, imagine o fluxo de dados numa tela que mostra os usuários de um sistema e você precisa fazer uma interação entre os resultados das Querys do banco nessa página intermediária (tipo algum cálculo mais complexo que deve ser feito antes de chegar na View). logo o fluxo seria: Sistema solicita -> página intermediária seleciona quais páginas do CRUD vão ser usadas -> CRUD lê os dados do banco (n leituras de n tabelas, agrupadas ou não (no projeto foi usado o localsorage) ) -> Dados chegam na página intermediária e são processadas -> dados tratados vão pra camada mais alta (seja direto pra View ou para o control para serem reinseridos na view)

# REACT

React (also known as React.js or ReactJS) is a free and open-source front-end JavaScript library for building user interfaces or UI components. It is maintained by Facebook and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications.

### npx create-react-app my-app

it's a package runner tool that comes with npm 5.2+. Create React App doesn't handle backend logic or databases; it just creates a frontend build pipeline, so you can use it with any backend you want.

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### vantagens do react
Todo componente pode ser reutilizado em novas partes de sua aplicação sem precisar ser recriado A aplicação fica bem organizada e escalável, ou seja, de fácil manutenção, mesmo que cresça em complexidade e tamanho O desenvolvimento fica mais rápido e limpo;
Uma biblioteca gratuita e de código aberto;
Uma curva de aprendizado direta, simplificando a adoção;
Um DOM leve que geralmente resulta em desempenho forte;
A capacidade de criar, reutilizar e combinar componentes no seu código.


### o Motivo de nao ter usado React nesse codigo
O principal motivo, mesmo considerando React uma ferramenta muito boa de se utilizar, foi a incapacidade de minha maquina de fazer operar o react, tendo problemas nos pacotes de babel-eslint, node-models e constantes erros no comando npm-start
