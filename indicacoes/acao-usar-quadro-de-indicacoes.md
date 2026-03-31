# Ação: usar quadro de indicações (Kanban)

## Cenário real
Você quer uma visão rápida do funil e precisa mover vários indicados de status sem abrir um por um, como se fosse um “quadro de tarefas”.

## Objetivo
Operar o funil de indicações de forma visual, deixando claro em que etapa cada indicado está.

## Quando usar
- Quando a equipe quer operar o funil visualmente (pipeline).
- Quando precisa atualizar status de muitas indicações rapidamente.

## Quando NÃO usar
- Se você precisa atualizar dados detalhados (telefone, observação longa). Nesse caso, use a lista de indicados.

## Passo a passo detalhado
1. Acesse **Indicações → Quadro**.
2. Localize o card do indicado.
3. Arraste o card para a coluna correspondente ao novo status:
   - Aguardando contato
   - Entrado em contato
   - Virou paciente
   - Descartado
4. (Opcional) Use o menu do card (⋯) para:
   - Editar
   - Converter para paciente (quando disponível)
   - Remover
5. **Checkpoint**: o card fica na coluna correta e o status foi salvo.

## Campos envolvidos
Não há formulário principal; as mudanças ocorrem por:
- Drag-and-drop de cards
- Menu de ações do card

## Regras de negócio
- Ao soltar o card em outra coluna:
  - O sistema tenta salvar o novo status.
  - A UI faz atualização otimista (mostra o card na coluna nova).
  - Em caso de erro, o estado anterior é restaurado.
- Mensagens:
  - Sucesso: “Status atualizado”
  - Erro: mensagem do backend (quando disponível) ou “Erro ao atualizar status”
- “Converter para paciente” só aparece quando o indicado ainda não virou paciente.

## Possíveis erros e como resolver
- **Erro ao atualizar status**:
  - Solução: tente arrastar novamente; se persistir, recarregue a página.
- **Arrastar não funciona**:
  - Pode ser por interação (distância mínima para iniciar arrasto).
  - Solução: clique e arraste com um pequeno movimento.

## Resultado esperado
O status do indicado muda e o card passa a aparecer na coluna correta, refletindo o estágio atual do funil.

## Observações importantes
- A lista dentro de cada coluna é virtualizada para performance; em listas muito grandes, role dentro da coluna para ver mais cards.

## Apêndice técnico (para suporte)
- Em caso de erro ao salvar, o sistema pode voltar o card para a coluna anterior.
