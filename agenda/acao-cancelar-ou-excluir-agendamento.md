# Ação: cancelar ou excluir agendamento

## Cenário real
O paciente desmarcou, não vai comparecer, ou o agendamento foi criado por engano. Você precisa **liberar a vaga** e deixar isso claro para a equipe.

## Objetivo
Tirar o agendamento da grade (ou marcar como cancelado), garantindo que ninguém conte com aquele horário e que a vaga possa ser reutilizada.

## Quando usar
- Quando o paciente desmarca e a clínica precisa registrar a ocorrência.
- Quando um agendamento foi criado por engano e deve ser removido.

## Quando NÃO usar
- Quando a intenção é só mudar horário: use **editar agendamento**.

## Passo a passo detalhado
1. Na Agenda, clique no evento para abrir o editor.
2. Procure as opções relacionadas a cancelamento/remoção (geralmente em uma seção “Apagar” ou similar).
3. Confirme a ação no diálogo de confirmação.
4. Verifique se o evento foi removido da grade (ou se mudou para um status de cancelado, conforme regra aplicada).

## Campos envolvidos
Normalmente não há muitos campos; costuma haver:
- Confirmação da ação (diálogo)
- (Opcional) Motivo/observação de cancelamento (se o app solicitar)

## Regras do trabalho (o que costuma dar certo)
- Se a clínica precisa de histórico, prefira **cancelar** em vez de excluir.
- Quando cancelar, avalie imediatamente se você vai preencher a vaga com a **lista de espera**.

## Possíveis erros e como resolver
- **Não consigo cancelar/excluir**: permissão insuficiente.
  - Solução: solicite acesso ao gestor.
- **Erro ao atualizar a agenda**:
  - Solução: recarregue a página e confirme se o evento mudou; se não, tente novamente.

## Resultado esperado
O evento deixa de ocupar o horário na agenda (ou passa a refletir o estado cancelado), liberando a grade para novos agendamentos.

## Observações importantes
- Se a clínica usa lista de espera, após cancelamento você pode preencher a vaga com um item da lista.

## Apêndice técnico (para suporte)
- Dependendo da configuração, “cancelar” pode manter registro e “excluir” pode remover definitivamente.
