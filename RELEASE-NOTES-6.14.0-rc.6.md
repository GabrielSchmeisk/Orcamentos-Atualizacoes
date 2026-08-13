# Orçamentos Simplificados 6.14.0-rc.6

## Atendimento e comunicação

- Orçamentos cancelados que ainda aguardam retirada exibem um aviso destacado de **serviço cancelado — não cobrar o cliente**.
- O valor é substituído visualmente por **NÃO COBRAR** nesse estado, sem alterar o histórico financeiro do registro.
- A mensagem enviada ao técnico em caso de cancelamento agora pode ser editada em Templates.
- Templates também passaram a reunir retirada após cancelamento, aparelho não retirado, peça encontrada, atualização de garantia e acesso ao painel técnico.
- A área de aparelhos abandonados ganhou notificação formal pronta para WhatsApp, com cliente, aparelho, tempo de espera e orientação sobre medidas legais cabíveis.

## Empresa e documentos

- Dados da empresa agora incluem site e horário de atendimento.
- Novos prefixos configuráveis para orçamento, garantia, venda e compra.
- Prazo padrão de validade dos novos orçamentos configurável entre 1 e 365 dias.
- Nova seção administrativa **Documentos**, separada dos templates de mensagens.
- Formas de pagamento, validade, aprovação, garantia, retirada, autorização de limpeza/formatação e rodapé dos PDFs podem ser editados pela administração.
- Site, horário e rodapé personalizado são reaproveitados nos documentos compatíveis.

## Navegação e segurança

- A tecla Espaço avança o tutorial e as etapas explicitamente marcadas como continuação, sem interferir na digitação em campos.
- O modo demonstração ficou visível e executável somente pela conta técnica protegida `admin`.
- Configurações antigas da empresa continuam válidas: os novos campos recebem padrões seguros durante a atualização.
- Prefixos personalizados são aplicados apenas a novos registros; documentos já existentes preservam sua numeração.

## Validação

- Compilação de produção, verificação TypeScript e auditoria de sintaxe concluídas.
- 107 testes unitários e 113 testes integrados aprovados.
- Migração, banco criptografado, backups, usuários, licenças, PDFs e atualização foram verificados contra regressões.

