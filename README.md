# <Next-Level-Week_2> ⚛
Projeto realizado durante a semana NLW#2 da Rocketseat
<p align="center">
  <img alt="License" src="./docs/NLW.gif">
</p>

## :computer: Projeto

Projeto Web e Mobile desenvolvido durante o programa Next Level Week da Rocketseat. Trata-se de uma plataforma que busca conectar alunos e professores. Por meio dela, professores podem fazer cadastro das matérias que lecionam, horários disponíveis, valor das aulas e seu contato. Os alunos podem pesquisar a lista de professores disponíveis, entrar em contato com eles e favoritá-los.

## :wrench: Tecnologias Utilizadas:

- ReactJS
- Javascript
- Axios
- React-Native
- Node.js
- Express
- Knex.js
- SQLite

## :heavy_check_mark: Pré-requisitos:

- **[Git](https://git-scm.com/)** instalado e configurado
- Ter o **[Node.js](https://nodejs.org/en/)** instalado
- Gerenciador de pacotes **[NPM](https://www.npmjs.com/)** ou **[Yarn](https://yarnpkg.com/)**.
- **[Expo](https://expo.io/)** instalado de forma global na máquina

Endereço da aplicação: http://localhost:3000/

## :star: Para contribuir:

1. Faça o _fork_ do projeto (<https://github.com/matheusfelipeog/proffy>)

2. Clone o seu _fork_ (`git clone https://github.com/user_name/proffy.git`)

3. Crie uma _branch_ para realizar a modificação (`git checkout -b feature/name_new_feature`)

4. Adicione as modificações e faça o _commit_ (`git commit -m "Descreva sua modificação"`)

5. _Push_ (`git push origin feature/name_new_feature`)

6. Crie um novo _Pull Request_

## Para Instalar
1. passo: Inatale:
- Node.js ([https://nodejs.org](https://nodejs.org/en/))
- Git Bash ([https://gitforwindows.org](https://gitforwindows.org/))
2. passo:
Após baixar o projeto, acesse ele via seu terminal e rode o comando:

```sh
npm install
```
```sh
npm install nunjucks
```
```sh
npm install sqlite-async
```

## Para rodar o projeto: 🚀

```sh
npm run dev
```

## Desafios
### 01 - Página de sucesso

- Mostrar página de sucesso após o cadastro do proffy
- aguardar 2 segundos na página e redirecionar para a listagem dos proffys, com filtro
    - use setTimeout para aguardar os 2 segundos
    - location.href = ""

### 02 - Correção de bugs

- Não permitir o usuário colocar um novo campo de dia e horário, se o dia e hora anterior estiver vazio
- Funcionalidade de deletar um campo de dia e hora
