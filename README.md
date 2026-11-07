# 🐍 Snake Game — Arcade Clássico

Um jogo da cobrinha inspirado nos clássicos arcades, desenvolvido com **HTML5, CSS3 e JavaScript puro (Vanilla JavaScript)**. 

O projeto combina uma experiência nostálgica com uma interface moderna, responsiva e intuitiva, proporcionando uma jogabilidade simples, divertida e desafiadora diretamente no navegador.

🎮 **Colete alimentos, aumente sua pontuação, faça sua cobrinha crescer e tente superar seu próprio recorde!**

---

## 📸 Sobre o Projeto

O **Snake Game** é uma aplicação web interativa na qual o jogador controla uma cobra que se movimenta continuamente por um tabuleiro dividido em células.

O objetivo é coletar os alimentos espalhados pelo cenário para aumentar o tamanho da cobra e acumular pontos, evitando colisões com as paredes e com o próprio corpo.

A aplicação foi desenvolvida utilizando tecnologias fundamentais do Front-End, sem frameworks, bibliotecas externas ou dependências de terceiros.

## ✨ Funcionalidades

- 🐍 **Jogabilidade clássica:** movimentação contínua da cobrinha em quatro direções.
- 🍎 **Coleta de alimentos:** cada alimento coletado adiciona 10 pontos à pontuação.
- 📈 **Crescimento progressivo:** a cobrinha aumenta de tamanho ao consumir alimentos.
- ⚡ **Dificuldade progressiva:** a velocidade aumenta conforme a pontuação evolui.
- 🏆 **Sistema de recorde:** melhor pontuação salva automaticamente no navegador utilizando LocalStorage.
- 💥 **Detecção de colisões:** encerramento da partida ao atingir as paredes ou o próprio corpo.
- ⏸️ **Sistema de pausa:** possibilidade de pausar e continuar a partida.
- 🔄 **Reiniciar partida:** opção para começar um novo jogo a qualquer momento.
- 📱 **Controles responsivos:** suporte a teclado, botões direcionais e gestos de toque (swipe).
- 🎨 **Interface moderna:** identidade visual inspirada nos jogos arcade, com cores vibrantes, efeitos visuais e animações suaves.
- 📊 **Placar em tempo real:** acompanhamento da pontuação atual e do recorde.
- ♿ **Acessibilidade básica:** identificação de elementos e mensagens de status para tecnologias assistivas.

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Aplicação |
|---|---|
| 🟠 HTML5 | Estrutura e organização da aplicação. |
| 🔵 CSS3 | Estilização, layout responsivo e efeitos visuais. |
| 🟡 JavaScript (Vanilla JS) | Lógica do jogo, movimentação, colisões e interatividade. |
| 🎨 Canvas API | Renderização gráfica da cobrinha, alimentos e tabuleiro. |
| 💾 LocalStorage | Armazenamento persistente do recorde do jogador. |
| 🎞️ RequestAnimationFrame | Controle do ciclo de animação e atualização do jogo. |

### 💡 Destaques Técnicos

- Código organizado em funções com responsabilidades específicas.
- Uso de JavaScript puro, sem frameworks ou bibliotecas externas.
- Renderização utilizando a API Canvas do HTML5.
- Controle de tempo baseado em `requestAnimationFrame`.
- Movimentação baseada em uma grade de 24 × 24 células.
- Gerenciamento de estados da partida: pronto, em execução, pausado e encerrado.
- Tratamento de indisponibilidade do LocalStorage.
- Interface adaptável a diferentes tamanhos de tela.

## 🎮 Como Jogar

O objetivo é controlar a cobrinha, coletar os alimentos e alcançar a maior pontuação possível sem colidir com as paredes ou com o próprio corpo.

### ⌨️ Controles

| Tecla / Comando | Ação |
|---|---|
| ⬆️ Seta para cima / W | Mover para cima |
| ⬇️ Seta para baixo / S | Mover para baixo |
| ⬅️ Seta para esquerda / A | Mover para esquerda |
| ➡️ Seta para direita / D | Mover para direita |
| Espaço | Pausar / Continuar |
| ESC | Pausar a partida |

### 📱 Dispositivos móveis

Em dispositivos com tela sensível ao toque, também é possível controlar a cobrinha utilizando:

- Botões direcionais exibidos na interface.
- Gestos de deslizar (swipe) diretamente sobre o tabuleiro.

## 🚀 Como Executar o Projeto

Não é necessário instalar dependências, configurar servidores ou utilizar ferramentas adicionais.

**1. Clone o repositório:**

```bash
git clone https://github.com/SEU-USUARIO/snake-game.git
```

**2. Entre na pasta do projeto:**

```bash
cd snake-game
```

**3. Execute o jogo:**

Abra o arquivo `index.html` diretamente no navegador de sua preferência.

Pronto! 🎉 O jogo estará disponível para jogar.

## 📂 Estrutura do Projeto

O projeto foi desenvolvido em um único arquivo HTML, concentrando toda a implementação em um só lugar.

```text
snake-game/
│
├── index.html       # Estrutura HTML, estilos CSS e lógica JavaScript
│
└── README.md        # Documentação do projeto
```

## 🏆 Pontuação e Dificuldade

- Cada alimento coletado vale **10 pontos**.
- A cada 30 pontos acumulados, a velocidade da cobrinha aumenta.
- A velocidade inicial é de 145 milissegundos por movimento.
- A velocidade máxima é limitada a um intervalo de 72 milissegundos.
- O recorde é armazenado localmente no navegador.

## 🎨 Identidade Visual

O jogo apresenta uma estética arcade moderna, com:

- 🌑 Fundo escuro e elementos em tons de verde.
- 💚 Cobrinha com tonalidades verdes e destaque luminoso na cabeça.
- 🌸 Alimentos em destaque na cor rosa.
- ⭐ Recorde destacado em dourado.
- ✨ Efeitos de sombra, transparência e cantos arredondados.

## 📌 Objetivos do Projeto

Este projeto foi desenvolvido com o propósito de praticar e demonstrar conhecimentos em desenvolvimento Front-End, especialmente:

- Manipulação do DOM.
- Lógica de programação com JavaScript.
- Manipulação e renderização com Canvas API.
- Eventos de teclado e interação por toque.
- Controle de animações com RequestAnimationFrame.
- Gerenciamento de estados e eventos.
- Armazenamento de dados com LocalStorage.
- Desenvolvimento de interfaces responsivas.
- Organização e boas práticas de código.

## 🔮 Possíveis Melhorias Futuras

- 🎵 Adicionar efeitos sonoros e música de fundo.
- 🎨 Implementar temas visuais alternativos.
- 🥇 Criar diferentes níveis de dificuldade.
- 📊 Desenvolver um ranking de pontuações.
- ⏱️ Adicionar cronômetro e estatísticas da partida.
- 🎮 Implementar novos modos de jogo.

## 👨‍💻 Autor

Desenvolvido por **Eduardo da Silva**.

💻 Projeto criado para praticar e aprimorar habilidades em desenvolvimento Front-End utilizando tecnologias nativas da Web.

---

⭐ Se você gostou do projeto, deixe uma estrela no repositório!

🐍 **Divirta-se e tente bater seu recorde!**
