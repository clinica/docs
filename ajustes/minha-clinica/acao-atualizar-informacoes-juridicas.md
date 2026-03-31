# Ação: atualizar informações jurídicas da clínica

## Cenário real
O financeiro não consegue emitir um documento ou percebe que os dados da clínica estão desatualizados (endereço antigo, CNPJ errado, razão social diferente do contrato).

## Objetivo
Manter os dados oficiais da clínica corretos para que cobrança e documentos fiscais saiam sem erro.

## Quando usar
- Ao criar a conta da clínica.
- Quando dados oficiais mudarem (endereço, razão social, regime, etc.).

## Quando NÃO usar
- Para “testar”: altere apenas com dados reais (isso afeta documentos).

## Passo a passo detalhado
1. Acesse **Ajustes → Minha Clínica**.
2. No card “Informações Jurídicas”, preencha/atualize os campos do formulário.
3. Salve e confirme que o sistema manteve os novos dados.
4. **Checkpoint**: ao reabrir a página, os dados permanecem e batem com os documentos oficiais.

## Campos envolvidos
Os campos são fornecidos pelo componente `FormularioJuridicoClinica` e podem incluir:
- Identificação da empresa (CNPJ/razão social)
- Endereço
- Dados complementares fiscais

## Regras de negócio
- Os dados impactam rotinas financeiras (boletos e NFe).

## Possíveis erros e como resolver
- **Erro ao salvar**:
  - Solução: revise formatação dos campos e tente novamente.

## Resultado esperado
Dados jurídicos ficam atualizados e passam a ser usados corretamente em documentos e integrações financeiras.

## Observações importantes
- Se sua clínica usa emissão de notas fiscais, mantenha esses dados sempre consistentes com a documentação oficial.
