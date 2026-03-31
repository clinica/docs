# Ação: gerar link do formulário de indicação (clínica ou paciente)

## Cenário real
Você quer divulgar o programa na recepção, no pós-consulta ou por mensagem, e precisa de um link pronto para a pessoa indicar com poucos cliques.

## Objetivo
Gerar um link (e, quando existir, QR Code) do formulário de indicação — padrão da clínica ou personalizado para atribuir a indicação ao paciente indicador.

## Quando usar
- Quando você quer divulgar o programa de indicações em redes sociais, recepção ou pós-consulta.
- Quando um paciente quer indicar amigos e você quer atribuir corretamente ao paciente indicador.

## Quando NÃO usar
- Se a clínica ainda não configurou a URL base do programa (a tela vai avisar). Primeiro configure, depois gere o link.

## Passo a passo detalhado
1. Acesse **Indicações → Formulário**.
2. Se quiser um link personalizado:
   1. Pesquise um paciente no bloco “Pesquisar cliente”.
   2. Copie/compartilhe o link e/ou QR Code gerado.
3. Se quiser o link padrão da clínica:
   1. Use o bloco do formulário da clínica e copie/compartilhe o link disponível.
4. **Checkpoint**: ao abrir o link em outra aba/celular, o formulário carrega.

## Campos envolvidos
- **Pesquisa de paciente**: seletor/pesquisa para escolher o paciente indicador.
- **Link/QR**: informações geradas a partir da base URL configurada.

## Regras do trabalho (para converter mais)
- Link da clínica: bom para divulgar em cartaz/QR na recepção.
- Link do paciente: bom para atribuir corretamente (ex.: paciente “embaixador”).

## Possíveis erros e como resolver
- **“A URL de indicações não está configurada.”**:
  - Solução: configurar `VITE_ENDPOINT_INDICACOES` no ambiente da aplicação.

## Resultado esperado
Você obtém um link (e eventualmente QR Code) pronto para ser enviado ao paciente ou divulgado em canais da clínica.

## Observações importantes
- O link personalizado melhora rastreabilidade porque vincula indicações ao paciente indicador.

## Apêndice técnico (para suporte)
- Sem a variável `VITE_ENDPOINT_INDICACOES` configurada, a tela pode informar que a URL não está configurada.
