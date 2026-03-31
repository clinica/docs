# Ação: configurar automação de confirmações

## Cenário real
Você confirma consultas e precisa que o paciente receba a confirmação automaticamente, sem depender de alguém lembrar de mandar mensagem.

## Objetivo
Padronizar e automatizar a mensagem que sai quando a equipe confirma a agenda.

## Quando usar
- Quando a clínica confirma consultas e quer notificar o paciente automaticamente.
- Quando deseja padronizar o texto enviado após confirmação.

## Passo a passo detalhado
1. Acesse **Automações → Confirmações**.
2. No card “Ao confirmar a agenda”, configure o fluxo/mensagem:
   - Texto livre
   - Fluxo/modelo (quando disponível)
3. Salve as alterações no próprio card (quando aplicável).
4. **Checkpoint**: em um teste controlado, ao confirmar um agendamento, a mensagem é enviada como esperado.

## Campos envolvidos
Dependem do componente de automação (`AutomacaoWhatsappPaginaCard`), mas tipicamente incluem:
- Seleção de fluxo/modelo
- Texto da mensagem
- Variáveis disponíveis (quando a UI oferecer)

## Regras de negócio
- O disparo ocorre por uma ação manual do utilizador (confirmar agenda).

## Possíveis erros e como resolver
- **Configuração não salva**:
  - Solução: tente novamente; se persistir, recarregue e repita.

## Resultado esperado
Ao confirmar um agendamento, o sistema fica preparado para disparar a mensagem configurada ao paciente.

## Observações importantes
- Teste a mensagem em um cenário controlado antes de aplicar em larga escala.

## Apêndice técnico (para suporte)
- A automação depende de alguém acionar “Confirmar Agenda”; não é disparo automático por horário.
