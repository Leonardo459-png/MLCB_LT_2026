--- RESULTADOS DO LAB 01 (AULA 03) ---
Mensagem: 'Preciso urgente da segunda via da fatura'
Intenção Predita: [segunda_via]
Vocabulário Filtrado (sem stopwords): ['2a', '2a via', 'aberto', 'acordo', 'acordo pagar', 'alterar', 'alterar endereço', 'app', 'atrasada', 'atualizo', 'atualizo dados', 'boleto', 'cadastramento', 'dados', 'dados residenciais', 'débito', 'débito aberto', 'dívida', 'emitir', 'emitir segunda', 'endereço', 'endereço cadastramento', 'fatura', 'fatura atrasada', 'fazer', 'fazer um', 'gostaria', 'gostaria alterar', 'negociar', 'negociar pagamento', 'no', 'no app', 'onde', 'onde atualizo', 'pagamento', 'pagamento dívida', 'pagar', 'pagar débito', 'posso', 'posso emitir', 'residenciais', 'residenciais no', 'segunda', 'segunda via', 'um', 'um acordo', 'via', 'via boleto', 'via fatura']

# 1 - ele deixar o tamanho menor e geralmente não ajudam a identificar a intenção da mensagem 
# 2 -  `ngram_range=(1, 2)` faz o modelo considerar palavras isoladas (1-gram) e combinações de duas palavras (2-gram), como **“segunda via”**, ajudando a identificar melhor o contexto das mensagens.
# 3 - A remoção de palavras genéricas reduz o **ruído** e faz o modelo focar nas palavras mais importantes da mensagem, diminuindo as chances de uma classificação incorreta.
