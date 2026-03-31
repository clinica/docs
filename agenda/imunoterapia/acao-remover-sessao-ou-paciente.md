# Ação: remover sessão ou paciente da imunoterapia

## Cenário real
Uma sessão foi cadastrada errada, ou o paciente encerrou o tratamento e você precisa “limpar” o módulo para ele não continuar aparecendo como pendente.

## Objetivo
Remover sessões/pacientes que não fazem mais parte do plano, mantendo a lista de pendências e indicadores coerentes.

## Quando usar
- Quando um paciente encerrou tratamento e não deve mais aparecer.
- Quando uma sessão foi criada incorretamente e precisa ser removida.

## Quando NÃO usar
- Quando a sessão apenas mudou de horário: nesse caso, ajuste a programação (ou cadastre a sessão correta e remova a errada conscientemente).

## Passo a passo detalhado
### Remover paciente
1. Acesse **Imunoterapia → Pacientes**.
2. Localize o paciente.
3. Clique no ícone de remover (lixeira) no cabeçalho do card do paciente.
4. Confirme (se houver confirmação) e aguarde a atualização.

### Remover sessão
1. Acesse **Imunoterapia → Pacientes**.
2. Localize o paciente e a sessão.
3. Clique no ícone de remover (lixeira) ao lado da sessão.
4. Aguarde a atualização.
5. **Checkpoint**: o paciente/sessão desaparece e os números (pendências/progresso) se ajustam.

## Campos envolvidos
Não há campos; são ações diretas.

## Regras do trabalho (para não perder histórico por engano)
- Remover paciente costuma remover todas as sessões dele neste módulo — faça isso apenas quando tiver certeza.
- Se o erro é só uma sessão, remova apenas a sessão.

## Possíveis erros e como resolver
- **Erro ao remover**:
  - Solução: tente novamente; se persistir, recarregue a página e repita.

## Resultado esperado
O paciente e/ou a sessão deixam de aparecer na UI e os indicadores (pendências, progresso) se atualizam.

## Observações importantes
- Remover paciente normalmente remove o conjunto de sessões associado a ele dentro deste módulo.

## Apêndice técnico (para suporte)
- O sistema exibe mensagens de sucesso/erro via toast ao remover paciente ou sessão.
