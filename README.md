# deckcorp.com.br

Site de apresentação da DeckCorp. **Estático**: só HTML/CSS, sem login, sem banco, sem servidor próprio.
Hospedado no GitHub Pages, **sem nenhum vínculo** com o painel, a VM Oracle ou outros sistemas.

- `index.html`: página única (versão "C · Editorial" aprovada em 24/09/2026)
- `404.html`, `favicon.svg`, `og.png` (prévia ao compartilhar o link), `robots.txt`, `sitemap.xml`, `CNAME`
- Número do WhatsApp: variável `WHATSAPP` no fim do `index.html` (vazio = botão escondido)
- Segurança: CSP no `<meta>` bloqueia qualquer conexão do navegador pra fora (`connect-src 'none'`), formulários e iframes.

Rodar local: `python3 -m http.server 8080` e abrir http://localhost:8080
