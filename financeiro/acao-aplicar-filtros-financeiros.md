# Ação: aplicar filtros financeiros

## Cenário real
Você precisa achar uma movimentação específica (“cadê o PIX do João?”) ou quer conferir só o que está pendente / só despesas / só um convênio.

## Objetivo
Recortar a lista do financeiro para responder perguntas do dia a dia sem ficar procurando manualmente.

## Quando usar
- Quando você precisa encontrar uma movimentação específica.
- Quando deseja analisar apenas pendências, apenas entradas, apenas despesas etc.

## Quando NÃO usar
- Se você não está encontrando nada: primeiro confirme o período. Depois, filtre.

## Passo a passo detalhado
1. Acesse **Financeiro** no período desejado.
2. Abra a seção **Filtro** na sidebar do módulo.
3. Ajuste os filtros:
   - Categoria
   - Convênio
   - Pendência
   - NFe
4. Observe a lista se atualizar conforme os critérios selecionados.
5. **Checkpoint**: os resultados batem com o recorte (e você consegue achar o que procurava).

## Campos envolvidos
- **Categoria** (seletor)
- **Convênio** (seletor)
- **Pendência** (seletor)
- **NFe** (seletor)

## Regras do trabalho (para não “sumir” tudo)
- Aplique um filtro por vez até encontrar o que precisa.
- Se zerar a lista, limpe filtros e recomece (geralmente é algum filtro esquecido).

## Possíveis erros e como resolver
- **Nenhum resultado**:
  - Solução: remova filtros ou amplie o período.

## Resultado esperado
Você enxerga somente o subconjunto de movimentações que atende ao recorte desejado.

## Observações importantes
- Para análises por “modo” (entradas/saídas/despesas), o sistema também possui rotas/modos específicos no menu de movimentações.

## Apêndice técnico (para suporte)
- Alguns filtros podem usar valores internos especiais (ex.: `0` como “todos/sem filtro”) e podem combinar com modos de listagem.
