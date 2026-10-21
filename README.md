# Detetive Lógico

![License](https://img.shields.io/badge/license-MIT-amber.svg)
![Technology](https://img.shields.io/badge/tech-HTML5%20%7C%20TailwindCSS%20%7C%20Vanilla%20JS-blue.svg)
![Audio](https://img.shields.io/badge/audio-Web%20Audio%20API-green.svg)
![Status](https://img.shields.io/badge/status-Complete-success.svg)

> Um jogo de mistério, investigação e dedução matemática procedural ambientado em um gabinete de fliperama.

---

## Sobre

**Detetive Lógico** é uma aplicação web interativa em um único arquivo inspirada nos clássicos gabinetes de fliperama. O objetivo do jogo é colocar o jogador na pele de um detetive que precisa solucionar crimes utilizando exclusivamente **regras de inferência da lógica formal e matemática**, abandonando achismos e intuição.

O jogo é inteiramente construído com **HTML5, CSS3 (Tailwind CSS) e JavaScript puro**, além de sintetizar sua própria trilha sonora de Jazz Noir em tempo real através da **Web Audio API**.

---

## Conceitos Lógicos Utilizados

1. **Modus Ponens & Modus Tollens (Condicional Direta e Negação):**
   - Implicações da forma $P \rightarrow Q$. Se a premissa é verdadeira, a consequência obrigatoriamente se confirma. De forma inversa, a negação da consequência implica a negação da premissa ($\neg Q \rightarrow \neg P$).
2. **Redução ao Absurdo (*Reductio ad Absurdum*):**
   - Assume-se temporariamente a inocência de um suspeito. Se essa hipótese resultar em uma contradição física ou lógica impossível no cenário do crime, a hipótese inicial é provada falsa, confirmando a culpa.
3. **Silogismo Disjuntivo & Eliminação:**
   - Estruturas de disjunção $A \lor B$. Ao provar a inocência de um dos suspeitos por meio de álibis ou ausência de evidências periciais, deduz-se que o outro é o culpado.

---

## Funcionalidades e Recursos

- **Visual CRT & Fliperama Noir:** Moldura em estilo gabinete arcade, linhas de varredura (*scanlines*), efeito de reflexo em tela escura e neon retrô.
- **Arte Vetorial Responsiva:** Ilustração atmosférica do detetive com efeitos de iluminação de rua e partículas de fumaça animadas.
- **Trilha Sonora Sintetizada (Jazz Noir):** Arranjo procedimental contínuo contendo *walking bass*, acordes de piano jazz e ruído de prato *brush* gerados via código, sem dependência de arquivos MP3 ou áudios externos.
- **Três Níveis de Dificuldade:**
  - **Fácil:** 3 Suspeitos — Dedução direta por Modus Ponens.
  - **Médio:** 4 Suspeitos — Negações e Silogismo Disjuntivo.
  - **Difícil:** 5 Suspeitos — Prova por Redução ao Absurdo.
- **Quadro de Rascunho / Tabela de Dedução:** Ferramenta interativa de marcação para testar e eliminar suspeitos.

---

## Controles e Atalhos

| Tecla / Ação | Função |
| :--- | :--- |
| **`F1`** | Iniciar partida no menu principal / Iniciar novo caso na tela de resultados. |
| **`P`** | Voltar ao menu principal ou reiniciar a partida a qualquer momento. |
| **Clique do Mouse** | Navegar entre as abas do relatório, alterar hipóteses e confirmar a acusação. |
| **Botão de Áudio** | Ativar ou desativar a trilha sonora de Jazz e os efeitos sonoros *retro*. |

---

## Como Executar Localmente

Como a aplicação é contida em um único arquivo autônomo, não é necessário instalar dependências, compilar código ou configurar servidores Node.js.

1. Clone o repositório ou baixe o arquivo `index.html`:
   ```bash
   git clone https://github.com/seu-usuario/detetive-logico.git
   ```
2. Navegue até a pasta do projeto:
   ```bash
   cd detetive-logico
   ```
3. Abra o arquivo `index.html` em qualquer navegador moderno (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).

---

## Tecnologias Utilizadas

- **HTML5:** Estruturação semântica da interface do gabinete e painéis do relatório.
- **Tailwind CSS (CDN):** Estilização ágil, grid layout e componentes visuais.
- **Vanilla JavaScript (ES6+):** Motor de geração de casos, gerenciamento do estado do jogo, manipulação do DOM e lógica de inferência.
- **Web Audio API:** Síntese de som em tempo real para música de fundo e efeitos sonoros (*typewriter*, botões e vereditos).

---

## Licença

Este projeto está sob a licença [MIT](LICENSE). Sinta-se livre para estudar, modificar e distribuir o código.
