--- RESULTADOS DO LAB 01 (AULA 03) ---
Mensagem: 'Preciso urgente da segunda via da fatura'
Intenção Predita: [segunda_via]
Vocabulário Filtrado (sem stopwords): ['2a', '2a via', 'aberto', 'acordo', 'acordo pagar', 'alterar', 'alterar endereço', 'app', 'atrasada', 'atualizo', 'atualizo dados', 'boleto', 'cadastramento', 'dados', 'dados residenciais', 'débito', 'débito aberto', 'dívida', 'emitir', 'emitir segunda', 'endereço', 'endereço cadastramento', 'fatura', 'fatura atrasada', 'fazer', 'fazer um', 'gostaria', 'gostaria alterar', 'negociar', 'negociar pagamento', 'no', 'no app', 'onde', 'onde atualizo', 'pagamento', 'pagamento dívida', 'pagar', 'pagar débito', 'posso', 'posso emitir', 'residenciais', 'residenciais no', 'segunda', 'segunda via', 'um', 'um acordo', 'via', 'via boleto', 'via fatura']

# 1 - ele deixar o tamanho menor e geralmente não ajudam a identificar a intenção da mensagem 
# 2 -  `ngram_range=(1, 2)` faz o modelo considerar palavras isoladas (1-gram) e combinações de duas palavras (2-gram), como **“segunda via”**, ajudando a identificar melhor o contexto das mensagens.
# 3 - A remoção de palavras genéricas reduz o **ruído** e faz o modelo focar nas palavras mais importantes da mensagem, diminuindo as chances de uma classificação incorreta.


--- RESULTADOS DO LAB 02 (AULA 03) ---

--- Relatório de Classificação ---
                     precision    recall  f1-score   support

horario_atendimento       0.50      1.00      0.67         1
        localizacao       0.00      0.00      0.00         1
    troca_devolucao       0.00      0.00      0.00         1

           accuracy                           0.33         3
          macro avg       0.17      0.33      0.22         3
       weighted avg       0.17      0.33      0.22         3

--- Matriz de Confusão ---
[[1 0 0]
 [1 0 0]
 [0 1 0]]

# 1 - Precision ele mostra previsões se estavam corretamente no modelo. Recall esclarece o casos que o modelo identificaram corretamente.
F1-Score combina precision e recall em uma unica medida
# 2 - A diagonal principal representa as previsões que o modelo identificou. Quanto maior a quantidade de valores na diagonal, melhor fica o seu desempenho do modelo.
# 3 - Porque uma classe com muitos exemplos pode dominar o resultado. O modelo pode ter alta acurácia, mas apresentar um desempenho ruim nas classes com poucos exemplos.

 
--- RESULTADOS DO LAB 03 (AULA 03) ---
Mensagem:
Acuracia via Pipeline: 0.00%

# 2 - A vantagem é organizar e automatizar todas as estapas do nosso modelo.
# 3 - Porque ele tem garantia que as mesmas etapas de pré-processamento sejam automaticamente aplicada no teste para nao ter erro e pequenas diferencas.
