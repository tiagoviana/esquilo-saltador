# 🐿️ Esquilo Saltador

Um jogo web offline no estilo *Infinite Runner Vertical / NinJump* construído inteiramente em um único arquivo `index.html` com **HTML5 Canvas 2D**, **CSS puro** e **JavaScript Vanilla**, com áudio e trilha sonora sintetizados proceduralmente via **Web Audio API**.

---

## 🎮 Como Jogar

Abra o arquivo `index.html` em qualquer navegador web moderno:

- **Mobile:** Toque na tela para saltar para o tronco da árvore oposta.
- **Desktop:** Pressione <kbd>Espaço</kbd>, <kbd>Setas</kbd> ou dê um clique com o mouse.
- **Objetivo:** Escale o mais alto possível, desvie de galhos secos, colmeias e varais de espinhos, e colete nozes douradas para bônus de pontuação!

---

## ✨ Recursos

- **100% Autônomo e Offline:** Zero imagens, fontes ou arquivos de áudio externos.
- **Gráficos em Canvas 2D:**
  - Esquilo estilizado com expressões faciais, orelhas, patinhas animadas e cauda felpuda que oscila senoidalmente.
  - Animação de salto em arco com giro acrobático de 360° no ar e squash & stretch na aterrissagem.
  - Cenário dinâmico com transição gradual de cores do céu conforme a altitude (Manhã $\rightarrow$ Pôr do Sol $\rightarrow$ Noite com estrelas e lua).
  - Três tipos de obstáculos: galhos secos, colmeias com abelhas em órbita e varais de cipó espinhoso.
- **Áudio Procedural com Web Audio API:**
  - Trilha sonora alegre em escala pentatônica maior com timbres de marimba/pluck e linha de baixo.
  - Efeitos sonoros completos: salto, pouso com filtro lowpass, coleta de itens em arpejo, fanfarra de novo recorde e colisão com screen shake.
  - Botão de Mute integrado com isolamento de clique.
- **Física Justa e Responsiva:**
  - Cálculo de física com `deltaTime` (independente de taxas de atualização de 60Hz a 180Hz+).
  - Regra estrita de espaçamento vertical ($\ge 240\text{px}$) entre obstáculos para garantir sempre um caminho viável.
  - Hitbox amigável com 30% de tolerância de colisão.
  - Recorde salvo automaticamente no `localStorage`.
- **Design Adaptativo:**
  - **Mobile:** Ocupa $100\text{vw} \times 100\text{dvh}$ sem barras de rolagem, bloqueando toques e seleções acidentais.
  - **Desktop:** Moldura centralizada elegante estilo arcade/smartphone com instruções laterais.

---

## 🛠️ Tecnologias

- HTML5
- CSS3
- JavaScript (Vanilla ES6+)
- HTML5 Canvas 2D API
- Web Audio API
