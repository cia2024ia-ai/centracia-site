# CIA – Site one-page (GitHub Pages) – V4 PRO FINAL

Inclui:
- `index.html` (página principal)
- `assets/` (logos, favicon, background, OG image)
- `CNAME` (define domínio customizado centracia.com.br)
- `README.md` (instruções)

## Publicar no GitHub Pages
1. Suba todos os arquivos no repositório do GitHub (branch `main`).
2. Vá em Settings → Pages → Deploy from a branch → main → `/ (root)` → Save.
3. O GitHub já reconhecerá o domínio customizado a partir do arquivo `CNAME`.

## Configuração de DNS para centracia.com.br
No provedor de domínio (ex.: Registro.br), configure:

- **CNAME**
  - Nome: `www`
  - Valor: `SEU_USUARIO.github.io`

- **A records** (para o domínio raiz funcionar sem www):
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153

Após salvar, aguarde até 30 minutos para propagação do DNS.

Acesse: https://centracia.com.br
