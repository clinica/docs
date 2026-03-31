# Ação: gerenciar fornecedores

## Cenário real
Você quer lançar uma despesa e precisa vincular ao fornecedor certo (laboratório, manutenção, internet, material). Sem isso, o financeiro fica confuso.

## Objetivo
Cadastrar e manter fornecedores para facilitar compras e lançamentos financeiros.

## Quando usar
- Quando cadastrar um novo fornecedor.
- Quando atualizar dados de contato ou status de um fornecedor.

## Passo a passo detalhado
1. Acesse **Ajustes → Fornecedores**.
2. Clique em **Novo**.
3. Preencha os dados solicitados e salve.
4. **Checkpoint**: o fornecedor aparece na lista e pode ser selecionado onde fizer sentido (ex.: despesas).

## Campos envolvidos
Dependem de `FornecedorAddDialog` e `FornecedorLista`.

## Possíveis erros e como resolver
- **Erro ao salvar**:
  - Solução: revise campos e tente novamente.

## Resultado esperado
O fornecedor passa a ficar disponível para seleção em rotinas que dependem dele (ex.: despesas, compras).
