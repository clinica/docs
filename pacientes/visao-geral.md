# Pacientes

## Objetivo
Manter o “coração do consultório” organizado: cadastro, contato e histórico do paciente. É daqui que você **acha a pessoa certa**, **atualiza dados** e abre o **prontuário** para atender com segurança.

## Para quem é (na prática)
- **Médico/profissional**: abrir prontuário rápido, revisar histórico e registrar consulta.
- **Secretária/recepção**: cadastrar, corrigir telefone, evitar duplicidade, organizar filtros.
- **Gestor**: qualidade da base (sem duplicidade) e processos consistentes.

## Principais benefícios
- **Menos erro no dia a dia**: telefone certo, nome certo, paciente certo.
- **Atendimento mais fluido**: prontuário abre no contexto correto.
- **Menos retrabalho**: mesclagem resolve duplicidade em vez de “manter dois cadastros”.

## Como essa área entra no seu dia (mini-fluxo)
1. Paciente novo → você cadastra.
2. Paciente antigo mudou contato → você atualiza.
3. Hora de atender → você abre o prontuário pelo paciente.
4. Duplicidade apareceu → você mescla e evita bagunça no histórico.

## Ações disponíveis neste grupo
- [`acao-criar-novo-paciente.md`](acao-criar-novo-paciente.md)
- [`acao-buscar-e-filtrar-pacientes.md`](acao-buscar-e-filtrar-pacientes.md)
- [`acao-editar-cadastro-do-paciente.md`](acao-editar-cadastro-do-paciente.md)
- [`acao-abrir-prontuario-do-paciente.md`](acao-abrir-prontuario-do-paciente.md)
- [`acao-mesclar-cadastros-de-pacientes.md`](acao-mesclar-cadastros-de-pacientes.md)
- [`acao-ver-aniversariantes.md`](acao-ver-aniversariantes.md)

## Impacto no sistema como um todo
Dados de paciente bem mantidos reduzem erros em todos os módulos: agenda, atendimento/prontuário e comunicação com o paciente (mensagens e lembretes, quando usados).

## Observações importantes
- Se você não encontra um paciente, quase sempre é filtro/pesquisa: limpe filtros e tente por variações do nome ou telefone.

## Apêndice técnico (para suporte)
- A rota base do módulo costuma ser `/paciente` (singular).
