# Ação: marcar sessão como completa ou pendente

## Cenário real
A sessão aconteceu (ou foi reagendada) e você precisa manter o controle: **o que já foi feito** e **o que ainda está pendente**.

## Objetivo
Marcar corretamente o status da sessão para refletir o andamento do tratamento e manter as métricas confiáveis.

## Quando usar
- Quando a sessão foi realizada e precisa ser marcada como completa.
- Quando uma sessão foi marcada incorretamente e precisa voltar para pendente.

## Quando NÃO usar
- Quando a sessão deve ser removida do plano (por erro de cadastro): nesse caso, remova a sessão.

## Passo a passo detalhado
### No Calendário
1. Acesse **Imunoterapia → Calendário**.
2. Localize a sessão do paciente na lista do dia.
3. Clique em **Completar** para marcar como completa.

### Na lista de Pacientes
1. Acesse **Imunoterapia → Pacientes**.
2. Localize o paciente e a sessão desejada.
3. Clique na sessão para alternar o estado (completa ↔ pendente).
4. **Checkpoint**: a sessão muda de visual (e o progresso do paciente se atualiza).

## Campos envolvidos
Não há campos de formulário; trata-se de uma ação direta de status.

## Regras do trabalho (o que evita ruído)
- Marque como completa assim que terminar a sessão para não esquecer depois.
- Se a sessão foi marcada errada, corrija no mesmo dia para manter o acompanhamento fiel.

## Possíveis erros e como resolver
- **Erro ao atualizar a sessão**:
  - Solução: tente novamente; se persistir, recarregue a página e repita.

## Resultado esperado
A sessão muda de estado e o progresso do paciente (incluindo percentuais e indicadores) é atualizado na UI.

## Observações importantes
- Em momentos de instabilidade, aguarde o fim do carregamento (mutação em andamento) antes de clicar novamente.

## Apêndice técnico (para suporte)
- A UI mostra mensagens de sucesso/erro via toast ao atualizar o status.
