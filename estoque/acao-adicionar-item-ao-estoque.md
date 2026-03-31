# Ação: adicionar item ao estoque

## Cenário real
Chegou um novo insumo (ou você percebeu que a clínica usa um material que ainda não está no sistema). Sem cadastrar, não dá para controlar lote, validade e saldo.

## Objetivo
Cadastrar um item do estoque com o mínimo necessário para começar a controlar lote/validade.

## Quando usar
- Quando a clínica passa a utilizar um novo insumo/material.
- Quando quer padronizar itens antes de criar lotes e registrar consumo.

## Quando NÃO usar
- Se o item já existe com outro nome parecido. Antes, pesquise para evitar duplicidade.

## Passo a passo detalhado
1. Acesse **Estoque → Itens do estoque**.
2. Clique em **Novo**.
3. No diálogo “Adicionar novo item”:
   1. Preencha **Nome do item**.
   2. Selecione **Forma** (pesquise e selecione).
4. Clique em **Adicionar ao estoque**.
5. Após sucesso, você será direcionado para os detalhes do item.
6. **Checkpoint**: na tela de detalhes, o item aparece com o nome correto e pronto para receber lotes.

## Campos envolvidos
- **Nome do item** (obrigatório)
- **Forma** (obrigatório)
  - Seletor com pesquisa

## Regras do trabalho (para não virar bagunça)
- Nomeie com padrão fácil (ex.: “Seringa 5ml”, “Agulha 25x7”, “Luvas P”), para a equipe encontrar rápido.
- Use uma “forma” coerente com o item, porque isso ajuda em listagens e relatórios.

## Possíveis erros e como resolver
- **“Por favor, selecione uma forma válida.”**:
  - Solução: selecione uma opção existente na lista.
- **Erro ao adicionar item ao estoque**:
  - Solução: tente novamente; se persistir, contate suporte.

## Resultado esperado
O item é criado e você passa a poder cadastrar lotes, validade e quantidades para ele.

## Observações importantes
- Se ocorrer erro retornado pelo backend, a mensagem pode aparecer no formulário e também como toast.

## Apêndice técnico (para suporte)
- Após criar, o sistema pode redirecionar automaticamente para a página do item recém-criado.
