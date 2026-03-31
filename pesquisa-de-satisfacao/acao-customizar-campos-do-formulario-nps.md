# Ação: customizar campos do formulário NPS

## Cenário real
Você quer mudar a linguagem para o jeito da clínica (mais humano, mais curto) ou adicionar uma pergunta de comentário para entender melhor as notas baixas.

## Objetivo
Ajustar o formulário que será enviado no futuro, para melhorar taxa de resposta e qualidade do feedback.

## Quando usar
- Quando a clínica quer mudar o texto/pergunta, adicionar campos de comentário ou adequar o formulário à linguagem do time.
- Quando deseja evoluir o formulário ao longo do tempo.

## Quando NÃO usar
- Para tentar “mudar” respostas antigas: mudanças valem para próximos envios.

## Passo a passo detalhado
1. Abra uma pesquisa específica em **Pesquisa de satisfação**.
2. Clique na aba **Customizar campos**.
3. Leia o card de orientação sobre o “molde”/snapshot do envio.
4. Use o editor de formulário para ajustar o modelo (quando disponível).
5. Salve as alterações no editor.
6. **Checkpoint**: ao copiar/abrir um novo link depois, o formulário aparece com o texto atualizado.

## Campos envolvidos
Depende do editor de formulários (`FormularioEditor`), mas em geral:
- Campos do formulário NPS (perguntas, textos, opções)
- Configurações do modelo

## Regras do trabalho (para não confundir a equipe)
- Combine um texto padrão e evite mudar toda semana.
- Se quer comparar antes/depois, faça mudanças em períodos e acompanhe as respostas.

## Possíveis erros e como resolver
- **Editor não aparece**:
  - Pode indicar `formularioHash` inválido.
  - Solução: volte para a lista e abra a pesquisa correta.

## Resultado esperado
O formulário NPS passa a refletir o modelo atualizado para futuros envios/links.

## Observações importantes
- Mudanças no modelo não alteram retroativamente envios já respondidos (por design).

## Apêndice técnico (para suporte)
- O “molde” do envio pode ficar congelado após a primeira resposta, por isso alterações não mudam envios antigos.
