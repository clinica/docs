# Ação: mesclar cadastros de pacientes

## Cenário real
Você percebeu que a mesma pessoa foi cadastrada duas vezes (por variação de nome, telefone antigo, digitação). Isso começa a bagunçar agenda e histórico de atendimento.

## Objetivo
Unificar dois cadastros em um só, evitando que o histórico fique dividido e que a equipe use “o paciente errado”.

## Quando usar
- Quando existem dois pacientes cadastrados para a mesma pessoa.
- Quando duplicidades estão causando confusão em agenda/atendimento/financeiro.

## Quando NÃO usar
- Quando não há certeza de que é a mesma pessoa. Antes, confirme por CPF/data de nascimento/telefone.

## Passo a passo detalhado
1. Acesse **Pacientes**.
2. No menu de opções (ícone de “mais opções”), clique em **Mesclar cadastros**.
3. Selecione o **Paciente que será mantido**.
4. Selecione o **Paciente que será mesclado**.
5. Clique em **Mesclar cadastros de pacientes**.
6. No diálogo de confirmação, leia o aviso e clique em **Confirmo a mesclagem**.
7. **Checkpoint**: ao voltar para a lista, ficou apenas um cadastro (o mantido).

## Campos envolvidos
Não há formulário tradicional; os campos são seleções:
- **Paciente que será mantido**: selecionado por pesquisa.
- **Paciente que será mesclado**: selecionado por pesquisa.
- Confirmação em diálogo de alerta.

## Regras do trabalho (muito importante)
- **É irreversível**: faça apenas quando tiver certeza.
- Escolha “manter” como o cadastro mais completo e correto (nome, documento, contato).
- Faça a mesclagem antes de criar novos agendamentos/atendimentos para não espalhar o histórico.

## Possíveis erros e como resolver
- **Paciente não encontrado**:
  - Solução: selecione novamente.
- **Erro retornado pelo backend**:
  - Pode aparecer como alerta com a mensagem.
  - Solução: siga a orientação; se persistir, contate suporte.

## Resultado esperado
Fica apenas um cadastro consolidado e o duplicado deixa de existir, reduzindo inconsistências no sistema.

## Observações importantes
- Faça a mesclagem antes de criar novos agendamentos/atendimentos para evitar fragmentação de histórico.

## Apêndice técnico (para suporte)
- A mesclagem invalida listas de pacientes e pode atualizar dados relacionados à agenda.
