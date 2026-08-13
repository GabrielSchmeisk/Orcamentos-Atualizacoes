# Orçamentos Simplificados 6.14.0-beta.3

> Versão beta para validação antes da próxima edição estável. O instalador preserva o banco, os backups e os documentos existentes durante a atualização.

## Backup e segurança dos dados

- A Central de Backup agora mostra o caminho completo onde os backups são armazenados.
- Adicionados botões para abrir a pasta de backups e escolher um novo local.
- O novo local é validado antes de ser salvo e permanece configurado após reiniciar o aplicativo.
- Ao trocar a pasta, os backups SQLite e seus arquivos de metadados são copiados com segurança; os originais não são apagados.
- Backups automáticos, de fechamento, atualização e proteção passam a respeitar o local configurado.

## Início e indicadores comerciais

- Os filtros de período foram movidos para junto do gráfico que eles controlam.
- Adicionado comparativo com o período anterior, com diferença absoluta e percentual.
- Melhorada a leitura do faturamento por período e a responsividade do gráfico.

## Interface e legibilidade

- Corrigida a posição vertical da área de clientes.
- Padronizado o campo de técnico responsável com os demais campos do orçamento.
- Corrigido o contorno duplicado de foco nas pesquisas de Clientes, Garantias e outros campos compostos equivalentes.
- Removida a navegação lateral redundante da tela de Configurações, aproveitando melhor a largura disponível.
- Traduzidas para português as principais atividades e ações exibidas na administração.

## PDFs

- Corrigidas as divisões e os espaçamentos da ficha A5 de avaliação técnica.
- Eliminadas sobreposições entre cartões de informação e títulos de seção.
- Reorganizado o conteúdo para preservar cliente, aparelho, problema informado e retorno técnico em uma única ficha.

## Instalador e desempenho

- O código auxiliar da exportação contábil passou a ser empacotado de forma otimizada.
- Removidos do pacote arquivos de desenvolvimento e dependências que não precisam acompanhar o aplicativo instalado.
- Mantidas as opções de desinstalação para remover somente o programa ou também os dados locais.
- Incluído `SHA256SUMS.txt` para conferir a integridade do instalador.
- Esta versão beta não possui certificado Authenticode comercial; o Windows pode exibir o SmartScreen. Confira o arquivo pelo SHA-256 publicado junto da versão.

## Validação

- Compilação da interface e do aplicativo desktop concluída.
- Suítes automatizadas do banco, regras de negócio e interface executadas.
- Inicialização do pacote desktop e fluxo de login verificados.
- PDF técnico renderizado e inspecionado visualmente.

## Integridade do instalador

- Arquivo: `Orcamentos-Simplificados-Setup-6.14.0-beta.3.exe`
- SHA-256: `18ced7489b8418dbe36b5dfcd0ff7e724703526fb109eb7d092e2a95a1df3ebc`
