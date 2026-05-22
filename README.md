# 🎮 Hash Mining - Web Version

Um jogo de mineração de criptomoedas com integração de anúncios MONETAG para monetização.

## 🚀 Como Usar

### Versão Web (Este repositório)
- Acesse: https://hash-mining-web.vercel.app
- Jogue diretamente no navegador
- Sem necessidade de Telegram

### Integração MONETAG
1. Crie uma conta em https://monetag.com
2. Gere um Zone ID
3. Abra `index.html` em um editor
4. Procure por `<!-- MONETAG SDK`
5. Descomente e adicione seu Zone ID:
```html
<script src="https://alb.ptchn.com/sdk/sdk.js" data-zone="SEU_ZONE_ID" data-sdk="show_SEU_ZONE_ID"></script>
```

## 📊 Funcionalidades

- ⛏ Mineração de criptomoedas
- 🤖 Máquinas de mineração (7 níveis)
- 💎 Sistema de diamantes
- 📺 Anúncios MONETAG para ganhos
- 🏆 Tarefas diárias
- 👥 Sistema de referência
- 💰 Carteira e estatísticas

## 🔧 Desenvolvimento Local

```bash
npm run dev
# Ou
python3 -m http.server 3000
```

Acesse: http://localhost:3000

## 📝 Licença

MIT
