# Ação: copiar link de avaliação

## Cenário real
Você quer pedir feedback sem complicar: copia um link e envia para o paciente no WhatsApp logo após a consulta (ou no dia seguinte).

## Objetivo
Copiar o link público da avaliação para enviar ao paciente no canal de preferência.

## Quando usar
- Após uma consulta/procedimento, para coletar feedback do paciente.
- Em campanhas de qualidade (ex.: pós-atendimento).

## Quando NÃO usar
- Se o paciente ainda está insatisfeito no momento: às vezes é melhor resolver primeiro e depois enviar a pesquisa.

## Passo a passo detalhado
1. Acesse **Pesquisa de satisfação**.
2. Encontre a pesquisa desejada.
3. Clique em **Copiar link**.
4. Cole o link no canal desejado e envie ao paciente.
5. **Checkpoint**: ao colar, aparece um link completo (e abre no celular).

## Campos envolvidos
Não há campos; é uma ação de botão.

## Regras de negócio
- O link é montado a partir de uma variável de ambiente (endpoint do formulário NPS) + `formularioHash`.
- Após copiar, o sistema exibe mensagem de sucesso (“Link de avaliação copiado”).

## Possíveis erros e como resolver
- **Não copia** (permissão do navegador):
  - Solução: permita acesso à área de transferência ou copie manualmente se a UI oferecer alternativa.

## Resultado esperado
O link fica copiado e pronto para ser compartilhado com o paciente.

## Observações importantes
- Boas práticas: enviar entre 24h e 72h após atendimento tende a aumentar taxa de resposta.

## Apêndice técnico (para suporte)
- Se o navegador bloquear área de transferência, pode ser necessário permitir permissão ou copiar manualmente.
