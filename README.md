## Lazy Loading JS

Este é um projeto de uma página web simples desenvolvida em HTML, CSS e JavaScript.
Este projeto foi criado como parte de curso de formação frontend.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript

## Funcionalidades

- Lazy Loading JavaScript

    O Lazy Loading é implementado utilizando JavaScript. 
    Quando a página é carregada, apenas as imagens inicialmente visíveis na visualização são carregadas. Esta é uma técnica de otimização de desempenho que adia o carregamento de recursos não essenciais, até que sejam necessários. Conforme o usuário rola a página para baixo, as imagens são carregadas dinamicamente, melhorando o desempenho e reduzindo as solicitações de rede desnecessárias. 


- API Intersection Observer
    
    O código JavaScript utiliza a API Intersection Observer para detectar quando as imagens entram na visualização do usuário. Quando uma imagem está prestes a entrar na visualização, seu atributo src é atualizado para o caminho da imagem de alta resolução, substituindo o caminho da imagem de baixa resolução. Isso garante que apenas as imagens visíveis na tela sejam carregadas, enquanto as imagens fora da visualização são adiadas até que sejam necessárias.


## Estrutura do Projeto

- `index.html`: O arquivo HTML principal que contém a estrutura da página.
- `css/styles.css`: Estilos CSS para a aparência da página.
- `js/scripts.js`:  Arquivo JavaScript para adicionar interatividade à página.


## Autores

- [@RaquelGui](https://www.github.com/RaquelGui)

Sinta-se à vontade para utilizar, modificar e adaptar este conteúdo, de acordo com as necessidades específicas do seu projeto. 