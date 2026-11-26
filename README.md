# KAIROS Social Desk | Política de Privacidade

Repositório público exclusivo para a página de política de privacidade do KAIROS Social Desk.

## Publicação

A página principal está em `index.html`. O GitHub Pages deve ser configurado para publicar a partir da branch `main`, pasta `/` (root).

URL esperada após ativar o Pages:
https://kairozgames-svg.github.io/kairos-socialdesk-privacy/

## Checklist de pendências (antes da análise da Meta)

- [ ] Substituir `[INSERIR NOME COMPLETO OU RAZÃO SOCIAL]` pelo nome legal/responsável pelo aplicativo.
- [ ] Substituir `[INSERIR E-MAIL OFICIAL]` por um e-mail real e monitorado para privacidade.
- [ ] Confirmar que as descrições de dados, armazenamento, retenção e exclusão correspondem à versão efetivamente publicada do aplicativo.
- [ ] Quando mensagens e comentários passarem a ser processados/armazenados, revisar as seções 2, 4, 5 e 7 da política.
- [ ] Implementar e testar um fluxo de solicitação de exclusão de dados compatível com os requisitos aplicáveis da Meta.

## Instruções para ativar GitHub Pages

1. Acesse **Settings** (Configurações) do repositório.
2. No menu lateral, clique em **Pages** (páginas).
3. Em **Source**, selecione **Deploy from a branch**.
4. Na branch, escolha **main**.
5. Na pasta, escolha **/(root)**.
6. Clique em **Save** (Salvar).

Após alguns minutos, a página estará disponível em:
**https://kairozgames-svg.github.io/kairos-socialdesk-privacy/**

## Observação de precisão

A auditoria de 25/11/2026 disponível no projeto indicava que o gateway recebia webhooks, validava a assinatura e reconhecia JSON válido, mas ainda não processava nem armazenava mensagens e comentários. Esta informação está refletida na seção 4 da política de privacidade (`index.html`).
