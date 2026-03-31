# Ação: abrir prontuário do paciente

## Cenário real
O paciente chegou, você vai atender, ou precisa revisar um histórico antes de decidir conduta. Você precisa chegar no prontuário certo sem perder tempo.

## Objetivo
Acessar o prontuário no contexto do paciente para consultar histórico e registrar a consulta.

## Quando usar
- Quando o paciente chegou para atendimento e você precisa registrar a consulta.
- Quando precisa revisar histórico e evoluções anteriores.

## Quando NÃO usar
- Se você já está com o atendimento aberto a partir da agenda do dia (quando existir esse caminho), pode ser mais direto continuar pelo fluxo de atendimento.

## Passo a passo detalhado
1. Acesse **Pacientes** e localize o paciente.
2. Abra o paciente e escolha a opção de **Prontuário**.
3. No prontuário, navegue entre as abas e registre/visualize informações.
4. **Checkpoint**: o nome do paciente no prontuário confere com a pessoa atendida.

## Campos envolvidos
O prontuário pode ter várias seções (dependendo da clínica):
- Registro clínico e formulários
- Modelos de atendimento
- Prescrição digital (quando habilitada)
- Recursos adicionais

## Regras do trabalho (segurança e rotina)
- Sempre confirme que está no prontuário do paciente certo (principalmente quando há nomes parecidos).
- Se o sistema bloquear navegação por edição em andamento, finalize/salve antes de trocar de paciente.

## Possíveis erros e como resolver
- **Redirecionamento para lista**:
  - Indica `pacienteId` inválido.
  - Solução: acesse a partir da lista e selecione o paciente correto.
- **Recursos faltando no prontuário**:
  - Pode depender de permissões ou habilitação de módulos.
  - Solução: confirme configurações e perfil.

## Resultado esperado
O prontuário abre no contexto do paciente e permite consultar/registrar informações clínicas.

## Observações importantes
- Se houver um editor de prontuário aberto, o sistema pode bloquear navegação para evitar perda de conteúdo.

## Apêndice técnico (para suporte)
- Alguns recursos do prontuário podem depender de integrações e configurações específicas do paciente.
