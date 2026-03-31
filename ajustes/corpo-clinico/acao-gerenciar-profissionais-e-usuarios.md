# Ação: gerenciar profissionais e usuários

## Descrição da ação
Adicionar e administrar pessoas que acessam o sistema, separando:
- **Profissionais** (atendimento)
- **Usuários** (não profissionais)

## Quando usar
- Ao contratar/incluir alguém na equipe.
- Ao ajustar acesso/permissões.

## Passo a passo detalhado
1. Acesse **Ajustes → Corpo Clínico**.
2. Em **Profissionais**:
   - Clique em **Novo** para adicionar.
   - Use a lista para manter/gerenciar existentes.
3. Em **Usuários**:
   - Clique em **Novo** para adicionar.
   - Use a lista para manter/gerenciar existentes.

## Campos envolvidos
Dependem dos diálogos e listas:
- `ProfissionalAddDialog` / `ProfissionalLista`
- `UsuarioAddDialog` / `UsuarioLista`

## Regras de negócio
- Profissionais costumam ter acesso a módulos como Atendimento e Prontuário.
- Usuários não profissionais podem ter acesso restrito (depende da configuração de permissões).

## Possíveis erros e como resolver
- **Não consigo adicionar**:
  - Solução: confirme se seu perfil tem permissão administrativa.

## Resultado esperado
Equipe fica cadastrada e com acesso adequado ao sistema.
