# Ação: criar agendamento

## Cenário real
O paciente pede um horário (primeira consulta, retorno, procedimento) e você precisa **reservar um slot**, registrar informações essenciais e deixar o time preparado para o dia do atendimento.

## Objetivo
Criar um agendamento que fique claro para a equipe: **quem é**, **quando é**, **qual serviço**, **qual status** e **o que precisa ser observado**.

## Quando usar
- Quando o paciente escolheu uma data/horário e você vai confirmar a marcação.
- Quando você vai fazer um **encaixe** (vaga aberta de última hora).
- Quando você vai agendar a partir da **lista de espera**.

## Quando NÃO usar
- Quando você ainda está só “vendo opções” sem reservar horário (evita segurar vaga por engano).
- Quando o paciente já tem um agendamento e o correto é **remarcar** (use a ação de editar).

## Passo a passo detalhado
1. Abra a **Agenda** e navegue até a data/semana desejada.
2. Clique em **Adicionar novo evento** (botão de adicionar na interface da agenda).
3. No editor do agendamento, preencha o mínimo para o dia funcionar:
   - Quem é o paciente (ou contato)
   - Qual serviço/procedimento
   - Data e hora
   - Situação/status (ex.: confirmado, pendente)
4. (Opcional, mas recomendado) Registre observações úteis:
   - Motivo do encaixe, preparo, detalhes de convênio, instruções combinadas.
5. Salve.
6. **Checkpoint**: o agendamento aparece na grade no horário certo.

## Campos envolvidos
Os campos podem variar, mas pense neles como “o que a equipe precisa saber para atender bem”:
- **Paciente/contato**: quem vai comparecer (e como falar com a pessoa).
- **Serviço**: o que será feito (consulta, retorno, procedimento).
- **Data e hora**: quando a pessoa deve chegar.
- **Status/situação**: em que pé está (pendente, confirmado, cancelado etc.).
- **Convênio** (quando a clínica usa): o pagador/regras de atendimento.
- **Observações**: instruções e detalhes (trazer exames, jejum, sala, prioridade).
- **Extras (se habilitados)**: videochamada, mensagens programadas, financeiro.

## Regras do trabalho (o que costuma dar certo)
- **Confirme o status**: se o paciente ainda não respondeu, deixe como pendente e só marque como confirmado quando houver confirmação.
- **Encaixe com contexto**: quando for encaixe, registre o porquê na observação para o médico não ser pego de surpresa.
- **Lista de espera**: se você está agendando alguém da lista de espera, confira se o paciente/contato e o serviço estão corretos antes de salvar.

## Possíveis erros e como resolver
- **Paciente não encontrado**:
  - O que fazer: busque por variações do nome/telefone. Se for uma pessoa nova, cadastre como paciente antes (ou use o fluxo de converter contato, quando existir).
- **Horário “não cabe” / conflito**:
  - O que fazer: escolha outro horário ou reduza o tempo/duração conforme a regra da clínica.
- **Erro ao salvar**:
  - O que fazer: revise os campos essenciais e tente de novo. Se repetir, recarregue a agenda e tente novamente.

## Resultado esperado
O agendamento fica visível na grade, com as informações necessárias para a equipe operar o atendimento sem ruído.

## Observações importantes
- Se houver um editor de prontuário aberto, navegação pode ser bloqueada para evitar perda de dados.

## Apêndice técnico (para suporte)
- Em alguns fluxos, criar agendamento pode ser iniciado a partir da lista de espera (o sistema abre o editor já “apontando” para o item).
