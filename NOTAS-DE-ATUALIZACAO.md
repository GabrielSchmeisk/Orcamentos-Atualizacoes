# Notas de atualização — Orçamentos Simplificados

Este documento registra a linha moderna e multiempresa do aplicativo, iniciada na versão 4.0.0. As versões anteriores pertencem à edição legada personalizada para uma única empresa e não fazem parte deste canal de atualização.

## 6.2.0 — versão atual

### Destaques

- Painel inicial com faturamento de atendimentos finalizados nos períodos de 1, 6 e 12 meses, ticket médio, serviços com maior faturamento e duração das manutenções.
- Área **Peças** reorganizada em Procurando, Cliente avisado e Finalizados, com prioridade Urgência, avanço rápido, resultado Vendida/Cliente desistiu, datas e exclusão confirmada.
- Histórico dividido entre ativos e encerrados, com valor em evidência, modo compacto e ações coloridas para manutenção, retirada, PDF e WhatsApp em texto.
- Retirada registra quem levou o aparelho; o nome passa a constar no comprovante.
- CPF/CNPJ é identificado automaticamente no orçamento, com filtro específico para empresas em Clientes.

### Documentos e licenciamento

- Logotipo cadastrado é lido diretamente do banco e aparece nos PDFs.
- Documentos voltaram ao padrão azul-petróleo de alto contraste.
- Comprovante inclui a exigência de apresentação para garantia.
- A versão mais recente de cada orçamento e comprovante é salva automaticamente em `Documentos\Orçamentos`.
- Rodapé discreto **Deus seja louvado** incluído nos dois documentos.
- Administrador técnico pode cancelar localmente a licença para testes; o arquivo revogado não pode ser reutilizado e uma nova ativação exige outra licença.

SHA-256: `1C6182BCB454210EE1A553E9DAE50080BCA32E26A0560F85BEC3C9845EE44022`

## 6.1.0

- Alteração de status sem congelar a interface e sem bloquear a edição dos campos.
- Novos serviços rápidos: Formatação, Remoção de vírus, Transferência de arquivos e Transferência de dados entre aparelhos.
- Prazo estimado automático e modelo especial para iPhones nunca abertos.
- Logotipo personalizado corrigido nos dois PDFs.
- Histórico reorganizado entre ativos e encerrados, com modo compacto, dias recolhíveis e controle de pagamento.
- Nova tela de peças procuradas com cliente, aparelho, fornecedor, observações e lembrete a cada sete dias.
- Backup oculto e bloqueado para operadores; cópia automática e silenciosa ao fechar nesse perfil.
- Edição de orçamento preserva o aparelho existente e evita duplicações.
- Logs administrativos com nomes compreensíveis, sem registros de entrada e saída da conta.
- Senhas com mínimo de quatro caracteres.
- Licença instalada criptografada pelo cofre do Windows, assinada e vinculada à máquina.
- Central de Ajuda e tutoriais atualizados.

SHA-256: `D357FBB7FBB4E51C3493E9CEDAF238E4B2F0D2AFD04960601393238A1EC3C485`

## 6.0.2

- Campos marcados com asterisco impedem salvar ou gerar PDF quando estão vazios ou inválidos.
- Resumo dos campos pendentes e foco automático no primeiro campo que precisa de atenção.
- Contraste reforçado nas telas administrativas do modo claro.
- Campos, seletores e botões administrativos passam a respeitar corretamente o tema escolhido.
- Correções de alinhamento em valores monetários, buscas, modelos de mensagem, abas administrativas e comprovante de retirada.

SHA-256: `210BD57D48C622377B492C9374D05038E5E9956219CB74AD08C697A004A99CFA`

## 6.0.1

Versão intermediária de manutenção produzida durante a revisão visual da linha 6.0. Ela recebeu ajustes iniciais de contraste, campos administrativos e validação do formulário, mas foi substituída pela 6.0.2, que consolidou essas correções. Para uso normal, instale a versão mais recente.

SHA-256: `16DD6098EC1E6E59B0DC468B98DC7A054EC8AC3E72FD4A2D954501FB2594BD0A`

## 6.0.0

- Novo nome oficial: **Orçamentos Simplificados** e título dinâmico com o nome da empresa.
- Central de Backup reorganizada com histórico, transferência, diagnóstico e manutenção.
- Personalização da cor principal com 12 opções profissionais e HEX personalizado.
- Códigos rastreáveis de erro e painel técnico de diagnóstico.
- Nome da empresa editável durante a emissão da licença.
- Melhor contraste no modo claro, refinamentos responsivos e logotipos sem recorte.
- Orçamentos cancelados permanecem visíveis.
- Correção de logos PNG, JPEG e WebP nos PDFs e de quebras em documentos longos.
- Administradores da loja não podem criar, visualizar ou alterar contas técnicas.
- Logs removem senhas, tokens e outros segredos antes do armazenamento.
- Dados comerciais, CNPJ, contatos, endereço, logo e cor atualizam a interface e os dois PDFs.

SHA-256: `655D0BEFAF09800BF6F2BA093A6EB6984E7B5072B62EC86AB74AB8AD3D20CC59`

## 5.0.0

- Cadastro persistente de clientes, pesquisa, detalhes, arquivamento, aparelhos, histórico e interações.
- Telefones, WhatsApp, preferências, ofertas, endereço, interesses, etiquetas e observações.
- Proteção contra clientes e aparelhos duplicados.
- Relação de vários aparelhos por cliente, com capacidade, IMEI e número de série.
- Perfis de usuário, senha temporária e verificações explícitas de permissão.
- Expiração automática de orçamento e correção administrativa controlada.
- Alertas de licença em 30, 15, 7, 3, 1 e 0 dias.
- Logs com filtros, estatísticas, exportação e limpeza auditada.
- Comprovante completo com loja, cliente, aparelho, serviços e valores.
- Central única de backup, restauração, histórico e transferência com verificação SHA-256.
- Melhorias de temas, botões, tutorial, responsividade, índices SQLite e manutenção do banco.

SHA-256: `9D4B5A8987263BB2436138E90AAE05797365B24A5FDE305393FFAC35001727F5`

## 4.0.0

- Nova identidade **Orçamentos**, sem marca de loja fixa.
- Ícone padrão neutro e identidade interna baseada no logotipo da empresa.
- Dados empresariais editáveis: nome, subtítulo, razão social, CNPJ, contatos, endereço, e-mail e logotipo.
- Orçamento e comprovante de retirada usam os dados empresariais configurados.
- Armazenamento, protocolo e licenciamento isolados da linha anterior.
- Canal automático de atualização direcionado a este repositório.

Esta versão iniciou uma nova identidade e uma nova chave de licenciamento. Dados das edições legadas não são importados automaticamente.

SHA-256: `5EEAD81C76F50A4150185EC5D2A3E0287B8059A049CFBF910F6219A1DE7C6EBC`

## Observação de segurança

Os instaladores ainda não possuem certificado comercial de assinatura digital. O Windows SmartScreen pode exibir um aviso. Baixe os arquivos somente da página oficial de Releases deste repositório.
