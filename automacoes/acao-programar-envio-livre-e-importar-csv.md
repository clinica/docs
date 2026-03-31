# Ação: programar envio livre e importar CSV

## Cenário real
Você precisa enviar um comunicado (campanha, aviso, mudança de horário) para uma lista de contatos que nem sempre estão cadastrados como pacientes.

## Objetivo
Programar envios em lote para contatos, manualmente ou importando um CSV, sem fazer “um por um”.

## Quando usar
- Quando a clínica precisa enviar mensagens para uma lista de contatos (campanhas, avisos, comunicados).
- Quando os destinatários não estão cadastrados como pacientes.

## Passo a passo detalhado
### Adicionar mensagem livre
1. Acesse **Automações → Envio livre**.
2. Clique em **Adicionar mensagem**.
3. Preencha a programação:
   - Data e hora
   - Contato (telefone/identificador)
   - Fluxo/Tipo (texto livre ou fluxo)
   - Mensagem (quando texto livre)
4. Salve e confirme que aparece na lista.

### Importar CSV
1. Na mesma tela, clique em **Importar CSV**.
2. Envie o arquivo conforme o formato esperado pelo sistema.
3. Confirme que os envios aparecem na lista programada.
4. **Checkpoint**: os contatos aparecem na lista com data/hora futura e sem erro de validação.

## Campos envolvidos
Na lista (edição por célula):
- Data e hora (calendário + hora)
- Contato (texto)
- Fluxo/Tipo (select)
- Mensagem (textarea, quando texto livre)

## Regras de negócio
- Validação de antecedência mínima:
  - Se a data/hora escolhida estiver muito próxima, o sistema bloqueia e mostra erro.
- Data mínima:
  - Não permite agendar para datas anteriores ao dia atual.
- Mensagens de retorno:
  - “Programação atualizada”, “Programação removida”, e mensagens de erro.

## Possíveis erros e como resolver
- **Erro de antecedência mínima**:
  - Solução: escolha um horário mais à frente.
- **Erro ao atualizar/remover**:
  - Solução: tente novamente; se persistir, recarregue a página.

## Resultado esperado
Mensagens livres ficam programadas corretamente e, se importadas via CSV, entram em lote na programação.

## Observações importantes
- Se você escolher um “fluxo”, a mensagem pode ficar não-editável na célula (dependendo da regra do tipo).

## Apêndice técnico (para suporte)
- O sistema pode bloquear agendamentos muito próximos do horário atual (antecedência mínima) e datas passadas.
