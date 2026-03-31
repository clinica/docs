# Ação: gerenciar lista de espera

## Cenário real
O paciente quer atendimento, mas hoje não tem horário. Você precisa **não perder o contato** e, quando abrir uma vaga, encaixar rapidamente sem refazer trabalho.

## Objetivo
Organizar pedidos de encaixe por profissional, com dados suficientes para agendar assim que houver disponibilidade.

## Quando usar
- Quando um paciente quer encaixe e você não tem horário disponível no momento.
- Quando você quer organizar os pedidos de encaixe por profissional e priorizar atendimentos.

## Quando NÃO usar
- Quando já existe uma vaga confirmada: nesse caso, faça o agendamento direto.

## Passo a passo detalhado
1. Na Agenda, clique em **Lista de espera** (botão/atalho no menu lateral da agenda).
2. Na seção do profissional desejado:
   1. Clique em **Adicionar paciente**.
   2. Preencha o formulário de inclusão (paciente/contato, serviço, telefone, observação).
   3. Confirme para salvar.
3. Para atualizar observação:
   1. Clique no texto da coluna **Observação** do item.
   2. Edite e clique em **Salvar**.
4. Para agendar um item:
   1. Clique no ícone de **Agendar** (calendário) na coluna de ações.
   2. O sistema volta para a agenda e abre o fluxo de criação do evento já “apontando” para o item da lista.
5. Para remover:
   1. Clique em remover e confirme no diálogo.
6. **Checkpoint**: a lista mostra o paciente/contato com telefone e serviço, pronto para encaixe.

## Campos envolvidos
Na lista:
- **Data**: data/hora em que o item entrou na lista.
- **Paciente**: nome do paciente (ou nome do contato).
- **Telefone**: pode incluir atalho para WhatsApp.
- **Serviço**: serviço associado ao pedido.
- **Observação**: texto livre editável.

No diálogo de observação:
- **Observação** (textarea)

## Regras do trabalho (o que costuma dar certo)
- Sempre registre **telefone** e **serviço**: quando abrir vaga, isso evita ter que ligar “só para perguntar de novo”.
- Use observação para prioridades (“gestante”, “dor aguda”, “retorno urgente”) sem expor detalhes sensíveis.

## Possíveis erros e como resolver
- **Erro ao carregar a lista de espera**:
  - A tela oferece botão **Tentar novamente**.
- **Erro ao atualizar observação**:
  - O sistema mostra mensagem de erro (incluindo mensagens vindas do backend quando disponíveis).
- **Erro ao remover**:
  - Pode ocorrer por permissão ou falha de rede.
  - Solução: tente novamente; se persistir, contate suporte.

## Resultado esperado
Itens entram e saem da lista de espera com consistência, e você consegue converter um item em agendamento quando surgir disponibilidade.

## Observações importantes
- Quando há telefone, pode haver atalho para abrir conversa no WhatsApp (em nova aba).

## Apêndice técnico (para suporte)
- Ao clicar em “Agendar”, a agenda pode ser aberta já com o contexto do item selecionado da lista de espera.
