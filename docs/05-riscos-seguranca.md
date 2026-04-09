# Riscos de Segurança

## Risco 1: Autenticação (Login/Sessão)
**Cenário**: Ataque de força bruta para descobrir senhas de usuários.  
**Impacto**: Acesso não autorizado a contas, potencial roubo de dados pessoais.  
**Mitigação**: Bloquear conta após 5 tentativas falhidas e implementar CAPTCHA.

## Risco 2: Autorização (Acesso Indevido)
**Cenário**: Usuário com perfil Participante tenta acessar funções de Admin.  
**Impacto**: Alteração indevida de eventos ou dados, comprometendo integridade do sistema.  
**Mitigação**: Verificar permissões em cada ação e usar sessões com timeout.

## Risco 3: Dados (Vazamento/Exposição)
**Cenário**: Banco de dados exposto devido a configuração incorreta.  
**Impacto**: Exposição de informações pessoais de participantes e organizadores.  
**Mitigação**: Criptografar dados sensíveis e realizar backups seguros.