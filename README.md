<h1 align="center"> NLW Copa Ignite </h1>

<p align="center">
Evento exclusivo e gratuito, promovido pela Rocketseat para ensino de tecnologias WEB.
</p>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<br>

<p align="center">
  <img alt="nlw-copa" src="web/src/assets/Web.png" width="100%">
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [React](https://pt-br.reactjs.org/)
- [Next.js](https://nextjs.org/)
- [React Native](https://reactnative.dev/)
- [Native Base](https://nativebase.io/)
- [TypeScript](https://www.typescriptlang.org/)
- [Expo](https://expo.dev/)
- [Expo Go](https://expo.dev/client)
- [TailwindCSS](https://tailwindcss.com/)
- [Prisma](https://www.prisma.io/)
- [Node e NPM](https://nodejs.org/)


## 💻 Projeto

 Um bolão da Copa, uma aplicação completa, web e mobile, pra garantir a diversão da família e dos amigos durante os jogos. 
## 🔖 Layout

Você pode visualizar o layout do projeto através [DESSE LINK](https://www.figma.com/file/39pjafPWhhyPBBAgoYNv9f/Bol%C3%A3o-da-Copa-(Community)?node-id=316%3A2316). É necessário ter conta no [Figma](https://figma.com) para acessá-lo.


## 🚀 Recomendações

## Server

entre na pasta `server` presente no diretório raiz, e rode o comando para instalar as dependências:

```bash
npm i
```

Agora para criar o banco de dados

Primeiramente crie um arquivo na raiz da pasta `server` chamado `.env` e depois cole nesse arquivo

```bash
   DATABASE_URL="file:./dev.db"
```
depois 

```bash
npx prisma migrate dev
```

Por fim para iniciar o servidor, rode o comando:

```bash
npm run dev
```

## Web

Para rodar o projeto web, entre na pasta `web` e rode o comando para instalar as dependências:

```bash
npm i
```

Agora para iniciar o projeto, rode o comando:

```bash
npm run dev
```

## Mobile

Para rodar o projeto mobile você precisará baixar o app [Expo Go](https://expo.dev/client).
Após baixar o app, entre na pasta `mobile` e rode o comando para instalar as dependências:

```bash
npm i
```

Agora para iniciar o projeto:

```bash
npx expo start
```

>Sempre que iniciar o `Web` ou `Mobile` lembre-se de estar com o `Server` iniciado!




## :memo: Licença

Esse projeto está sob a licença MIT.

---

<p align="center">Feito com ♥ por mim junto com a Rocketseat :wave: </p>


