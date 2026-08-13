# Orçamentos Simplificados 6.14.0-beta.1

Versão beta de modernização visual, organização operacional e refinamento dos documentos.

## Principais novidades

- Página inicial reformulada com indicadores de operação, alertas e gráfico em barras de faturamento.
- Perfil do usuário no menu lateral com nome de exibição, foto local e troca da própria senha.
- Atalhos no topo para Documentos, Notificações e Ajuda.
- Configurações reorganizadas por seções, com acesso mais rápido a aparência, atualizações, rede, segurança e suporte.
- Central de backup modernizada com visão geral, backups disponíveis, transferência, saúde do sistema e histórico de operações.
- Clientes reformulados com métricas, filtros de pessoa/empresa/arquivados, detalhes, aparelhos, atendimentos e relacionamento.
- Central de aparelhos integrada para vendas, compras de usados, estoque e catálogo de imagens.
- Catálogo de aparelhos com alternativa segura para cadastrar uma imagem autorizada pela própria loja quando a pesquisa não localizar o modelo.
- Garantias mantidas na interface moderna, com pesquisa padronizada e remoção do componente visual antigo.

## Orçamentos, histórico e cancelamento

- Novo status **Aguardando técnico** para salvar serviços cujo valor ainda não foi retornado pelo técnico.
- Botão ao lado do preço aplica o status sem quebrar a validação dos demais campos obrigatórios.
- PDF, impressão, WhatsApp e avanço para aprovação ficam protegidos enquanto houver algum valor pendente.
- Após preencher todos os preços, o Histórico oferece **Enviar para aprovação** e mantém os próximos botões do fluxo já existente.
- Ficha compacta A5 para a bancada técnica, com cliente, contatos, aparelho, identificadores, acessórios, defeito relatado e espaço para diagnóstico, serviço, valor e prazo.
- A ficha fica salva em **Documentos > Fichas técnicas** e abre pronta para impressão.
- Novo fluxo ao cancelar um serviço: o sistema pergunta se o aparelho já foi retirado.
- Se o aparelho já foi retirado, o atendimento é encerrado diretamente como **Cancelado** e o comprovante é salvo.
- Se o aparelho ainda estiver na loja, permanece como **Pronto para retirada** com cancelamento pendente; ao registrar a retirada, muda automaticamente para **Cancelado**.
- A ação de cancelar também fica disponível durante a manutenção.
- O comprovante de retirada informa se o serviço foi concluído ou cancelado pelo cliente.
- Mensagem de WhatsApp específica para retirada de atendimento cancelado.

## PDFs e documentos

- Download restaurado nas ações que tradicionalmente baixavam o PDF, incluindo envio por WhatsApp + PDF.
- A mensagem de WhatsApp + PDF informa sempre o valor total do orçamento, inclusive para templates antigos.
- Cópias oficiais continuam organizadas na Central de documentos.
- Orçamento reorganizado: serviços e valores ficam antes; prazo, autorização e termos seguem na página posterior.
- Eliminada uma página quase vazia no orçamento padrão.
- Cabeçalhos, colunas, textos e comprovantes revisados visualmente em A4.
- Cartão de status, emissão, alteração e validade centralizado com quatro colunas de largura idêntica.

## Qualidade e segurança

- Migração do banco para a versão 21, preservando os dados existentes e adicionando foto de perfil.
- Perfil, usuários, técnicos, clientes, orçamentos e backups validados após reabertura do banco.
- Pacote do cliente auditado para impedir inclusão de chaves privadas ou rotinas do emissor de licenças.
- Testes de banco, licença, backup, PDF, histórico, painel técnico, atualizações, atalhos e regras comerciais aprovados.

## Observação

Esta é uma versão beta. Antes de instalar em uma máquina de produção, mantenha um backup recente do banco pela Central de Backup.
