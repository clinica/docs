# Ação: editar cadastro do paciente

## Cenário real
O paciente mudou de número, escreveu o nome diferente, ou você percebeu um dado errado na recepção. Se você não corrigir, o consultório perde contato e a equipe se confunde.

## Objetivo
Manter o cadastro atualizado para que agenda, confirmações e prontuário funcionem sem ruído.

## Quando usar
- Quando o paciente atualizou telefone, endereço ou informações pessoais.
- Quando você precisa corrigir um dado que foi lançado incorretamente.

## Quando NÃO usar
- Quando existem dois cadastros da mesma pessoa: primeiro mescle para não corrigir “o cadastro errado”.

## Passo a passo detalhado
1. Na lista de Pacientes, localize o paciente desejado.
2. Abra o cadastro do paciente (clicando no item da lista, ou na ação de editar/abrir cadastro).
3. Atualize os campos necessários.
4. Salve e confirme a persistência da alteração.
5. **Checkpoint**: ao reabrir, os dados continuam corretos.

## Campos envolvidos
Os campos dependem da view `AtualizarPacienteView`. Tipicamente incluem:
- Dados pessoais (nome, documento)
- Contato (WhatsApp, telefone, email)
- Outras informações configuradas pela clínica

## Regras do trabalho (o que evita falha na comunicação)
- Confirme o telefone/WhatsApp com o paciente na recepção.
- Se o paciente não recebe mensagens, quase sempre é cadastro desatualizado.

## Possíveis erros e como resolver
- **Redireciona para a lista**:
  - O `pacienteId` pode estar inválido ou o paciente pode não existir.
  - Solução: acesse novamente pela lista e selecione o paciente.
- **Erro ao salvar**:
  - Solução: revise campos obrigatórios e tente novamente.

## Resultado esperado
O cadastro do paciente fica atualizado e refletido em módulos dependentes (agenda, atendimento, comunicação).

## Observações importantes
- Se houver duplicidade de cadastros, prefira mesclar antes de fazer manutenção massiva.

## Apêndice técnico (para suporte)
- Se o identificador do paciente estiver inválido, o sistema pode redirecionar para a lista.
