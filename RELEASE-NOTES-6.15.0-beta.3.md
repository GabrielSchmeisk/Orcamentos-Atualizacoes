# Orçamentos Simplificados 6.15.0-beta.3

## Interface e navegação

- Corrige a largura das pesquisas de Clientes e da Central de Documentos.
- Reorganiza filtros de período no Histórico e campos do orçamento em janelas reduzidas.
- Corrige a navegação lateral no modo de tela dividida.
- Faz cada área abrir no início da página ao trocar de menu.
- Impede que notificações cubram tutoriais e caixas de diálogo.
- Padroniza foco, tecla Esc, bloqueio do fundo e navegação por teclado nos modais.
- Corrige a estrutura de acessibilidade das áreas Configurações e Administração.

## Desempenho e estabilidade

- Atualiza somente o orçamento alterado, evitando recarregar todo o banco a cada mudança.
- Reduz a frequência da atualização completa de segurança quando o aplicativo permanece aberto.
- Evita recarregar peças e garantias quando apenas um orçamento é alterado.
- Otimiza listas extensas para renderizar prioritariamente os registros visíveis.
- Remove uma dependência direta não utilizada e mantém módulos pesados carregados sob demanda.
- Evita repetir a varredura de expiração do banco em consultas realizadas no mesmo minuto.

## Validação

- Inclui verificações de regressão para pesquisas, responsividade, regiões de acessibilidade e leitura incremental do banco.
- Mantém banco, documentos, backups e configurações existentes durante a atualização.
