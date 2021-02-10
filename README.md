
## Recursos

Loaders Webpack
Este iniciador contém os seguintes loaders de webpack:

* Sass Loader para compilar sass (SCSS)
* File loader para carregar arquivos de ativos
* HTML Loader para carregar arquivos HTML
* Babel Loader para compilar código ES6

## Começando

### Requisitos
* Certifique-se de ter o NodeJS 12+ instalado, pois ele contém `npm`, o que é necessário
para instalar dependências, iniciar os scripts apropriados e criar seu projeto da web.

### Quick Start
Clone o repositório, navegue para a pasta do projeto.

Instale todos os pacotes e dependências necessárias para este projeto:

    npm install
    
Iniciando o ambiente de desenvolvimento (http://localhost:8080):

    npm start
 
Em seguida, irá abrir uma nova pagina no seu navegador: http://localhost:8080/
    
Os arquivos de build podem ser feitos da seguinte maneira:

    npm run build

### Como usar
* Adicione seus arquivos HTML inserindo ou incluindo-os no diretório `src` (Por padrão,` index.html` é adicionado ao diretório `src`, fique à vontade para editá-lo).
    
    * Certifique-se de reiniciar o servidor de desenvolvimento após adicionar novos arquivos HTML

* Adicione imagens à sua pasta `src / img`.
* Certifique-se de importar o arquivo img em `index.js`.
* Adicione arquivos sass (SCSS) à pasta `src / scss`.
* Certifique-se de importar o arquivo scss em `main.scss`.
    
`` sass
    import'sass/filename.scss'
`` 

`` img
    import '../img/filename.png'
`` 