## Título: Mensagem de email incorreto induz ao erro
*[referente ao CT 001]*
## Ambiente: 
**Desktop:** Chrome, Windows 10 Pro
## Descrição: 
Ao inserir o email/código de aluno incorreto, a mensagem informa “você excedeu o limite de senhas incorretas” para o usuário e o campo de senha fica em destaque.
## Pré-condição: 
Ter uma senha válida cadastrada no sistema.
## Passos para reproduzir:
1. Abra o site https://universidade.br/index ou o aplicativo Minha Universidade;
2. Insira o email/código de aluno inválido: email.aluno1@gmail.com ou 111111;
3. Insira a senha válida: Senha*135
## Resultado esperado: 
O acesso é bloqueado e a mensagem “email ou senha incorreto” aparece na tela.
## Resultado obtido: 
O acesso é bloqueado, a mensagem "você excedeu o limite de senha incorretas" é exibida e o campo de senha fica em destaque.
## Severidade: 
Média - não bloqueia o fluxo do software, mas induz o usuário ao erro.
## Evidência: 
