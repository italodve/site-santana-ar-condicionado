# Santana Ar Condicionado — Site

Site institucional da Santana Ar Condicionado: climatização residencial e
comercial em Itapevi e região metropolitana de São Paulo.

## Estrutura

- `index.html` — estrutura da página (single page)
- `styles.css` — identidade visual (azul profundo + dourado + verde)
- `script.js` — interações, formulário de contato via WhatsApp e chat
  integrado ao backend [agente-santana-ar-condicionado](https://github.com/italodve/agente-santana-ar-condicionado)
- `SCRIPT-GOOGLE-FLOW.md` — prompt para gerar as fotos do site (Google Flow)

## Imagens pendentes

As imagens abaixo ainda precisam ser geradas/adicionadas na raiz do projeto
(nomes exatos usados no `index.html`):

- `logo.png` — logo real da marca (asset fornecido pelo cliente, não gerado por IA)
- `favicon.png` — recorte quadrado do logo
- `hero.jpg`
- `servico-instalacao.jpg`
- `servico-manutencao.jpg`
- `servico-reparos.jpg`
- `projeto-residencial.jpg`
- `projeto-comercial.jpg`
- `projeto-corporativo.jpg`
- `depoimento.jpg`

As 8 fotos (exceto logo/favicon) devem ser geradas seguindo exatamente o
`SCRIPT-GOOGLE-FLOW.md` deste repositório, para manter a mesma identidade
visual em todas.

## Configuração antes do deploy

Em `script.js`, ajuste `AI_AGENT_BASE_URL` para a URL real do deploy do
backend `agente-santana-ar-condicionado` (Railway ou outro serviço).

## Deploy

Qualquer hospedagem de arquivos estáticos serve (GitHub Pages, Netlify,
Vercel, Railway). Não há build step — é HTML/CSS/JS puro.
