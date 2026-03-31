# Ação: remover item do estoque

## Cenário real
Um item foi cadastrado errado (nome duplicado, item que a clínica não usa) e está poluindo a lista. Você quer remover para a equipe não lançar no lugar errado.

## Objetivo
Remover (ou inativar/arquivar, quando for a regra) um item que não deve mais ser usado na operação.

## Quando usar
- Quando um item foi cadastrado indevidamente.
- Quando um item não será mais utilizado e a clínica deseja removê-lo do catálogo.

## Quando NÃO usar
- Se o item tem histórico importante que a clínica precisa manter. Nesse caso, avalie se existe opção de arquivar/inativar.

## Passo a passo detalhado
1. Abra o item em **Estoque → Itens do estoque**.
2. Role até o final da página (quando necessário).
3. Use a ação de **remover** (diálogo) e confirme.
4. **Checkpoint**: o item não aparece mais na lista (ou aparece como inativo, se for o caso).

## Campos envolvidos
Geralmente apenas confirmação:
- Confirmação de remoção (diálogo)

## Regras do trabalho (para não perder rastreabilidade)
- Se existir lote/uso/histórico, pode não ser possível remover. Isso é bom para auditoria.
- Antes de remover, confirme com a gestão se pode “sumir” da operação.

## Possíveis erros e como resolver
- **Não consigo remover**:
  - Pode ser restrição por uso/histórico.
  - Solução: verifique se há lotes/uso recente; considere desativar/arquivar (se existir no produto).
- **Erro ao remover**:
  - Solução: tente novamente; se persistir, contate suporte.

## Resultado esperado
O item deixa de aparecer na lista (ou fica arquivado/inativo, conforme regra adotada).

## Observações importantes
- Antes de remover, confirme com a equipe se há necessidade de manter histórico para auditoria.

## Apêndice técnico (para suporte)
- A remoção pode ser bloqueada por vínculos com lotes e histórico.
