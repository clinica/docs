# Ação: configurar automações por status da agenda

## Cenário real
Você quer que o paciente receba mensagens automaticamente em momentos-chave: quando agenda, quando confirma e quando finaliza, sem depender de alguém lembrar de mandar.

## Objetivo
Configurar mensagens automáticas por etapa da agenda, mantendo comunicação consistente e reduzindo trabalho manual.

## Quando usar
- Quando a clínica quer automatizar comunicação em cada etapa do agendamento.
- Para reduzir trabalho manual da recepção.

## Passo a passo detalhado
1. Acesse **Automações → Status da agenda**.
2. Configure os cards disponíveis:
   - “Ao agendar um paciente”
   - “Ao alterar o status para confirmado”
   - “Ao finalizar um atendimento”
3. Salve as alterações (conforme UI do card).
4. **Checkpoint**: em um agendamento de teste, ao mudar o status, a mensagem sai como esperado.

## Campos envolvidos
Dependem de `AutomacaoWhatsappPaginaCard`:
- Fluxo/modelo
- Texto livre
- (Opcional) parâmetros do disparo

## Regras de negócio
- Os disparos são vinculados a eventos de domínio (agendamento/status/conclusão).

## Possíveis erros e como resolver
- **Mensagem não dispara no dia a dia**:
  - Pode ser conexão do WhatsApp ou regra de status.
  - Solução: confirme conexão e se o status realmente foi alterado no fluxo.

## Resultado esperado
Ao ocorrer o evento correspondente, o sistema envia a mensagem conforme configurado.

## Observações importantes
- Padronize textos e variáveis para evitar mensagens inconsistentes.

## Apêndice técnico (para suporte)
- O envio depende de conexão ativa e do status/evento ser realmente acionado no fluxo.
