Plano de Teste – Tela de Login

1. Objetivo
Validar que o sistema permite que usuários autenticados acessem a aplicação com segurança, garantindo comportamento correto nos fluxos de login válidos, inválidos e exceções.
________________________________________
2. Escopo
•	Validação dos Campos de entrada (usuário/e-mail e senha)
•	Validação do Botão “Entrar”
•	Recuperação de senha
•	Validações de formato e campos obrigatórios
•	Mensagens de erro
•	Segurança básica – Regras de bloqueio
•	Desempenho/UX
________________________________________
3. Requisitos Funcionais
•	O usuário deve informar e-mail ou username válido.
•	O usuário deve informar senha válida.
•	O sistema deve validar credenciais e permitir acesso apenas se forem corretas.
•	O sistema deve mostrar mensagens de erro adequadas em caso de falhas.
•	O botão Entrar deve ficar desabilitado enquanto campos obrigatórios estiverem vazios.
•	Deve existir link de “Esqueci minha senha”.
•	O sistema deve bloquear após X tentativas inválidas (se existir essa regra).
________________________________________
4. Tipos de Testes
•	Testes Funcionais
•	Testes de Validação
•	Testes de UX/UI
•	Testes de Segurança (básico)
•	Testes de Fluxo Alternativo
•	Testes de Erro e Mensagens
•	Testes de Limite
________________________________________
5. Critérios de Aceite
•	100% dos testes críticos aprovados (login, senha incorreta, bloqueio)
•	Nenhum bug blocker pendente
•	Mensagens adequadas e consistentes
•	Autenticação funcionando para usuário válido
________________________________________
6. Ambiente de Testes
•	URL: [definir]
•	Banco: [dev / staging]
•	Navegadores: Chrome, Edge, Firefox, Safari (mínimo)
•	API/Backend: versão [X]
•	Frontend: versão [Y]
________________________________________
7. Riscos
•	Alterações de API durante o teste
•	Instabilidade do ambiente
•	Regras de negócios incompletas

