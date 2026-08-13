# Orçamentos Simplificados 6.14.0-rc.1

> Versão candidata à edição estável. O instalador preserva o banco, os backups, as configurações e os documentos existentes durante a atualização.

## Estabilidade e garantia

- Corrigido o formulário de conclusão de garantia para não perder textos durante atualizações automáticas.
- A conclusão da garantia agora grava os dados e o novo status em uma única operação.
- Quando outro computador ou painel altera a mesma garantia, a edição em andamento é preservada e o aplicativo informa o conflito antes de substituir os dados.
- Melhorada a atualização otimista da interface para evitar cartões temporariamente desatualizados.

## Clientes

- Adicionados filtros para clientes novos no mês, atendidos no mês, maiores faturamentos, maior quantidade de serviços, atendimentos ativos e clientes sem atendimento recente.
- Os filtros de faturamento e serviços ordenam os clientes pelos resultados do mês.
- Ao selecionar um cliente, a página retorna ao topo para apresentar imediatamente seus dados e ações.
- Mantidos os filtros de pessoas, empresas e arquivados.

## Interface e acessibilidade

- Padronizadas as barras de pesquisa de Histórico, Clientes, Garantias, Documentos, Vendas e Estoque.
- Corrigidos ícones desalinhados, contornos de foco duplicados e campos cortados em telas divididas.
- Reorganizados filtros do Histórico para se adaptarem automaticamente à largura disponível.
- Botões principais de venda e impressão receberam hierarquia visual consistente.
- Melhorados contraste, navegação por teclado, foco visível e suporte à preferência de redução de movimento.
- Revisadas as versões clara e escura em diferentes tamanhos de janela.

## Documentos e PDFs

- Comprovantes de compra e venda receberam identidade visual coerente e adequada à impressão em preto e branco.
- Reduzidas as áreas escuras dos comprovantes para economizar tinta.
- Corrigido o divisor do cabeçalho do comprovante de compra para não sobrepor a logomarca.
- A ficha de avaliação técnica ganhou divisões mais claras e linhas de preenchimento afastadas dos rótulos.

## Atualizações

- As notas exatas da versão instalada passam a aparecer uma vez após o primeiro login da atualização.
- O conteúdo é apresentado como texto seguro e inclui acesso opcional à página oficial da versão.

## Validação da versão

- Lint, build de produção e auditoria do pacote cliente executados.
- Suítes automatizadas de interface, banco de dados, backup, licenciamento, atualizações e painel técnico executadas.
- Fluxos responsivos verificados em telas estreitas, tela dividida e tema claro/escuro.
- PDFs de compra, venda e avaliação técnica renderizados e inspecionados visualmente.

## Integridade do instalador

- Arquivo: `Orcamentos-Simplificados-Setup-6.14.0-rc.1.exe`
- SHA-256: `d965d27b06fc9f588c05dfd36d432644b91a28c83b4d16aa6cd8853ffc74a096`
- O mesmo valor está disponível no arquivo `SHA256SUMS.txt` anexado a esta versão.
- Esta versão não possui certificado Authenticode comercial; o Windows pode exibir o SmartScreen.
