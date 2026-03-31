# Ação: gerenciar grupos de uso do estoque

## Cenário real
Você quer padronizar consumo por procedimento (ex.: “kit curativo”, “aplicação X”), para prever reposição e evitar que falte item no meio do atendimento.

## Objetivo
Criar grupos que representam “o que vai” em cada uso/procedimento, ajudando controle e reposição.

## Quando usar
- Quando você quer agrupar itens usados juntos (ex.: “Kit curativo”, “Procedimento X”).
- Quando precisa controlar consumo padrão por evento/procedimento.

## Quando NÃO usar
- Se você ainda não cadastrou os itens no estoque. Primeiro cadastre itens, depois crie o grupo.

## Passo a passo detalhado
1. Acesse **Estoque → Grupos de uso**.
2. Clique para **adicionar um grupo**.
3. No modal de criação:
   1. Defina nome e descrição do grupo.
   2. Selecione itens de estoque e quantidades por uso (quando solicitado).
4. Salve e confirme que o grupo aparece na lista.
5. **Checkpoint**: o grupo aparece e você consegue ver itens por uso.

## Campos envolvidos
Depende do modal (`GrupoAddModal`), mas tipicamente:
- Nome do grupo
- Descrição
- Seleção de itens de estoque
- Quantidade por uso

## Regras do trabalho (para ser útil de verdade)
- Nomeie por rotina (“Kit curativo”, “Procedimento X”) e mantenha descrição curta.
- Revise quantidades por uso quando mudar protocolo ou fornecedor.

## Possíveis erros e como resolver
- **Não aparece item para selecionar**:
  - Solução: cadastre itens de estoque primeiro.
- **Erro ao salvar grupo**:
  - Solução: revise campos obrigatórios e tente novamente.

## Resultado esperado
O grupo passa a existir e pode ser usado como referência para consumo e controle de estoque.

## Observações importantes
- O grupo pode exibir métricas como “itens por uso” e saldo disponível agregado por item.

## Apêndice técnico (para suporte)
- A lista de itens precisa existir para montar grupos.
