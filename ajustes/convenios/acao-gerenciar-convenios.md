# Ação: gerenciar convênios

## Cenário real
Você precisa incluir um convênio novo (ou ajustar um existente) para a recepção não errar na hora de marcar e para o financeiro conseguir acompanhar.

## Objetivo
Cadastrar e manter convênios disponíveis para uso na agenda, atendimento e financeiro.

## Quando usar
- Ao cadastrar um novo convênio.
- Ao arquivar/desarquivar ou atualizar dados do convênio (quando disponível).

## Passo a passo detalhado
1. Acesse **Ajustes → Convênios**.
2. Clique em **Novo**.
3. Preencha os dados solicitados no diálogo.
4. Salve e confira o convênio na lista.
5. **Checkpoint**: ao agendar um paciente, o convênio aparece como opção (se a clínica usar esse vínculo).

## Campos envolvidos
Dependem de `ConvenioAddDialog` e `ConvenioLista`.

## Regras de negócio
- Botão “Novo” tem rastreamento de ação (`trackName="ajustes-convenios-novo"`).

## Regras do trabalho (para evitar confusão)
- Padronize o nome do convênio como a equipe usa no dia a dia.
- Se um convênio não for mais atendido, arquive/inative para não ser selecionado por engano (quando existir essa opção).

## Possíveis erros e como resolver
- **Erro ao salvar**:
  - Solução: revise campos obrigatórios e tente novamente.

## Resultado esperado
O convênio fica disponível nos módulos que permitem associar convênio a paciente/atendimento.
