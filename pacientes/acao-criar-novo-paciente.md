# Ação: criar novo paciente

## Cenário real
Chegou um paciente novo (ou um contato que ainda não está cadastrado) e você precisa registrar para agendar/atender sem confundir com outra pessoa.

## Objetivo
Cadastrar o paciente com o mínimo necessário para operar: identificação e um contato confiável para confirmações e orientações.

## Quando usar
- Quando o paciente ainda não existe na base da clínica.
- Quando um contato precisa ser convertido em paciente para agendamento/atendimento.

## Quando NÃO usar
- Quando você suspeita que já existe cadastro: antes, busque por nome/telefone/CPF para evitar duplicidade.

## Passo a passo detalhado
1. Na barra lateral, clique em **Pacientes**.
2. No topo da barra lateral do módulo, clique em **Novo**.
3. No formulário/diálogo de criação:
   1. Preencha os dados básicos (nome, CPF, WhatsApp).
   2. (Opcional) Selecione a origem/evento quando disponível.
4. Confirme para salvar.
5. **Checkpoint**: o paciente aparece na lista e pode ser usado na agenda.

## Campos envolvidos
Os valores iniciais exibidos indicam os campos típicos:
- **Nome** (texto)
- **CPF** (texto)
- **WhatsApp** (texto)
- **Evento/origem** (opcional)

## Regras do trabalho (para evitar dor de cabeça depois)
- Antes de criar, busque por **nome e telefone**. Se achar parecido, confirme com o paciente.
- Se acontecer duplicidade, resolva cedo com **mesclagem** (evita histórico dividido).

## Possíveis erros e como resolver
- **Paciente duplicado** (por CPF ou contato):
  - Solução: procure na lista; se existirem cadastros duplicados, use a ação de mesclar cadastros.
- **Erro ao salvar**:
  - Solução: revise campos obrigatórios e tente novamente; se persistir, contate suporte.

## Resultado esperado
O paciente é criado, aparece na lista e pode ser usado em agendamentos e no atendimento.

## Observações importantes
- Podem aparecer campos adicionais conforme configuração da clínica.

## Apêndice técnico (para suporte)
- Campos adicionais podem variar conforme configuração (implementação interna do módulo).
