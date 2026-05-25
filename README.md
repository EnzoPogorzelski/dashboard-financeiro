# Dashboard Financeiro Protegido

Este pacote contém uma versão estática do dashboard financeiro com tela de senha.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie os arquivos `index.html` e `.nojekyll`.
3. Vá em **Settings > Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/root`.
6. Abra o link publicado pelo GitHub Pages.

## Observação importante

O dashboard foi criptografado dentro do `index.html`. A senha não está escrita no arquivo.

Por ser um site estático, não existe login com servidor, usuários, recuperação de senha ou bloqueio por tentativas. Para proteção mais forte, use uma solução com autenticação real, como Cloudflare Access, Netlify/Vercel com autenticação, Firebase Auth ou uma aplicação com backend.
