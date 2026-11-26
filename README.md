# KAIROS Social Desk | Política de Privacidade

Repositório público exclusivo para a página de política de privacidade do KAIROS Social Desk.

## Publicação

A página principal está em `index.html`. O GitHub Pages deve ser configurado para publicar a partir da branch `main`, pasta `/ (root)`.

URL esperada após ativar o Pages:
https://kairozgames-svg.github.io/kairos-socialdesk-privacy/

## Pendências obrigatórias antes de enviar para análise da Meta

- [ ] Substituir `[INSERIR NOME COMPLETO OU RAZÃO SOCIAL]` pelo responsável legal pelo aplicativo.
- [ ] Substituir `[INSERIR E-MAIL OFICIAL DE CONTATO]` por um e-mail real e monitorado.
- [ ] Confirmar que as descrições de dados, armazenamento, retenção e exclusão correspondem à versão efetivamente publicada do aplicativo.
- [ ] Quando mensagens e comentários passarem a ser processados/armazenados, revisar as seções 2, 5, 6 e 7.
- [ ] Implementar e testar um fluxo de solicitação de exclusão de dados compatível com os requisitos aplicáveis da Meta, se exigido para os produtos/permissões utilizados.

## Observação de precisão

A auditoria de 25/11/2026 disponível no projeto indicava que o gateway recebia webhooks, validava a assinatura e reconhecia JSON válido, mas ainda não processava nem armazenava mensagens e comentários. A página registra esse estado para não afirmar que uma funcionalidade já está operacional quando ainda está em desenvolvimento.
