# Orçamentos Simplificados 6.4.1

## Pagamentos e finalização

- Todo orçamento com status **Finalizado** representa pagamento concluído.
- Ao finalizar um atendimento, a data do pagamento é registrada automaticamente junto da retirada.
- Orçamentos finalizados antes desta atualização também aparecem como **Pagamento concluído**, mesmo sem a antiga marcação manual.
- Orçamentos cancelados ou rejeitados são tratados como pagamento não concluído e não preservam marcações antigas incompatíveis.
- A tela inicial deixou de apresentar pagamentos pendentes em Finalizações recentes.
- O cartão de atendimentos informa claramente que o pagamento é confirmado ao finalizar.

## Validação

- 68 testes de regra e PDF aprovados.
- 47 testes de integração aprovados.
- Lint, builds web/desktop e auditoria de segurança aprovados.

SHA-256 do instalador: `345883A369514BD024D53DB49C8B687941CC389CA4B9DA8AAE77743AC054879E`
