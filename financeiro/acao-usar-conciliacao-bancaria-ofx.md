# Ação: usar conciliação bancária (OFX)

## Cenário real
Chegou o fim do mês e você precisa bater o que está no banco com o que foi lançado no sistema. Também quer achar transações que aconteceram no extrato, mas ninguém lançou.

## Objetivo
Importar um extrato OFX e vincular transações do banco às movimentações do sistema, deixando o financeiro mais confiável.

## Quando usar
- Quando a clínica quer conferir se tudo que entrou/saiu no banco está refletido no sistema.
- Quando deseja identificar transações não lançadas e criar movimentações a partir do extrato.

## Quando NÃO usar
- Se você ainda não tem extrato fechado do período (ou o OFX está incompleto). Espere ter o arquivo certo para não confundir.

## Passo a passo detalhado
### Importar extrato OFX
1. Acesse **Financeiro → Conciliação bancária**.
2. Clique em **Importar extrato OFX**.
3. Selecione o arquivo OFX e confirme (no diálogo de importação).
4. Aguarde o extrato aparecer na lista.

### Abrir um extrato
1. Na lista de extratos, clique no extrato desejado para abrir o detalhe.
2. Veja a tabela de transações do extrato.

### Vincular ou criar movimentação
1. Para itens com **match disponível**, clique em **Vincular**.
2. Para itens **sem match**, use a opção de **criar movimentação** a partir do item (quando disponível).
3. **Checkpoint**: os itens vinculados ficam como “conciliados” (ou equivalente).

## Campos envolvidos
### Lista de extratos
- Ações: importar OFX

### Detalhe do extrato
Cada transação exibe:
- Status (conciliado / match / sem match)
- Data
- Tipo (entrada/saída)
- Descrição
- Valor
- Ações (vincular ou criar movimentação)

## Regras do trabalho (para conciliar com segurança)
- Se o sistema sugerir “match”, confira data/valor/descrição antes de vincular.
- Se não houver match, crie a movimentação e depois vincule para não deixar buraco.

## Possíveis erros e como resolver
- **Erro ao vincular item**:
  - Pode mostrar mensagem do backend.
  - Solução: tente novamente; se persistir, crie movimentação manualmente e vincule.
- **Nenhuma transação encontrada**:
  - Verifique se o arquivo OFX possui transações válidas.

## Resultado esperado
As transações do extrato passam a ficar vinculadas às movimentações do sistema, deixando o status como **Conciliado**.

## Observações importantes
- A conciliação pode estar em fase de ativação, mas o sistema já permite importar arquivos para iniciar o histórico.

## Apêndice técnico (para suporte)
- O sistema pode sugerir match com tolerância de dias e valor (ex.: 3 dias e 0,01).
