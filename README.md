# Callahan Alistair Hargreaves — Ficha de Personagem

Página de personagem RPG no Stories of Magic.

## ♟️ Xadrez multiplayer

O tabuleiro de xadrez usa conexão **P2P via PeerJS (WebRTC)** — sem servidor, funciona diretamente entre dois navegadores.

### Como usar:
1. **Jogador 1** acessa a página e clica em **CRIAR PARTIDA**
2. Um **código de sala** aparece na tela → copie e envie ao adversário
3. **Jogador 2** acessa a mesma página, cola o código e clica em **ENTRAR**
4. A conexão é estabelecida e o jogo começa automaticamente

> ⚠️ Ambos os jogadores precisam estar na página ao mesmo tempo.

---

## 🎨 Tecnologias usadas

- HTML5 + CSS3 puro (sem frameworks)
- [Google Fonts](https://fonts.google.com) — Oswald, Inter, IM Fell English
- [chessboard.js](https://chessboardjs.com) — renderização do tabuleiro
- [chess.js](https://github.com/jhlywa/chess.js) — validação de movimentos
- [PeerJS](https://peerjs.com) — conexão P2P em tempo real (WebRTC)
- [jQuery](https://jquery.com) — dependência do chessboard.js

Todos os assets externos são carregados via CDN gratuito.

EH NOOOOOOIS

---
