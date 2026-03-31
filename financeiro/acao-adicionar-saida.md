# Ação: adicionar saída

## Cenário real
Você pagou uma despesa (fornecedor, material, aluguel, taxa) e precisa registrar para o fechamento bater.

## Objetivo
Registrar uma saída no período correto, com categoria/descrição que permita entender depois para onde o dinheiro foi.

## Quando usar
- Quando a clínica paga um fornecedor.
- Quando registra uma despesa operacional.

## Quando NÃO usar
- Quando o pagamento ainda não aconteceu (só orçamento). Registre quando houver saída real.

## Passo a passo detalhado
1. Acesse **Financeiro**.
2. Clique em **Adicionar saída** (botão com ícone “–”).
3. No diálogo de lançamento:
   1. Preencha os campos solicitados (ex.: valor, data, descrição, categoria).
   2. Confirme para salvar.
4. Verifique se a saída aparece no histórico do período.
5. **Checkpoint**: a saída aparece no dia correto e entra no total do período.

## Campos envolvidos
O diálogo é controlado por um contexto (`CTXCashflowDialogController`) e pode exibir campos conforme configuração:
- **Paciente**: normalmente desabilitado para saída (`paciente: false`)
- **Data**: habilitado (`data: true`)
- Outros campos dependem do formulário interno de movimentação.

## Regras do trabalho (para facilitar auditoria)
- Use categorias consistentes (ex.: “Material”, “Impostos”, “Serviços”, “Aluguel”).
- Descrição clara evita retrabalho na hora do fechamento.

## Possíveis erros e como resolver
- **Diálogo não abre**:
  - Solução: recarregue e tente novamente.
- **Não salva**:
  - Solução: revise campos obrigatórios e tente novamente.

## Resultado esperado
Uma nova saída fica registrada e passa a compor resumos e totais do período selecionado.

## Observações importantes
- Em estados vazios (sem movimentações), a tela também oferece um atalho para adicionar saída.

## Apêndice técnico (para suporte)
- Ao abrir, o sistema define o tipo inicial como saída (`OUT`) e pode ocultar o campo de paciente.
