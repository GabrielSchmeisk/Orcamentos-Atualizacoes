# Orçamentos Simplificados 6.14.0-rc.5

## Melhorias

- Ficha de avaliação técnica reorganizada para caber em uma única folha A5, mantendo os campos legíveis.
- Senha numérica e padrão de desbloqueio integrados ao visual do formulário e exibidos nos detalhes internos do orçamento.
- Histórico preserva o modo compacto e abre somente o orçamento recém-criado ou atualizado.
- Campos numéricos não são mais alterados acidentalmente pela roda do mouse.
- Orçamentos aguardando técnico avançam automaticamente para aguardando aprovação quando todos os valores são preenchidos.
- O botão de aprovação abre a edição quando ainda existem valores pendentes.
- Foco visual das caixas de seleção corrigido.
- Central de Backup ganhou limpeza segura de cópias automáticas antigas.
- Cadastro de técnicos agora aceita WhatsApp e aviso opcional de cancelamento.
- Central de documentos reindexa ao abrir, atualiza PDFs substituídos e remove referências de arquivos que já não existem.

## Segurança e compatibilidade

- Migração aditiva do cadastro de técnicos, preservando os registros existentes.
- A limpeza de backups preserva cópias manuais, o backup mais recente e as recuperações novas.
- Substituição de documentos passou a usar troca atômica com restauração do arquivo anterior em caso de falha.
