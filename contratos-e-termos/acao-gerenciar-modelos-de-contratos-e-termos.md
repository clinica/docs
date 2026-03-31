# Ação: gerenciar modelos de contratos e termos

## Cenário real
Você quer parar de usar “um termo diferente para cada paciente” e precisa ter modelos aprovados, prontos para enviar quando necessário.

## Objetivo
Criar e manter modelos de documentos e acompanhar se estão aceitos para envio, evitando enviar documento errado ou não aprovado.

## Quando usar
- Quando precisa adicionar um novo modelo de documento.
- Quando quer verificar se um modelo está “aceito” para envio.
- Quando deseja arquivar um modelo antigo.

## Quando NÃO usar
- Quando você só precisa reenviar um documento específico para um paciente. Nesse caso, use o fluxo de envio (se disponível) e acompanhe no histórico.

## Passo a passo detalhado
1. Acesse **Contratos e Termos → Modelos**.
2. Clique em **Adicionar** para criar um novo modelo.
3. Na lista de modelos:
   - Veja **Nome**, **Status** e **Adicionado em**.
   - Para um modelo aceito, clique em **Enviar**.
   - Para remover da operação, use **Arquivar**.
4. **Checkpoint**: o modelo aparece com status e fica claro se pode enviar.

## Campos envolvidos
Na listagem:
- **Nome**
- **Status** (aceito / em análise / rejeitado)
- **Data de criação**
- **Ações**: enviar, arquivar

## Regras do trabalho (para não errar)
- Só envie quando estiver **aceito**.
- Se estiver em análise/rejeitado, ajuste o modelo e aguarde o aceite.

## Possíveis erros e como resolver
- **Não consigo enviar**:
  - O modelo pode estar em análise ou rejeitado.
  - Solução: aguarde aceitação/aprovação ou crie/ajuste o modelo.
- **Lista não carrega**:
  - Solução: recarregue a página.

## Resultado esperado
Você mantém um catálogo de modelos prontos para envio e consegue controlar ciclo de vida (ativo vs arquivado).

## Observações importantes
- O fluxo completo de “Enviar” pode envolver integração e etapas adicionais (assinatura).

## Apêndice técnico (para suporte)
- O botão “Enviar” pode ficar desabilitado conforme status do modelo (ex.: diferente de `aceito`).
