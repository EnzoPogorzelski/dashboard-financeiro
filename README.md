# Dashboard Financeiro Editável

Esta versão foi feita para GitHub Pages e permite atualizar o dashboard sem editar código.

## Como publicar

Suba apenas estes arquivos no GitHub:

- `index.html`
- `.nojekyll`
- `README.md`

Depois ative o GitHub Pages em **Settings > Pages > Deploy from a branch > main > /root**.

## Como atualizar os dados

1. Abra o site publicado.
2. Digite a senha inicial: `Enzo@Financeiro2026`.
3. Vá em **Importar/Backup**.
4. Importe uma planilha `.xlsx` ou `.csv` com as colunas:
   - Mês
   - Tipo
   - Bloco
   - Categoria
   - Item
   - Valor
   - Observações
5. O dashboard será atualizado automaticamente.

## Importante

Não suba a planilha financeira preenchida em repositório público. Mantenha a planilha no seu computador e importe pelo site quando precisar atualizar.

Os dados importados ficam salvos no navegador usado para acessar o site, de forma criptografada com a senha de acesso. Em outro dispositivo, será necessário importar novamente ou usar um backup.
