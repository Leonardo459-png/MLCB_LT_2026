--- RESULTADOS DO LAB 01 ---
Mensagem: 'Quero consultar quanto dinheiro tenho' ==> Intenção Predita: [fazer_pix]
Mensagem: 'Pode me ajudar a fazer um pix?' ==> Intenção Predita: [fazer_pix]
Mensagem: 'Gostaria de cancelar meu cartão de crédito' ==> Intenção Predita: [cancelar_conta]

# 1 - Os dois primeiros resultados estão corretos. O terceiro está incorreto, pois a mensagem fala em cancelar o cartão, e não a conta.
# 2 - Adicionar mais exemplos ao dataset, principalmente uma categoria específica para cancelar_cartao.
# 3 - A LogisticRegression é o modelo que aprende com os exemplos e classifica novas mensagens de acordo com a intenção mais provável.
