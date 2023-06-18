<h1 align="center">
  Portal Tchauzinho
</h1>

<p align="center">
    Um template inicial do Portal Tchauzinho com <a href="https://vitejs.dev">Vite</a> + <a href="https://reactjs.org">React</a> + <a href="https://docs.ethers.org/v5/">EthersJS</a>
</p>

![Portal Tchauzinho](https://i.imgur.com/ociZqkC.png)

## Estrutura de pastas

Nenhuma configuração ou estruturas de pastas complicada, apenas os arquivos necessários para criar seu aplicativo:

```
frontend
├── node_modules
├── public
│   ├── vite.svg
└── src
    ├── App.css
    ├── App.jsx
    ├── index.css
    ├── main.jsx
├── .eslintrc.cjs
├── .gitignore
├── index.html
├── package.json
├── README.md
├── vite.config.js
```

## Desenvolvimento

Para criar uma cópia local do código, clone-o usando git:

```
git clone 
cd portal-tchauzinho-vite
```

Adicione no seu git:

```
rm -rf .git && git init && npm init
git add .
git commit -m "Primeiro commit"
```

Instalando dependencias

```
npm i
```

Agora, você pode iniciar um servidor web local executando:

```
npm start
```

Em seguida, abra <http://localhost:3000> para visualizá-lo no navegador.

### Scripts Disponíveis

In this project, you can run the following scripts:

| Script        | Description                                         |
| ------------- | --------------------------------------------------- |
| npm run dev   | Runs the app in the development mode.               |
| npm run build | Builds the app for production to the `dist` folder. |
| npm run serve | Serves the production build from the `dist` folder. |
