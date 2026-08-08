# Orçamentos Simplificados 6.6.1

## Garantias

- O sistema calcula o prazo a partir da data de entrega registrada no atendimento original.
- A garantia continua aceita até completar 90 dias; a partir do 91º dia, a solicitação é recusada automaticamente.
- A recusa automática informa quantos dias transcorreram e fica registrada no histórico da garantia.
- A mesma regra é validada pela interface e pelo banco local, evitando contorno manual.
- Garantias abertas dentro do prazo não são recusadas depois apenas porque a análise ou o reparo demorou.

## Comprovante de conclusão

- Novo documento profissional para garantias concluídas e cobertas.
- Registra cliente, aparelho, IMEI, número de série, retirada original, problema relatado, avaliação técnica, serviços realizados e peças substituídas.
- Inclui dados e logotipo da empresa, responsável pela conclusão e espaços para assinaturas.
- O PDF é salvo em `Documentos\Orçamentos\Garantias` e pode ser impresso diretamente pelo aplicativo.
- Layout revisado e validado visualmente em uma única página A4.

## Validação

- 138 testes automatizados aprovados.
- Compilação web e desktop concluída.
- Auditoria do pacote cliente aprovada, sem chaves privadas ou componentes do emissor.
- Instalador assinado com certificado autoassinado.

SHA-256: `C74847D9AE1C6B5C533B253E854A51ABD3D0A71896CAE5BE3138B1D307D46D3A`
