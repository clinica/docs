# Ação: gerenciar bancos

## Cenário real
Você quer conciliar o extrato ou organizar lançamentos por conta, mas o banco/conta ainda não existe no sistema.

## Objetivo
Cadastrar e manter bancos/contas para uso no financeiro e na conciliação (quando usada).

## Quando usar
- Ao adicionar uma nova conta/banco.
- Ao atualizar informações de um banco existente.

## Passo a passo detalhado
1. Acesse **Ajustes → Bancos**.
2. Clique em **Novo banco**.
3. Preencha os dados no diálogo e salve.
4. Confirme na lista.
5. **Checkpoint**: o banco/conta aparece como opção no financeiro/conciliação (quando aplicável).

## Campos envolvidos
Dependem de `BancoAddDialog` e `BancoLista`.

## Possíveis erros e como resolver
- **Erro ao salvar**:
  - Solução: revise campos e tente novamente.

## Resultado esperado
O banco fica disponível para uso em operações financeiras (incluindo conciliação, quando aplicável).
