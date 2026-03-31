# Ação: configurar automação de contratos e termos

## Cenário real
Você envia um termo para assinatura e o paciente fica com dúvida (“o que eu faço agora?”). Uma mensagem no momento certo reduz idas e voltas e melhora a taxa de assinatura.

## Objetivo
Padronizar mensagens para o fluxo de contratos/termos: envio manual e retorno após assinatura (quando a clínica usa).

## Quando usar
- Quando a clínica envia contratos/termos para pacientes assinarem.
- Quando deseja notificar/confirmar automaticamente após a assinatura.

## Passo a passo detalhado
1. Acesse **Automações → Contratos**.
2. Configure os cards:
   - “Envio manual”
   - “Após o paciente assinar o contrato/termo”
3. Salve as alterações.
4. **Checkpoint**: em um teste, o paciente recebe a mensagem certa antes/depois da assinatura.

## Campos envolvidos
Dependem de `AutomacaoWhatsappPaginaCard`:
- Fluxo/modelo
- Texto da mensagem

## Regras de negócio
- O card “após assinar” depende do evento de assinatura ser registrado no sistema.

## Possíveis erros e como resolver
- **Mensagem pós-assinatura não enviada**:
  - Solução: confirme se a assinatura foi registrada corretamente e se a conexão do WhatsApp está ativa.

## Resultado esperado
O paciente recebe mensagens alinhadas ao processo de assinatura, aumentando clareza e reduzindo suporte manual.

## Observações importantes
- Garanta que o texto inclua instruções claras e, quando aplicável, links para assinatura.

## Apêndice técnico (para suporte)
- A mensagem pós-assinatura depende do evento de assinatura estar sendo registrado corretamente.
