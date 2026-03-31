# Ação: configurar agendas e opções de exibição

## Cenário real
A recepção pede para “aparecer tal informação” no agendamento (ex.: guia do convênio) ou a agenda está ficando confusa e você quer padronizar o que todo mundo enxerga.

## Objetivo
Ajustar as opções que aparecem na agenda e acessar as configurações de cada agenda quando necessário.

## Quando usar
- Quando a clínica quer ajustar horários/intervalos de uma agenda.
- Quando deseja exibir/ocultar informações adicionais na agenda.

## Passo a passo detalhado
1. Acesse **Ajustes → Agenda**.
2. Em “Configurações da agenda”:
   1. Selecione uma agenda na lista para abrir os ajustes daquela agenda.
3. Configure cores (quando disponível) no card de cores.
4. Em “Informações adicionais na agenda”, ajuste os toggles:
   - Exibir número de guia de convênio
   - Exibir controle gestacional
5. **Checkpoint**: ao abrir a Agenda, as informações extras aparecem (ou somem) como esperado.

## Campos envolvidos
- Lista de agendas (links)
- Toggles (`Switch`):
  - **Exibir número de guia de convênio**
  - **Exibir controle gestacional**

## Regras de negócio
- Ao alterar um toggle:
  - Atualiza configuração no backend.
  - Atualiza cache de configuração da sessão.
  - Exibe toast de sucesso indicando se foi exibido/ocultado.

## Possíveis erros e como resolver
- **“Erro ao atualizar configuração”**:
  - Solução: tente novamente; se persistir, recarregue e repita.
- **Nenhuma agenda cadastrada**:
  - Solução: confirme se há profissionais/agendas configurados na clínica.

## Resultado esperado
As opções passam a valer para a operação da agenda e a UI reflete imediatamente as configurações.

## Observações importantes
- Ajustes detalhados de horários e intervalos costumam estar na página de ajustes da agenda específica (aberta ao clicar em uma agenda na lista).

## Apêndice técnico (para suporte)
- Ao alterar toggles, o sistema recarrega configuração de sessão para refletir imediatamente na UI.
