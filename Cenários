Cenários em Gherkin (BDD)
________________________________________
📌 Feature: Autenticação de Usuário – Tela de Login
Feature: Login do usuário
  Como um usuário registrado
  Quero acessar o sistema através da tela de login
  Para utilizar as funcionalidades disponíveis
  
    Dado que estou na tela de login
________________________________________
✔ Cenário 1 – Login com credenciais válidas

  Quando informo o e-mail "usuario@teste.com"
  E a senha "SenhaCorreta123"
  E clico no botão "Entrar"
  Então devo ser autenticado com sucesso
  E devo visualizar a página inicial do sistema
________________________________________
❌ Cenário 2 –  Login com senha incorreta

  Quando informo o e-mail "usuario@teste.com"
  E a senha "SenhaErrada"
  E clico no botão "Entrar"
  Então devo visualizar a mensagem "Credenciais inválidas"
  E devo permanecer na tela de login
________________________________________
❌ Cenário 3 – Login com e-mail em formato inválido

  Quando informo o e-mail "usuario-sem-arroba"
  E informo a senha "Senha123"
  E clico no botão "Entrar"
  Então devo visualizar a mensagem "Credenciais inválidas"
________________________________________
⚠ Cenário 4 – Campos obrigatórios
Cenário: Tentativa de login com campos vazios
  Quando clico no botão "Entrar"
  Então devo visualizar a mensagem "Preencha todos os campos obrigatórios"
________________________________________
❌ Cenário 5 – Usuário inexistente

  Quando informo o e-mail "inexistente@teste.com"
  E informo a senha "Senha123"
  E clico no botão "Entrar"
  Então devo visualizar a mensagem "Usuário não encontrado"
________________________________________
🔄 Cenário 6 – Recuperação de senha

  Quando clico no link "Esqueci minha senha"
  E informo o e-mail "usuario@teste.com"
  E clico em "Enviar"
  Então devo visualizar a mensagem "Enviamos instruções para o seu e-mail"
________________________________________
🔒 Cenário 7 – Múltiplas tentativas inválidas
cenário: Bloqueio após várias tentativas
  Dado que já realizei 4 tentativas inválidas
  Quando informo e-mail "usuario@teste.com"
  E informo senha "SenhaErrada"
  E clico no botão "Entrar"
  Então devo visualizar a mensagem "Conta temporariamente bloqueada"
________________________________________
🔐 Cenário 8 – Segurança do campo senha
cenário: Visualização da senha protegida
  Quando informo a senha "Senha123"
  Então o campo deve exibir caracteres mascarados

