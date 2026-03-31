# Ação: gerenciar serviços

## Cenário real
Você vai começar a oferecer um novo procedimento, ou a equipe está agendando com nomes diferentes para a mesma coisa. Isso vira confusão na agenda e no financeiro.

## Objetivo
Manter uma lista de serviços clara e padronizada para selecionar na agenda e usar no financeiro.

## Quando usar
- Ao cadastrar um novo procedimento/serviço.
- Ao ajustar nomenclatura, preço e características do serviço (quando disponíveis).

## Passo a passo detalhado
1. Acesse **Ajustes → Serviços**.
2. Clique em **Novo**.
3. Preencha os dados solicitados no diálogo.
4. Salve e confirme na lista.
5. **Checkpoint**: ao voltar para a Agenda, o serviço aparece na seleção.

## Campos envolvidos
Dependem do diálogo `ServicoAddDialog` e da lista `ServicoLista`.

## Regras de negócio
- Serviços podem ser usados em filtros e vínculos em outros módulos.

## Regras do trabalho (para ficar organizado)
- Use nomes que façam sentido para a recepção (ex.: “Consulta”, “Retorno”, “Procedimento X”).
- Evite duplicar serviços parecidos; isso atrapalha relatórios e padronização.

## Possíveis erros e como resolver
- **Erro ao salvar**:
  - Solução: revise campos e tente novamente.

## Resultado esperado
O serviço passa a ficar disponível para seleção/uso nos módulos que dependem dele.
