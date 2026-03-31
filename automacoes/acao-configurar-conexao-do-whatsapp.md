# Ação: configurar conexão do WhatsApp

## Cenário real
Você ativou automações, mas nada está sendo enviado. Na maioria das vezes, é porque o WhatsApp não está conectado (ou caiu).

## Objetivo
Conectar o WhatsApp para que confirmações, lembretes e outros envios automáticos funcionem.

## Quando usar
- Quando a clínica vai habilitar automações pela primeira vez.
- Quando precisa reconectar o WhatsApp após expiração/desconexão.

## Quando NÃO usar
- Se o WhatsApp já está conectado e enviando normalmente. Nesse caso, só acompanhe.

## Passo a passo detalhado
1. Acesse **Automações → Conexão**.
2. Verifique a lista de conexões existentes.
3. Se não houver nenhuma conexão:
   1. Use o card de **iniciar nova conexão**.
   2. Siga as instruções de pareamento exibidas.
4. Confirme que a conexão aparece como ativa.
5. **Checkpoint**: a conexão aparece como ativa e as automações deixam de falhar por “sem conexão”.

## Campos envolvidos
Depende dos cards de conexão:
- Lista de instâncias/conexões
- Ações de iniciar/conectar

## Regras de negócio
- O card de “nova conexão” só aparece quando **não existe** instância na lista.

## Possíveis erros e como resolver
- **Conexão não inicia**:
  - Solução: recarregue e tente novamente; valide rede e permissões.

## Resultado esperado
O WhatsApp fica conectado e pronto para que automações enviem mensagens.

## Observações importantes
- Se o WhatsApp estiver desconectado, as automações podem não conseguir enviar mensagens.

## Apêndice técnico (para suporte)
- O card de “nova conexão” pode aparecer apenas quando não existe instância na lista.
