### CDU001 – Cadastrar Usuário
*Descrição:* Permite que um novo usuário crie uma conta na plataforma.  
*Atores:* Usuário  
*Pré-condição:* O usuário não deve estar registrado no sistema.  
*Fluxo Principal:*
1. Usuário acessa a tela de cadastro.
2. Preenche os dados obrigatórios (nome, e-mail, senha).
3. Confirma o cadastro.
4. Sistema valida os dados e cria a conta.
5. Exibe mensagem de sucesso.

### CDU002 – Realizar Login
*Descrição:* Permite que usuários registrados acessem suas contas.  
*Atores:* Usuário  
*Pré-condição:* Conta já registrada no sistema.  
*Fluxo Principal:*
1. Usuário informa e-mail e senha.
2. Sistema valida as credenciais.
3. Em caso de sucesso, redireciona para a tela principal.

### CDU003 – Criar Horário de Estudo
*Descrição:* Permite criar e personalizar horários de estudo conforme a rotina do usuário.  
*Atores:* Usuário  
*Pré-condição:* Usuário logado.  
*Fluxo Principal:*
1. Usuário acessa a função "Novo Horário".
2. Define os dias da semana, matérias e horários.
3. Salva a programação.
4. Sistema armazena e exibe no painel principal.
