# Orçamentos Simplificados 6.13.0-beta.1

Versão beta para validação da nova organização visual e do catálogo local de aparelhos. O banco anterior é migrado automaticamente e permanece compatível.

## Nova navegação

- Menu principal reorganizado em **Operação**, **Negócio** e **Gestão**.
- Botão **Novo orçamento** mantido em destaque.
- Perfil conectado, tipo de acesso e saída reunidos no rodapé do menu.
- **Aparelhos** agora é uma central única, sem menus duplicados na barra lateral.
- Documentos, notificações, ajuda e demais recursos existentes foram preservados.

## Início mais completo

- Indicadores de faturamento, ticket médio, tempo médio, atendimentos ativos, estoque e garantias.
- Bloco **Precisam de atenção agora** com acesso direto aos registros.
- Resumo operacional de orçamentos, aparelhos, peças e garantias.
- Funil comercial, evolução do faturamento e serviços que mais faturam.
- Ranking de desempenho dos técnicos quando houver técnico vinculado aos atendimentos.
- Comparação das vendas de aparelhos com o mês anterior.

## Central de aparelhos

- Visão geral com estoque disponível, aparelhos em análise, vendas do mês e faturamento.
- Compras de usados, estoque e vendas continuam usando as mesmas regras e documentos existentes.
- Movimentações recentes de compra e venda reunidas em ordem cronológica.
- Avisos para aparelhos que precisam de análise ou definição de preço.

## Catálogo seguro de imagens

- Pesquisa opcional por marca, modelo e código do aparelho usando o Openverse.
- Somente resultados com licenças abertas compatíveis são exibidos.
- Nenhuma imagem é escolhida ou salva automaticamente.
- Confirmação explícita mostra imagem, fonte, autor e licença antes do cadastro.
- A miniatura confirmada fica no banco local para uso offline e acompanha os backups do banco.
- Ausência de imagem mantém o ícone padrão, sem bloquear compras, estoque ou vendas.

> A informação de licença é fornecida pelos provedores do Openverse. O usuário deve conferir a página da fonte antes de confirmar o uso.

## Administração

- Seções administrativas reorganizadas em uma navegação lateral lógica.
- Grupos de empresa/equipe e sistema/segurança separados visualmente.
- Visão geral ganhou atividade recente e pontos de atenção.
- Usuários, técnicos, templates, dados da empresa, licença, logs, relatórios, erros e registros foram preservados.

## Segurança e dados

- Banco atualizado para a estrutura 20 com migração atômica.
- Catálogo local registra fonte, autor, licença, usuário responsável e data de confirmação.
- Download de imagem limitado a HTTPS, tipos permitidos e tamanho máximo.
- Pesquisa remota usa identificadores temporários para impedir que a interface solicite URLs arbitrárias ao processo principal.
- Código-fonte não é publicado no repositório de atualizações.

## Validação

- Compilação web e desktop validada.
- Lint e verificação TypeScript concluídos.
- Testes de banco, usuários, licenças, backups, PDFs, histórico, atalhos e atualizações executados.
- Interface principal revisada nos modos claro e escuro e em larguras responsivas.
