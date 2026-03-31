# Ação: criar ou editar modelo de atendimento

## Cenário real
Você quer criar um modelo novo (ex.: “consulta gineco”, “retorno”, “pós-operatório”) ou ajustar um modelo existente para refletir o padrão atual do consultório.

## Objetivo
Deixar um modelo pronto para ser reutilizado, economizando tempo na consulta e garantindo consistência no prontuário.

## Quando usar
- Quando você quer acelerar o preenchimento do prontuário com um “template” pronto.
- Quando um modelo precisa ser atualizado para refletir novos protocolos da clínica.

## Quando NÃO usar
- Para registrar informações de um paciente específico: isso é no prontuário do paciente.

## Passo a passo detalhado
1. Acesse **Atendimento → Modelos de atendimento**.
2. Selecione **criar novo** ou clique para **editar** um modelo existente.
3. No editor de modelo:
   1. Preencha **Nome do modelo**.
   2. Selecione o **Tipo de modelo**.
   3. Escreva/ajuste o **conteúdo** no editor.
4. Clique em **Salvar modelo**.
5. Após salvar, você retorna automaticamente para a lista de modelos.
6. **Checkpoint**: ao voltar para a lista, o modelo aparece atualizado.

## Campos envolvidos
- **Nome do modelo** (obrigatório)
  - O que significa: como você vai reconhecer esse modelo no dia a dia.
- **Tipo de modelo**
  - O que significa: categoria do modelo (depende do que a clínica habilitou).
- **Conteúdo**
  - O que significa: o texto/estrutura que vai aparecer como base ao iniciar um atendimento.

## Regras do trabalho (para não virar bagunça)
- Mantenha o conteúdo “base”: o que sempre se repete e vale para a maioria dos atendimentos.
- Evite colocar dados que mudam sempre (isso fica para o atendimento do paciente).

## Possíveis erros e como resolver
- **Erro ao carregar modelo**: hash inválido ou indisponibilidade.
  - Solução: volte para a lista e tente abrir novamente; se persistir, anote qual modelo e contate suporte.
- **Não foi possível salvar o modelo**:
  - Pode ocorrer por falha de rede ou validação.
  - Solução: revise os campos obrigatórios e tente salvar novamente.
- **Mensagem de erro no formulário (erro raiz)**:
  - Quando o backend retorna erro controlado, ele aparece no formulário.
  - Solução: siga a orientação da mensagem exibida.

## Resultado esperado
O modelo fica salvo e disponível para uso e seleção durante atendimentos, ajudando a padronizar e acelerar registros.

## Observações importantes
- Ao sair da tela sem salvar, mudanças podem ser perdidas (dependendo do estado do editor).
- O editor do prontuário pode ter comportamento de salvamento local/sincronização em outras partes do sistema; aqui o salvamento é explícito via botão.

## Apêndice técnico (para suporte)
- “Novo” pode abrir o editor com modelo vazio; modelo existente depende de carregamento por identificador.
