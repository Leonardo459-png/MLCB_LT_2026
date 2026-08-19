--- RESULTADOS DO LAB 01 ---
Mensagem: 'Quero consultar quanto dinheiro tenho' ==> Intenção Predita: [fazer_pix]
Mensagem: 'Pode me ajudar a fazer um pix?' ==> Intenção Predita: [fazer_pix]
Mensagem: 'Gostaria de cancelar meu cartão de crédito' ==> Intenção Predita: [cancelar_conta]

# 1 - Os dois primeiros resultados estão corretos. O terceiro está incorreto, pois a mensagem fala em cancelar o cartão, e não a conta.
# 2 - Adicionar mais exemplos ao dataset, principalmente uma categoria específica para cancelar_cartao.
# 3 - A LogisticRegression é o modelo que aprende com os exemplos e classifica novas mensagens de acordo com a intenção mais provável.


--- RESULTADOS DO LAB 02 ---
Mensagem de Teste: 'Gostaria de devolver o produto que comprei'
Intenção Predita: troca_devolucao

--- Distribuição de Probabilidades por Classe ---
Classe [duvida_frete]: 27.99%
Classe [rastrear_pedido]: 24.54%
Classe [troca_devolucao]: 47.46%

# 1 - Sim. A mensagem foi correta e classificada como troca_devolucao.
# 2 - Adicionar mais exemplos ao dataset para aumentar a precisão do modelo.
# 3 - O Naive Bayes calcula a probabilidade de uma mensagem pertencer a cada intenção e escolhe a classe com maior probabilidade.

