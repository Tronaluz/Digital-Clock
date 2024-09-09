# 🕒 Relógio Digital

![Imagem do Relógio Digital](https://user-images.githubusercontent.com/84548221/201499100-03685ad7-340c-4eac-9d10-00649747d7ec.PNG)

Um simples projeto de relógio digital criado com HTML, CSS e JavaScript.

## 📜 Descrição

Este projeto é um relógio digital básico que exibe a hora atual em horas, minutos e segundos. Utiliza HTML para a estrutura, CSS para o estilo e JavaScript para a funcionalidade. É uma aplicação web simples que demonstra como criar uma interface de relógio funcional e estilizada.

## 🗂️ Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

- **index.html**: Estrutura HTML do relógio digital.
- **assets/css/style.css**: Estilo CSS do relógio digital.
- **assets/js/script.js**: Código JavaScript que atualiza o relógio em tempo real.

## 🚀 Instalação

Não é necessário instalar nada para rodar este projeto. Basta abrir o arquivo `index.html` em um navegador moderno.

## 💻 Uso

1. Abra o arquivo `index.html` em seu navegador para visualizar o relógio digital em ação.
2. O relógio será atualizado automaticamente para mostrar a hora atual.

## 🎨 Estilo

O estilo do relógio digital é definido no arquivo `assets/css/style.css`. Abaixo estão algumas das principais características:

- **Fonte**: Open Sans, importada do Google Fonts.
- **Fundo da Página**: Gradiente linear que vai do laranja claro ao vermelho.
- **Relógio**: Exibido com três divisões (Horas, Minutos e Segundos) com fundo escuro e texto branco.
- **Sombras e Bordas**: Sombras e bordas arredondadas para um efeito moderno e limpo.

### Exemplo de CSS

```css
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;500&display=swap');

* {
    margin: 0;
    padding: 0;
    font-family: 'Open Sans', sans-serif;
}

body {
    height: 100vh;
    background: linear-gradient(120deg, #ffe53bd8, #ff2525da);
    display: flex;
    align-items: center;
    justify-content: center;
}

.relogio {
    display: flex;
    align-items: center;
    justify-content: space-around;
    height: 300px;
    width: 550px;
    background: transparent;
    border-radius: 3px;
    box-shadow: 0px 8px 10px rgba(0, 0, 0, .5);
}

.relogio div {
    height: 170px;
    width: 150px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: #fff;
    background: rgba(5, 5, 5, .9);
    box-shadow: 5px 5px 15px rgba(0, 0, 0, .7);
    border-radius: 7px;
    letter-spacing: 3px;
}

.relogio span {
    font-weight: bolder;
    font-size: 60px;
}

.relogio span.tempo {
    font-size: 20px;
}
