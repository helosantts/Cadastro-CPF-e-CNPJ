print("Bem-Vindo à plataforma da academia Stard Strong! \n")
while True:
  #solicitação dos dados do usuário
  nome = input("Digite seu nome completo:")
  cpf = input("Digite seu CPF:")
  email = input("Digite seu email:")
  senha = input("Crie uma senha:")

  # Exibição dos dados cadastrados
  print("\n CADASTRO REALIZADO COM SUCESSO!")
  print("nome", nome)
  print("CPf", cpf)
  print("E-mail:", email)

  # Pergunta se o usuário deseja continuar ou sair
  continuar = input("\nDigite '1' para cadastrar outro usuário ou  '3'para sair:")
  if continuar != "1":
    break # sai do loop


print("\ncadastro finalizado. Obrigado por se cadastrar na nossa plataforma!")
