# Indicações

## Objetivo
Organizar o programa de indicações para a clínica crescer com consistência: acompanhar quem indicou, fazer contato com indicados, avançar status e converter em pacientes quando fecharem.

## Para quem é (na prática)
- **Gestor/marketing**: acompanhar resultados e ajustar a página/formulário.
- **Secretária/atendimento comercial**: entrar em contato com indicado e atualizar o andamento.
- **Profissional**: compartilhar link/QR para receber indicações atribuídas.

## Principais benefícios
- **Crescimento orgânico**: transforma pacientes em canal de aquisição.
- **Rastreabilidade**: sabe quem indicou e em qual estágio está cada indicado.
- **Conversão assistida**: permite converter indicado em paciente e manter vínculo.

## Como essa área entra no seu dia (mini-fluxo)
1. Chega uma indicação pelo formulário.
2. A recepção/atendimento comercial faz o primeiro contato.
3. Atualiza status (em andamento, agendado, convertido etc.).
4. Quando virar paciente, converte e segue o fluxo normal (agenda e prontuário).

## Ações disponíveis neste grupo
- [`acao-ver-ranking-de-indicadores.md`](acao-ver-ranking-de-indicadores.md)
- [`acao-gerenciar-indicados.md`](acao-gerenciar-indicados.md)
- [`acao-usar-quadro-de-indicacoes.md`](acao-usar-quadro-de-indicacoes.md)
- [`acao-gerar-link-do-formulario-de-indicacao.md`](acao-gerar-link-do-formulario-de-indicacao.md)
- [`acao-ajustar-pagina-publica-de-indicacoes.md`](acao-ajustar-pagina-publica-de-indicacoes.md)

## Impacto no sistema como um todo
- **Pacientes**: conversão de indicado cria paciente e relaciona ao `indicacaoHash`.
- **Operação**: status do indicado ajuda a priorizar contato e acompanhar resultados.
- **Comunicação**: a clínica pode usar WhatsApp/email para contato com indicados (fora do escopo desta tela).

## Observações importantes
- **Disponibilidade do menu**: o item “Indicações” pode não aparecer na sidebar quando o programa não está habilitado (`exibirProgramaIndicacao`).

## Apêndice técnico (para suporte)
- A exibição do módulo pode depender do recurso `exibirProgramaIndicacao`.
