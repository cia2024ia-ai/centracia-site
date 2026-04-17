# Apk TV Streaming

Projeto estático pronto para publicação no GitHub Pages.

## Arquivos principais
- `index.html`: página única com:
  - login da área do cliente (senha `12345`)
  - login da área do desenvolvedor (senha `cia2024`)
  - lista fixa de apps editável no bloco `LISTA DE APPS PARA EDITAR`
- `CNAME`: domínio customizado já configurado (opcional para uso no seu repositório)

## Publicação rápida no GitHub Pages
1. Envie os arquivos para a branch `main` do seu repositório.
2. No GitHub, acesse **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione **Branch: main** e pasta **/(root)**.
5. Salve e aguarde o link do GitHub Pages ficar disponível.

## Como editar os apps
Abra `index.html` e edite o bloco JavaScript com o título:

`LISTA DE APPS PARA EDITAR`

Cada item possui:
- `nome`
- `descricao`
- `versao`
- `arquivoNome`
- `linkDownload`

Depois de editar, faça commit e push para publicar a atualização.
