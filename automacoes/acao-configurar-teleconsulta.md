# Ação: configurar automações de teleconsulta

## Cenário real
Em teleconsulta, o paciente se perde com link, horário e orientações. Mensagens automáticas no momento certo reduzem atraso e suporte manual.

## Objetivo
Padronizar mensagens de teleconsulta (antes do horário e envio manual), com instruções claras e link quando aplicável.

## Quando usar
- Quando a clínica realiza teleconsultas e quer orientar paciente automaticamente.
- Quando precisa padronizar instruções de acesso, links e recomendações.

## Passo a passo detalhado
1. Acesse **Automações → Teleconsulta**.
2. Configure os cards:
   - “5 minutos antes do horário da teleconsulta”
   - “Envio manual pelo prontuário”
3. Salve as alterações no card.
4. **Checkpoint**: em um teste, o paciente recebe instruções e consegue entrar sem pedir ajuda.

## Campos envolvidos
Dependem de `AutomacaoWhatsappPaginaCard`:
- Seleção de fluxo
- Texto livre

## Regras de negócio
- O card “envio manual” depende de uma ação no prontuário para disparar.

## Possíveis erros e como resolver
- **Mensagem não dispara**:
  - Solução: valide conexão do WhatsApp e se o evento (teleconsulta/manual) foi acionado corretamente.

## Resultado esperado
Mensagens de teleconsulta são enviadas automaticamente no tempo configurado e/ou manualmente quando acionadas.

## Observações importantes
- Inclua instruções claras, especialmente link e recomendações de conexão.

## Apêndice técnico (para suporte)
- A mensagem automática depende do horário do evento e a manual depende de um acionamento no prontuário.
