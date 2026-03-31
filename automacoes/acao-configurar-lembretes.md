# Ação: configurar lembretes automáticos

## Cenário real
Paciente esquece, chega atrasado ou falta. Um lembrete curto no horário certo reduz no-show e melhora a organização do dia.

## Objetivo
Configurar lembretes para serem enviados antes da consulta, com texto claro e útil.

## Quando usar
- Para reduzir faltas e atrasos.
- Para orientar paciente sobre preparação/documentos antes da consulta.

## Passo a passo detalhado
1. Acesse **Automações → Lembretes**.
2. Configure os cards de lembrete:
   - Enviar 2 horas antes da consulta
   - Enviar 12 horas antes da consulta
3. Salve as alterações no próprio card (quando aplicável).
4. **Checkpoint**: em um agendamento de teste, o lembrete é enviado no timing configurado.

## Campos envolvidos
Dependem de `AutomacaoWhatsappPaginaCard`:
- Fluxo/modelo
- Texto da mensagem

## Regras de negócio
- O disparo depende da data/hora do agendamento e do tempo configurado (ex.: 2h/12h).

## Possíveis erros e como resolver
- **Lembrete não enviado**:
  - Solução: confirme se o agendamento está no status correto, e se a conexão do WhatsApp está ativa.

## Resultado esperado
Os pacientes recebem lembretes automáticos nos horários configurados.

## Observações importantes
- Mensagens de lembrete devem ser claras e curtas, com data/hora e instruções essenciais.

## Apêndice técnico (para suporte)
- O envio depende do status do agendamento e da conexão ativa do WhatsApp.
