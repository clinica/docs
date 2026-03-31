# Ação: ativar ou desativar recursos

## Cenário real
Um módulo sumiu da sidebar (ou apareceu e vocês não usam). Você precisa ajustar para a clínica trabalhar com o que faz sentido, sem confusão.

## Objetivo
Ativar/desativar recursos opcionais para que a operação fique alinhada com a rotina da clínica.

## Quando usar
- Ao iniciar o uso de um recurso (ex.: Imunoterapia, Pesquisa de satisfação).
- Quando quer esconder um módulo que não será usado pela clínica.

## Passo a passo detalhado
1. Acesse **Ajustes → Recursos**.
2. Em cada card, leia a descrição do recurso.
3. Ative/desative conforme necessidade:
   - Agenda de Imunoterapia
   - Pesquisa de Satisfação
   - Programa de indicações (pode ter controles próprios na seção)
4. Aguarde o toast de confirmação.
5. **Checkpoint**: ao voltar para a sidebar, o módulo aparece (ou some) conforme o toggle.

## Campos envolvidos
- Toggles (`Switch`) por recurso.

## Regras de negócio
- Ao ativar/desativar:
  - O sistema atualiza a configuração da clínica.
  - Recarrega a configuração de sessão.
  - Exibe uma mensagem de sucesso (ex.: “Pesquisa de satisfação ativada/desativada”).

## Possíveis erros e como resolver
- **“Erro ao atualizar configuração”**:
  - Solução: tente novamente; se persistir, recarregue e repita.

## Resultado esperado
O recurso fica disponível (ou indisponível) para a clínica, inclusive em menus e rotas.

## Observações importantes
- Se você desativar um recurso, telas relacionadas podem deixar de aparecer na sidebar.

## Apêndice técnico (para suporte)
- Após alterar, pode ser necessário recarregar a tela para ver menus atualizados em alguns casos.
