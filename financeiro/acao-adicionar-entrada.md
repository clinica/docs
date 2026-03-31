# Ação: adicionar entrada

## Cenário real
O paciente pagou (PIX, cartão, dinheiro) ou entrou um repasse, e você precisa registrar para não “sumir” no fechamento.

## Objetivo
Registrar uma entrada no período correto, com informação suficiente para conferir depois.

## Quando usar
- Quando um paciente paga um atendimento.
- Quando a clínica recebe um repasse/entrada diversa.

## Quando NÃO usar
- Quando o valor ainda não entrou de verdade (só promessa): espere confirmar para não bagunçar o caixa.

## Passo a passo detalhado
1. Acesse **Financeiro**.
2. Clique em **Adicionar entrada** (botão com ícone “+”).
3. No diálogo de lançamento:
   1. Preencha os campos solicitados (ex.: valor, data, descrição, paciente quando aplicável).
   2. Confirme para salvar.
4. Verifique se a entrada aparece no histórico do período.
5. **Checkpoint**: ao filtrar o dia, a entrada aparece com valor e descrição corretos.

## Campos envolvidos
O diálogo é controlado por um contexto (`CTXCashflowDialogController`) e pode exibir campos conforme configuração:
- **Paciente**: normalmente habilitado para entrada (`paciente: true`)
- **Data**: habilitado (`data: true`)
- Outros campos dependem do formulário interno de movimentação (não visível diretamente nesta rota).

## Regras do trabalho (para fechar sem dor)
- Sempre preencha descrição clara (ex.: “Consulta 31/03”, “Retorno”, “Repasse convênio”).
- Se houver paciente relacionado, vincule — facilita encontrar depois.

## Possíveis erros e como resolver
- **Diálogo não abre**:
  - Solução: recarregue e tente novamente; se persistir, pode haver erro de UI.
- **Não salva**:
  - Solução: revise campos obrigatórios e tente de novo.

## Resultado esperado
Uma nova entrada fica registrada e passa a compor resumos e totais do período selecionado.

## Observações importantes
- Em estados vazios (sem movimentações), a tela também oferece um atalho para adicionar entrada.

## Apêndice técnico (para suporte)
- Ao abrir, o sistema define o tipo inicial como entrada (`IN`) e pode mostrar/ocultar campos conforme configuração.
