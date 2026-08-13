# Orçamentos Simplificados 6.14.0-rc.2

> Versão candidata à edição estável. A atualização preserva o banco, os backups, as configurações, os usuários e os documentos existentes.

## Histórico e persistência

- Corrigido o erro que fazia os registros do Histórico desaparecerem temporariamente após editar um orçamento ou contato.
- A atualização agora recarrega somente o domínio de dados alterado, sem substituir a lista de orçamentos por resultados de clientes, vendas ou aparelhos.
- Removido o filtro silencioso que podia permanecer aplicado depois de abrir um orçamento específico.
- Usuários, técnicos, vínculos e senhas locais permanecem gravados após fechar e reabrir o programa.
- Incluído teste automático que atualiza um contato, reabre o banco e confirma a permanência dos orçamentos no Histórico e na paginação.

## Garantias e interface

- A visualização da garantia foi separada do formulário de edição.
- Cartões abertos receberam melhor hierarquia para problema relatado, avaliação, decisão e evolução dos status.
- A edição em andamento não é mais apagada por atualizações automáticas.
- Garantias concluídas podem ser excluídas por administrador, com confirmação e registro da ação.
- A seleção de clientes agora rola suavemente até os dados do cliente escolhido.

## Orçamentos e comunicação

- A ação principal “Gerar PDF” foi substituída por “PDF + WhatsApp”.
- O aplicativo salva o orçamento, gera o documento e abre o envio ao número validado do cliente em um único fluxo.
- Os demais meios de envio e impressão foram preservados.

## Início e diagnóstico

- Faturamento e ticket médio principais passam a representar o mês atual.
- Erros da interface e do processo principal são registrados no diagnóstico interno com código de suporte.
- Telefone, CPF/CNPJ, e-mail, endereço, IMEI, senhas, tokens e conteúdo pessoal são removidos dos registros técnicos.

## Proteção do banco e backups

- O banco local completo passou a usar criptografia forte compatível com SQLCipher.
- A chave é protegida pelo Windows e vinculada ao usuário e ao computador.
- Bancos antigos em formato aberto são migrados automaticamente, com cópia de segurança para reversão em caso de falha.
- Backups próprios usam criptografia autenticada, verificação de integridade e chave de recuperação separada.
- Cópias alteradas, corrompidas ou abertas com outra chave são recusadas antes do uso.
- O componente nativo do banco é conferido por SHA-256 na inicialização para detectar alteração dos arquivos instalados.

## Licenciamento e pacote final

- A validação de licença permanece ofuscada seletivamente e separada do emissor.
- Mapas de código, testes, bancos, chaves, arquivos de desenvolvimento e implementação do emissor não acompanham o instalador.
- Corrigida a inclusão do componente nativo de banco no pacote final.
- O executável empacotado foi aberto em ambiente isolado e criou o banco criptografado corretamente.

## Validação

- 201 testes automatizados aprovados: interface, Histórico, banco, contas, garantias, backups, licenciamento, atualizações e painel técnico.
- Lint, builds web/desktop, auditoria de segurança do cliente e teste do executável empacotado aprovados.

## Integridade do instalador

- Arquivo: `Orcamentos-Simplificados-Setup-6.14.0-rc.2.exe`
- SHA-256: `a45acf43a465d3465cc428b0c8e083db8ccf76315649aa03851c1587e3be99d0`
- O mesmo valor está no arquivo `SHA256SUMS.txt` anexado à versão.
- Esta versão não possui certificado Authenticode comercial; o Windows pode exibir o SmartScreen.
