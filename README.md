# 📷 Galeria de Portfólio Interativa

## 🎯 Objetivo do Projeto
Esse projeto foi criado como parte do Curso de Web Moderno com o objetivo de colocar em prática conceitos essenciais de desenvolvimento front-end, como:

✔ Manipulação do DOM com JavaScript puro

✔ Filtragem dinâmica de conteúdo sem recarregar a página

✔ Responsividade com Bootstrap 4

✔ Build e otimização usando Webpack

Além disso, serviu como um portfólio interativo para exibir fotos de diferentes cidades (Nova York, Florianópolis e Rio de Janeiro) de forma organizada e visualmente atraente.


## 🔧 Como Surgiu a Ideia
Senti a necessidade de criar algo que unisse:

Prática de JavaScript (eventos, filtros, manipulação de elementos)

Design Responsivo (Bootstrap + CSS customizado)

Otimização de Imagens (compressão e carregamento eficiente)

A ideia foi desenvolver uma galeria que permitisse filtrar imagens por cidade, simulando um projeto real que poderia ser usado em um site de fotografia ou viagens.


## ✨ Funcionalidades

### Filtragem Inteligente
- Seletor por cidades (Nova York, Florianópolis, Rio)
- Transições suaves entre imagens
- Layout responsivo para todos os dispositivos

### Tecnologias Implementadas
| Frontend         | Build Tools       | Estilos         |
|------------------|-------------------|-----------------|
| HTML5 Semântico  | Webpack 4         | Sass (.scss)    |
| JavaScript ES6+  | Babel             | Bootstrap 4     |
| jQuery 3.3.1     | File-loader       | Font Awesome    |

## 🛠️ Configuração do Ambiente

### 1. **Pré-requisitos**
```bash
   Node.js <= 14.x
   npm >= 6.

   git clone https://github.com/CaueReis/projeto-galeria-portifolio.git

   cd projeto-galeria-portifolio

   npm install

   # Dev server (localhost:9000)
    npm start

   # Build produção
    npm run build
````

## 2.📂 Estrutura do Projeto
```bash
projeto-galeria-portifolio/  
├── dist/                  # Pasta de build (gerada pelo Webpack)  
├── src/  
│   ├── js/                # Lógica principal  
│   │   ├── gallery.js     # Filtro por cidades  
│   │   └── includes/      # Funções compartilhadas  
│   ├── scss/              # Estilos em Sass  
│   │   ├── _variables.scss  
│   │   └── main.scss      # Estilo global  
│   └── index.js           # Ponto de entrada  
├── public/  
│   ├── imgs/              # Imagens otimizadas  
│   └── index.html         # HTML principal  
├── webpack.config.js      # Config do Webpack  
└── package.json           # Dependências e scripts  
````
## 🚀 Próximas Melhorias
Lightbox para ampliar imagens

Lazy Loading para carregamento sob demanda

Animações CSS ao filtrar imagens

Integração com API (ex: Flickr) para buscar fotos dinamicamente



## 📸 Prévia

![image](https://github.com/user-attachments/assets/7466ae0d-789f-4a29-960b-359813b79228)
![image](https://github.com/user-attachments/assets/82e6c2ac-5b9d-4b88-97ea-458bdc0ca56d)
