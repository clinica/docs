# Ação: programar envio manual

## Cenário real
Você quer padronizar mensagens que a equipe envia com frequência (retorno, instruções, pós-consulta) e, às vezes, já deixar programado para uma data.

## Objetivo
Manter fluxos de mensagens “manuais” organizados e, quando necessário, programar envios para não depender de lembrança.

## Quando usar
- Quando a clínica quer padronizar mensagens de contato (ex.: retorno, instruções, pós-consulta).
- Quando precisa programar envios para pacientes em momentos específicos.

## Passo a passo detalhado
1. Acesse **Automações → Envio manual**.
2. No card “Fluxos ativos”, configure os fluxos disponíveis (criar/ativar/editar conforme a UI do card).
3. Para ver e ajustar programações já existentes, clique em **Ver próximos envios**.
4. **Checkpoint**: um fluxo aparece como ativo e (se programado) aparece em “próximos envios”.

## Campos envolvidos
Dependem do componente de automação (fluxos):
- Nome/estrutura do fluxo
- Mensagem/texto e passos do fluxo

## Regras de negócio
- Fluxos manuais podem ser usados por ações explícitas do utilizador, e também por programações (cron).

## Possíveis erros e como resolver
- **Não aparece fluxo**:
  - Solução: confirme se existe fluxo ativo do tipo manual.

## Resultado esperado
Fluxos de envio manual ficam configurados e disponíveis para uso/programação.

## Observações importantes
- O histórico/programações ficam na tela “Próximos envios”.

## Apêndice técnico (para suporte)
- Fluxos manuais podem ser usados tanto por ações manuais quanto por programações.
