# 🐾 MundoPet Blog

Este é um projeto simples de blog voltado para o mundo dos pets, onde esta sendo apresentado somente atualmente a HOME do site. Ele foi inicialmente criado com **HTML** e **CSS** com o objetivo de relembrar os conceitos fundamentais dessas tecnologias, para posteriormente aplicar **React + TypeScript**. 

## 🧩 Desafio futuro:

Criar um **blog** utilizando **React**, com os seguintes requisitos:

- Uma **Navbar** (menu superior) fixa com links de navegação.
- Um componente **Home** que exibe a **página inicial** com uma introdução e/ou destaque.
- Os **posts** devem ser carregados em um **outro componente**, podendo ser **criador e editados** dinamicamente pelo usuário.

---

## 🔍 O que foi feito

### 📄 HTML (`index.html`)

- **Navbar (barra de navegação)** localizada no topo da página:
  - Contém o logo **"MundoPet"**.
  - Menu com três opções: **Home**, **Sobre** e **Criar post**.

- **Banner principal** com imagem em destaque e texto sobreposto, apresentando uma breve introdução ao blog.

- **Seção de posts** com três artigos básicos como exemplo:
  - *Como cuidar do seu filhote nos primeiros meses*
  - *10 curiosidades sobre gatos*
  - *Alimentação natural para cães*

- **Sidebar (barra lateral)** com categorias de animais:
  - Mamíferos
  - Aves
  - Répteis
  - Anfíbios
  - Peixes
  - Insetos

- **Rodapé** simples com um texto de autoria.

---

### 🎨 CSS (`index.css`)

- O arquivo CSS foi criado para estilizar o HTML, tornando o site mais atrativo e agradável visualmente.
- Estilos aplicados em:
  - Cabeçalho fixo.
  - Layout dividido entre conteúdo e barra lateral
  - Botões de leitura com `hover`
  - Tipografia com fontes do Google Fonts

---

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- Google Fonts (`Lora`, `Candal`)
- Font Awesome (`fa-bars`)
- 
## 🎨 Imagem do layout:
![image](https://github.com/user-attachments/assets/17f9408b-6558-4887-8e0f-bffaf2c20d3a)

## 🔮 Atualizações Futuras
A migração para React + TypeScript incluirá:
- Estruturar o projeto por divisão de pastas para melhor se utilizar com o React
- Um componente 'home' que possui uma página inicial
- Criação  de posts que são carregados em um outro componente, criados e alterados.
- Uso de **hooks** (`useState`, `useEffect`)
  - `useState`: para gerenciamento de estados locais, como contador de cliques ou lista de posts
  - `useEffect`: para carregar dados dinamicamente (ex: simular uma chamada de API e exibir posts em um grid 3x3)
- Passagem de **props** para comunicação entre componentes pai e filho
- Práticas de componentização reutilizável
  
# 🌬️ Como Executar
## Passos para Execução

### 1. Clone o repositório
```bash
https://github.com/sylviavitoria/Blog/tree/dev
```
### 2. Vá para a pasta do projeto
```bash
cd vite-project
```
### 3. Execute a aplicação
```bash
npm run dev
```
