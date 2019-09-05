## Frontend_Tindev
Aplicação desenvolvida na 8ª Semana Omnistack da <a href="https://rocketseat.com.br" target="_blank"> Rocketseat</a>.
Uma réplica do Tinder para desenvolvedores.
A mesma consome dados da <a href="https://developer.github.com/v3/" target="_blank">API do GitHub</a> e possui uma base de dados em MongoDB que armazena as informações dos desenvolvedores e os likes e deslikes que os mesmos receberam, quando um desenvolvedor dá um like em um desenvolvedor que já deu um like nele a aplicação exibe a janela informando aos dois desenvolvedores que houve o <strong>Match</strong>. 

![Tindev Web Demo](tindev_web.gif)


# Tecnologias Utilizadas :

* ReactJs
* Axios
* Socket.io-client
* React Router Dom

# Instalação
Para funcionamento da aplicação é necessário utilizar a api <a href="https://github.com/Montezi/Backend_Tindev" target="_blank"> Backend Tindev </a>

**- Se estiver utilizando Yarn**
```
  Todos os comandos abaixo devem ser excutados na raiz do Projeto 
  Para instalar as dependências:
  yarn install 
  Para subir o JSON server :  
  json-server server.json -p 3333 
  
  Para startar a aplicação :
  yarn start 
  
  Executa o aplicativo no modo de desenvolvimento.
  Abra http: // localhost: 3000 para visualizá-lo no navegador. 
   
```

**- Se estiver utilizando npm**
```
  Todos os comandos abaixo devem ser excutados na raiz do Projeto 
  Para instalar as dependências:
  npm install 
  Para subir o JSON server :  
  json-server server.json -p 3333 
  
  Para startar a aplicação :
  npm start 
  
  Executa o aplicativo no modo de desenvolvimento.
  Abra http: // localhost: 3000 para visualizá-lo no navegador. 

```

## Licença

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
