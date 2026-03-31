# Ação: ajustar página pública de indicações

## Cenário real
Você divulgou o programa, mas as pessoas ainda têm dúvidas (“como funciona?”, “qual benefício?”) ou a página não está com a identidade da clínica. Você quer melhorar a conversão e reduzir perguntas.

## Objetivo
Deixar a página pública clara e confiável: texto simples, FAQ que antecipa dúvidas e visual alinhado com a clínica.

## Quando usar
- Quando a clínica quer alinhar a página com a identidade visual.
- Quando precisa ajustar texto e FAQ para reduzir dúvidas e aumentar conversão.

## Quando NÃO usar
- Toda hora. Defina um texto padrão, ajuste com calma e depois só refine quando tiver feedback real.

## Passo a passo detalhado
1. Acesse **Indicações → Ajuste da página**.
2. Em **Logo**:
   - Clique em **Enviar imagem** para enviar o arquivo.
   - (Opcional) Remova a logo.
3. Em **Título e descrição**:
   - Ajuste os textos conforme a comunicação desejada.
4. Em **Perguntas frequentes**:
   - Edite título/descrição.
   - Adicione/remova itens (pergunta e resposta).
5. Em **Cores**:
   - Escolha uma paleta (preset).
6. Clique em **Salvar configuração**.
7. Verifique a pré-visualização ao lado (quando disponível) para validar o resultado.
8. **Checkpoint**: ao abrir a página pública, ela mostra a logo/textos/FAQ atualizados.

## Campos envolvidos
- **Logo**: upload de imagem (`accept="image/*"`)
- **Título** (texto)
- **Descrição** (textarea)
- **FAQ**:
  - Título (texto)
  - Descrição (textarea)
  - Itens: pergunta (texto) e resposta (textarea)
- **Cores**: seleção de preset (aplica `corFundo` e `corTexto`)

## Regras de negócio
- Validações principais (exemplos):
  - Campos de texto têm limites de tamanho (min/max).
  - Itens do FAQ vazios são filtrados ao salvar (só salva pares pergunta+resposta preenchidos).
- Upload de logo:
  - Sucesso: “Logo enviada”
  - Erro: “Erro ao enviar imagem”
- Salvar configuração:
  - Sucesso: “Configuração salva”
  - Erro: “Erro ao salvar configuração”

## Possíveis erros e como resolver
- **Erro ao enviar imagem**:
  - Solução: tente outro arquivo (tamanho/formato) e repita.
- **Erro ao salvar configuração**:
  - Solução: revise campos obrigatórios e tente novamente.

## Resultado esperado
A página pública passa a refletir a configuração salva, melhorando experiência e conversão do programa de indicação.

## Observações importantes
- No momento, a configuração é “uma página por clínica” (conforme descrição da tela).

## Apêndice técnico (para suporte)
- Itens de FAQ vazios podem não ser salvos (o sistema pode filtrar pergunta+resposta vazios).
