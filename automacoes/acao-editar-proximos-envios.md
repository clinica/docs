# Ação: editar próximos envios (programações)

## Cenário real
Você programou mensagens, mas mudou o horário de atendimento, mudou a campanha ou percebeu que uma mensagem está errada. Precisa corrigir antes de enviar.

## Objetivo
Revisar e ajustar envios futuros: mudar data/hora, trocar fluxo/tipo, editar mensagem (quando for texto livre) e cancelar programações.

## Quando usar
- Quando precisa corrigir horário de envio.
- Quando quer trocar o fluxo associado a um envio.
- Quando precisa cancelar um envio programado.

## Passo a passo detalhado
1. Acesse **Automações → Envio manual → Ver próximos envios**.
2. Na tabela, clique em um campo para editar:
   - **Data e hora**: abre calendário + seletor de hora.
   - **Fluxo/Tipo**: seleciona um fluxo ativo ou “Texto livre”.
   - **Mensagem**: editável quando o tipo for “Texto livre”.
3. Clique em **Salvar** no popover do campo.
4. Para remover, use o botão de remoção (com confirmação).
5. **Checkpoint**: a lista mostra as alterações (e o envio certo, no horário certo).

## Campos envolvidos
- **Data** (calendário)
- **Hora** (input `time`)
- **Fluxo/Tipo** (select com fluxos ativos + “Texto livre”)
- **Mensagem** (textarea, apenas quando for texto livre)

## Regras de negócio
- Ao salvar, a programação é atualizada e a lista é recarregada.
- Mensagens de retorno:
  - Sucesso: “Programação atualizada”
  - Remoção: “Programação removida”
  - Erros: mensagem do backend (quando disponível) ou mensagens genéricas.
- Quando o envio tem um fluxo (não é texto livre), a célula de mensagem fica desabilitada.

## Possíveis erros e como resolver
- **Erro ao atualizar**:
  - Solução: tente novamente; se persistir, recarregue.
- **Erro ao remover**:
  - Solução: tente novamente; se persistir, contate suporte.

## Resultado esperado
Programações ficam corretas e refletidas na lista, reduzindo envios indevidos.

## Observações importantes
- A tela é voltada para envios futuros (ainda não enviados).

## Apêndice técnico (para suporte)
- Quando o envio usa um fluxo (não texto livre), a célula de mensagem pode ficar desabilitada.
