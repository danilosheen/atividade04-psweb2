# Evolução da API-Projetos e Sistemas WEB 2
## Licença
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/danilosheen/web2-atividade03/blob/main/License)
## Sobre o projeto
Projeto proposto como atividade 4 para adição de testes nas rotas cadastradas
## Tecnologias utilizadas
[![Tecnologias](https://skillicons.dev/icons?i=nodejs,postgres)](https://skillicons.dev)
## Como rodar o projeto
### Pré-requisitos
- Nodejs ver. 18.15.0 LTS
### Como executar
- Abra o terminal na raiz do projeto e rode o seguinte comando
```bash
node npm install
```
- Após carregar todos os pacotes necessários rode o seguinte comando
```bash
node index.js
```
- Abra o navegador no endereço <a href="https://127.0.0.1:3000">127.0.0.1:3000/</a>
- Agora é só adicionar a rota que deseja acessar
## Rotas cadastradas:
### Alunos
- Get
  - <a href="https://127.0.0.1:3000/alunos">/alunos</a>
  - <a href="https://127.0.0.1:3000/alunos/id">/alunos/id</a>
- Post
  - <a href="https://127.0.0.1:3000/login">/login</a>
  - <a href="https://127.0.0.1:3000/alunos">/alunos</a>
- Put
  - <a href="https://127.0.0.1:3000/alunos/id">/alunos/id</a>
- Delete
  - <a href="https://127.0.0.1:3000/alunos/id">/alunos/id</a>
  
### Assuntos
- Get
  - <a href="https://127.0.0.1:3000/assuntos">/assuntos</a>
  - <a href="https://127.0.0.1:3000/assuntos/id">/assuntos/id</a>
- Post
  - <a href="https://127.0.0.1:3000/assuntos">/assuntos</a>
- Put
  - <a href="https://127.0.0.1:3000/assuntos/id">/assuntos/id</a>
- Delete
  - <a href="https://127.0.0.1:3000/assuntos/id">/assuntos/id</a>
  
### Encontros
- Get
  - <a href="https://127.0.0.1:3000/encontros">/encontros</a>
- Post
  - <a href="https://127.0.0.1:3000/encontros">/encontros</a>
- Put
  - <a href="https://127.0.0.1:3000/encontros/id">/encontros/id</a>
- Delete
  - <a href="https://127.0.0.1:3000/encontros/id">/encontros/id</a>

#### As rotas de criação, atualização e remoção exigem que o usuário esteja logado utilizando autenticação JWT passado para login pelo parâmetro x-access-token
##### - Os dados de login se encontram no <a href="https://github.com/danilosheen/web2-atividade03/blob/main/.env">.env</a>
##### - foram adicionados testes nas rotas cadastradas
  ---
 ### Autor

<a href="https://github.com/danilosheen/">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/49424200?v=4" width="100px;" alt=""/>
 <br />
 <sub><b>Danilo Ferreira</b></sub></a> <a href="https://github.com/danilosheen" title="GitHub"></a>


 Entre em contato!

[![Linkedin Badge](https://img.shields.io/badge/-Danilo-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/danilo-ferreira-b56969194/)](https://www.linkedin.com/in/danilo-ferreira-b56969194/) [![Gmail Badge](https://img.shields.io/badge/-c.danilo.f.siva@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:c.danilo.f.siva@gmail.com)](mailto:c.danilo.f.siva@gmail.com)

