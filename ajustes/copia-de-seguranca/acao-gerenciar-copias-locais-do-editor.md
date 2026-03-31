# Ação: gerenciar cópias locais do editor

## Descrição da ação
Visualizar cópias de segurança locais do editor (prontuário), anexar o conteúdo ao prontuário do paciente (quando possível) e apagar cópias locais.

## Quando usar
- Quando o editor travou/fechou e você precisa recuperar texto que ficou salvo localmente.
- Quando um atendimento foi iniciado mas não foi salvo no prontuário e você precisa anexar o conteúdo.

## Passo a passo detalhado
1. Acesse **Ajustes → Cópias locais**.
2. Se existirem backups, eles aparecem agrupados por data.
3. Para um item:
   - Revise o conteúdo exibido.
   - Se houver paciente identificado na chave e o item não estiver sincronizado:
     1. Clique em **Anexar ao prontuário**.
     2. Aguarde a confirmação.
4. Para apagar uma cópia local:
   1. Clique no ícone de lixeira.
   2. Confirme em “Apagar cópia local”.

## Campos envolvidos
Não há formulário; são ações diretas:
- Anexar ao prontuário
- Apagar cópia local

## Regras de negócio
- Só são listadas chaves do localStorage com prefixo do editor (`cw-editor-v5-longeditor-...`).
- O sistema tenta extrair `pacienteId` a partir da chave para permitir anexar ao prontuário.
- “Presente no prontuário” aparece quando o backup indica que já foi sincronizado (`sync`).

## Possíveis erros e como resolver
- **Nenhuma cópia encontrada**:
  - Solução: confirme se está no mesmo navegador/dispositivo onde o texto foi digitado.
- **Anexar ao prontuário não aparece**:
  - Pode faltar `pacienteId` válido no backup.
  - Solução: procure um backup que contenha referência ao paciente.

## Resultado esperado
Conteúdos locais podem ser recuperados e anexados ao prontuário, reduzindo perda de informação.

## Observações importantes
- Apagar cópia local não remove nada do prontuário já salvo, apenas do navegador.
