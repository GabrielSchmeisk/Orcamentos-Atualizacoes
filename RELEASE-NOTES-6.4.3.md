# Orçamentos Simplificados 6.4.3

## Histórico

- O quadro de **Valor a receber** deixou de usar o retângulo rígido e recebeu cantos arredondados, alinhamento consistente e uma cápsula discreta para o valor.
- Novo filtro **Ordenar** no Histórico.
- **Últimos atualizados** é a ordem padrão e coloca primeiro os atendimentos alterados mais recentemente.
- A opção **Mais recentes** preserva a consulta pela data em que o orçamento foi criado.
- Empates de atualização usam a data de criação para manter uma ordem estável.
- O novo campo acompanha o layout responsivo e os filtros passam para uma segunda linha quando necessário.

## Validação

- 68 testes de regra e PDF aprovados.
- 48 testes de integração aprovados, incluindo a nova ordenação.
- Lint, builds web/desktop e auditoria de segurança aprovados.
- Interface conferida em uma janela intermediária sem estouro lateral dos filtros.

SHA-256 do instalador: `BAB642F4E7A43793E0D5C4B1823AB1086A549B86AB367DB2D03EE5B760D26310`
