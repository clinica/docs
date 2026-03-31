# Ação: gerenciar lotes de um item

## Cenário real
Chegou reposição de um material, você fez inventário e precisa ajustar saldo, ou percebeu que um lote está próximo de vencer. Lote bem cuidado evita falta e desperdício.

## Objetivo
Manter lotes, validade e saldo do item atualizados para a operação clínica não parar.

## Quando usar
- Quando chega uma nova remessa (novo lote).
- Quando precisa corrigir saldo por ajuste/inventário.
- Quando precisa atualizar validade informada incorretamente.

## Quando NÃO usar
- Para cadastrar um item novo (sem existir no estoque). Primeiro crie o item, depois os lotes.

## Passo a passo detalhado
1. Acesse **Estoque** e abra um item específico.
2. Na seção **Lotes**:
   1. Clique em **Adicionar lote** e preencha os dados solicitados.
   2. Em um lote existente:
      - Use as ações de quantidade para ajustar saldo.
      - Use a ação de validade para ajustar a data.
      - Abra “Mais opções” para ver histórico e outras ações (quando disponível).
3. Confirme que o lote aparece/atualiza com os novos dados.
4. **Checkpoint**: saldo e validade do lote refletem a realidade do estoque.

## Campos envolvidos
Variam por diálogo/ação, mas tipicamente incluem:
- Nome do lote
- Quantidade
- Preço/custo
- Data de validade

## Regras do trabalho (o que evita desperdício)
- Use o lote/validade para priorizar consumo do que vence antes.
- Ajuste saldo sempre que fizer inventário (evita “tem no sistema, mas não tem na prateleira”).

## Possíveis erros e como resolver
- **Ações não aplicam**:
  - Solução: recarregue a página e tente novamente.
- **Erro ao atualizar validade/quantidade**:
  - Solução: revise valores e tente novamente; se persistir, contate suporte.

## Resultado esperado
Os lotes ficam atualizados e refletem com precisão validade e saldo disponível do item.

## Observações importantes
- O módulo costuma exibir forma do item e preço do lote, ajudando a operação a tomar decisões.

## Apêndice técnico (para suporte)
- A UI pode permitir ver histórico e ações adicionais por lote via “mais opções”.
