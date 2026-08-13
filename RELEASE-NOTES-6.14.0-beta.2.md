# Orçamentos Simplificados 6.14.0-beta.2

## Otimização do instalador

- Removida do pacote final a cópia completa e duplicada das dependências de desenvolvimento.
- O gerador de exportação contábil em PDF passou a ser empacotado em um módulo próprio, compacto e autossuficiente.
- Removidos do instalador arquivos públicos duplicados que não eram usados em tempo de execução.
- Mantidas todas as funcionalidades, documentos, banco local, painel técnico e compatibilidade com as instalações existentes.
- Preservadas as licenças de terceiros exigidas pelas bibliotecas distribuídas.

## Validação

- Compilação da interface e do aplicativo desktop.
- Testes automatizados do banco, licenciamento, backups, PDFs, atualizações e painel técnico.
- Verificação de segurança do pacote cliente.
- Teste de inicialização do aplicativo empacotado.
