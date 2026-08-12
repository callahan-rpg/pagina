# Callahan Alistair Hargreaves — Ficha de Personagem

Página de personagem RPG no universo de Harry Potter.

## 📁 Estrutura de arquivos

```
hargreaves-character-page/
├── index.html              ← Página principal
├── callahan_hero.jpg       ← Foto do personagem (hero)
├── callahan_profile.jpg    ← Foto do personagem (perfil)
├── hero_werewolf.jpg       ← Lobisomem (hero, lado direito)
├── showcase_wolf.jpg       ← Lobo nas Terras Altas (showcase)
├── feature_werewolf.jpg    ← Lobisomem close-up (feature)
├── castle_hargreaves.jpg   ← Castelo escocês (cards)
└── README.md               ← Este arquivo
```

## 🌐 Publicar no GitHub Pages

### Passo 1 — Criar repositório no GitHub
1. Acesse [github.com](https://github.com) e faça login
2. Clique em **New repository** (botão verde)
3. Nome sugerido: `hargreaves` ou `callahan-hargreaves`
4. Deixe como **Public** (obrigatório para GitHub Pages gratuito)
5. Clique em **Create repository**

### Passo 2 — Fazer upload dos arquivos
1. Na página do repositório recém-criado, clique em **Add file → Upload files**
2. Arraste **todos os arquivos desta pasta** (index.html + todas as imagens .jpg)
3. Clique em **Commit changes**

### Passo 3 — Ativar GitHub Pages
1. Vá em **Settings** (aba do repositório)
2. No menu lateral esquerdo, clique em **Pages**
3. Em **Source**, selecione **Deploy from a branch**
4. Em **Branch**, selecione **main** e pasta **/ (root)**
5. Clique em **Save**

### Passo 4 — Acessar a página
Após ~2 minutos, sua página estará disponível em:
```
https://SEU_USUARIO.github.io/NOME_DO_REPOSITORIO/
```
Exemplo: `https://callahan.github.io/hargreaves/`

---

## 🖼️ Substituir as fotos do personagem

Para usar suas próprias fotos do personagem:

1. Renomeie sua foto **de corpo/ambiente** para `callahan_hero.jpg`
2. Renomeie sua foto **de retrato/close-up** para `callahan_profile.jpg`
3. Substitua os arquivos na pasta e faça novo upload no GitHub

As fotos aparecem automaticamente nas seções Hero e Perfil.

---

## ♟️ Xadrez multiplayer

O tabuleiro de xadrez usa conexão **P2P via PeerJS (WebRTC)** — sem servidor, funciona diretamente entre dois navegadores.

### Como usar:
1. **Jogador 1** acessa a página e clica em **CRIAR PARTIDA**
2. Um **código de sala** aparece na tela → copie e envie ao adversário
3. **Jogador 2** acessa a mesma página, cola o código e clica em **ENTRAR**
4. A conexão é estabelecida e o jogo começa automaticamente

> ⚠️ Ambos os jogadores precisam estar na página ao mesmo tempo.
> A conexão é direta (P2P) — nenhum dado fica armazenado em servidor.

---

## 🎨 Tecnologias usadas

- HTML5 + CSS3 puro (sem frameworks)
- [Google Fonts](https://fonts.google.com) — Oswald, Inter, IM Fell English
- [chessboard.js](https://chessboardjs.com) — renderização do tabuleiro
- [chess.js](https://github.com/jhlywa/chess.js) — validação de movimentos
- [PeerJS](https://peerjs.com) — conexão P2P em tempo real (WebRTC)
- [jQuery](https://jquery.com) — dependência do chessboard.js

Todos os assets externos são carregados via CDN gratuito.

---

*Universo expandido não oficial. Personagem criado para fins de roleplay.*
