# Ação: gerenciar indicados (lista completa)

## Cenário real
Chegaram várias indicações e você precisa operar como um “funil”: ligar, registrar status, agendar e converter para paciente quando fechar.

## Objetivo
Trabalhar a lista de indicados com método: encontrar pessoas, atualizar status/observação e transformar em paciente quando fizer sentido.

## Quando usar
- Quando a equipe precisa entrar em contato com indicados e acompanhar resultados.
- Quando você quer localizar rapidamente uma pessoa indicada pelo nome ou telefone.

## Quando NÃO usar
- Para configurar a página e o formulário do programa: use as telas de ajuste e formulário.

## Passo a passo detalhado
1. Acesse **Indicações → Indicados**.
2. Use a caixa de **pesquisa** para buscar por nome ou telefone.
3. Use a paginação para navegar pelos resultados.
4. Para um indicado específico, use as ações disponíveis na linha:
   - **Editar**: abre diálogo para ajustar dados/status/observação.
   - **Converter para paciente**: inicia criação de paciente com dados pré-preenchidos.
   - **Remover**: exclui a indicação (com confirmação).
5. **Checkpoint**: o status reflete o que foi feito (ex.: contatado, agendado, convertido).

## Campos envolvidos
### Pesquisa
- Campo de busca (texto), com debounce (atualiza após pequeno intervalo).

### Colunas da tabela
- Nome
- Telefone
- Indicado em (data/hora)
- Status
- Indicado por
- Observação

## Regras do trabalho (para o funil funcionar)
- Sempre registre uma observação curta do contato (ex.: “liguei, retornou amanhã”, “agendou para 10/04”).
- Atualize status no mesmo dia para o time não duplicar contato.

## Possíveis erros e como resolver
- **Nenhum resultado**:
  - Solução: revise o termo ou limpe a pesquisa.
- **Ações não funcionam**:
  - Pode ser permissão ou falha de rede.
  - Solução: tente novamente; se persistir, contate suporte.

## Resultado esperado
Você consegue operar o funil de indicações em escala: pesquisar, atualizar dados e transformar indicados em pacientes.

## Observações importantes
- Como a busca e paginação ficam na URL, é possível compartilhar um link já filtrado (quando apropriado).

## Apêndice técnico (para suporte)
- “Converter para paciente” pode não aparecer quando o indicado já virou paciente.
