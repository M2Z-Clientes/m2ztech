# Protótipos M2Z Creative Tech

Protótipos navegáveis de UX/UI para apresentação a clientes, publicados pelo GitHub Pages.
Não são os sites oficiais dos clientes e não são indexados (robots.txt + meta noindex).

## Como publicar um novo protótipo
1. Crie uma pasta com o nome do cliente em minúsculas, sem acento (ex.: `nomedocliente/`).
2. Coloque o protótipo como `index.html` dentro da pasta (arquivo único, com imagens e fontes embutidas).
3. Faça commit e push na branch `main`. Em 1 a 2 minutos o link fica no ar:
   `https://<conta>.github.io/<repositório>/nomedocliente/`

## Configuração do GitHub Pages (uma vez)
Settings → Pages → Build and deployment → Source: *Deploy from a branch* → Branch: `main` / `(root)`.

## Domínio próprio (opcional)
Para usar, por exemplo, `prototipos.m2z.com.br`:
1. Crie um arquivo `CNAME` na raiz com o domínio.
2. No DNS da M2Z, crie um registro CNAME `prototipos` apontando para `<conta>.github.io`.
3. Em Settings → Pages, informe o domínio e ative "Enforce HTTPS".
