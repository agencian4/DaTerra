# DaTerra Paisagismo · protótipos de aprovação

Duas versões do site, desenvolvidas pela Agência N4:

- `v1/`: Versão 1, com hero em foto de tela cheia
- `v2/`: Versão 2 ("Trópico Construído")
- `index.html`: página simples para escolher entre as duas (útil se publicar a raiz)

Cada pasta é um site estático completo (HTML, imagens e fontes locais), sem build.

## Vercel
1. Suba esta pasta inteira para um repositório no GitHub.
2. Na Vercel: **Add New → Project** e importe o repositório.
3. **Framework Preset:** Other. **Build Command:** vazio. **Output Directory:** vazio.
4. **Root Directory:** `v1` ou `v2`, conforme a versão que quiser publicar.
   Para ter as duas no ar, crie dois projetos na Vercel apontando para o mesmo repositório, um com `v1` e outro com `v2`.
   Se deixar a raiz (`./`), a Vercel publica a página de escolha, com as duas versões em `/v1/` e `/v2/`.

## Antes de ir para produção
- Remover `<meta name="robots" content="noindex, nofollow">` do `index.html` da versão escolhida.
- Confirmar com a DaTerra: autorização dos logos e depoimentos de clientes, locais dos projetos, WhatsApp, telefone, e-mail, horário e CNPJ.
