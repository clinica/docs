# Ação: buscar e filtrar pacientes

## Cenário real
Você precisa achar um paciente rápido para agendar, confirmar dados, abrir prontuário ou resolver duplicidade — e não pode perder tempo rolando lista.

## Objetivo
Encontrar o paciente certo usando pesquisa e filtros, sem ficar preso em “nenhum resultado”.

## Quando usar
- Quando você precisa localizar um paciente para editar cadastro ou abrir prontuário.
- Quando quer montar listas operacionais (ex.: pacientes com retorno, pacientes com agendamento em determinada data).

## Quando NÃO usar
- Quando você já sabe exatamente quem é e tem acesso por outro caminho (ex.: veio pelo agendamento do dia).

## Passo a passo detalhado
1. Acesse **Pacientes**.
2. Use a **caixa de pesquisa** para buscar por nome/termo.
3. Se não encontrar, use filtros (um de cada vez):
   - **Começa com** (alfabeto)
   - **Com agendamento em** (evento)
   - **Com lembrete de retorno**
   - **Agenda**, **Etiquetas**, **Convênio**
   - **Ordenar por**
4. Observe a lista paginada e refine filtros até encontrar o paciente.
5. **Checkpoint**: ao clicar no paciente, você abre o cadastro/prontuário correto.

## Campos envolvidos
- **Pesquisa**: campo de texto.
- **Filtros**: seletores/itens interativos em acordeões.
- **Paginação**: controles para navegar entre páginas.

## Regras do trabalho (para não “sumir” paciente)
- Se der **nenhum resultado**, remova filtros até voltar a aparecer alguém.
- Evite combinar muitos filtros de uma vez até ter certeza do que está ativo.

## Possíveis erros e como resolver
- **Nenhum resultado**:
  - Solução: remova filtros um a um e tente novamente.
- **Resultados inesperados**:
  - Solução: confirme se algum filtro ficou marcado sem você perceber; limpe e tente de novo.

## Resultado esperado
Você encontra o paciente desejado e consegue seguir para editar cadastro, agendar ou abrir prontuário.

## Observações importantes
- Alguns filtros podem depender de dados de outros módulos (agenda/etiquetas/convenios).

## Apêndice técnico (para suporte)
- Alguns filtros podem persistir conforme estado do sistema e impactar buscas futuras.
