# Santana Ar Condicionado — Site

Site institucional da Santana Ar Condicionado: climatização residencial e
comercial em Itapevi e região metropolitana de São Paulo.

## Estrutura

- `index.html` — estrutura da página (single page)
- `styles.css` — identidade visual (azul profundo + dourado + verde)
- `script.js` — interações, formulário de contato via WhatsApp e chat
  integrado ao backend [agente-santana-ar-condicionado](https://github.com/italodve/agente-santana-ar-condicionado)
- `SCRIPT-GOOGLE-FLOW.md` — prompt para gerar as fotos do site (Google Flow)

## Imagens

As 8 fotos geradas seguindo o `SCRIPT-GOOGLE-FLOW.md` já estão na raiz do
projeto (nomes exatos usados no `index.html`):

- `hero.jpg`
- `servico-instalacao.jpg`
- `servico-manutencao.jpg`
- `servico-reparos.jpg`
- `projeto-residencial.jpg`
- `projeto-comercial.jpg`
- `projeto-corporativo.jpg`
- `depoimento.jpg`

`logo.png` e `favicon.png` (assets reais da marca, fornecidos pelo cliente,
não gerados por IA) também já estão na raiz do projeto.

## Configuração antes do deploy

Em `script.js`, ajuste `AI_AGENT_BASE_URL` para a URL real do deploy do
backend `agente-santana-ar-condicionado` (Railway ou outro serviço).

## Deploy

Qualquer hospedagem de arquivos estáticos serve (GitHub Pages, Netlify,
Vercel, Railway). Não há build step — é HTML/CSS/JS puro.
