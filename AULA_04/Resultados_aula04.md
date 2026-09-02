# - GERADOR SINTÉTICO DE DADOS - SAC MÓVEIS RESIDENCIAIS

 Dataset 'dataset_moveis_100.csv' criado com 100 frases distribuidas em 5 intencoes!

# - Atividade 1: Chatbot Versão 1 (knn)

precision    recall  f1-score   support

logistica_entregas       1.00      1.00      1.00         6
       reclamacoes       1.00      1.00      1.00         6
           suporte       1.00      1.00      1.00         6
 trocas_devolucoes       1.00      1.00      1.00         6
            vendas       1.00      1.00      1.00         6

          accuracy                           1.00        30
         macro avg       1.00      1.00      1.00        30
      weighted avg       1.00      1.00      1.00        30

[[6 0 0 0 0]
 [0 6 0 0 0]
 [0 0 6 0 0]
 [0 0 0 6 0]
 [0 0 0 0 6]]

=== INICIANDO BATERIA DE TESTES (10 INPUTS OBRIGATÓRIOS) ===

[Teste 1/10]
Digite a frase do cliente: vendas
Fallback: encaminhando o cliente para a equipe humana 

# - Atividade 2: Construção do Zero (Versão 2 — Decision Tree e 8 Testes Digitados)

=== MATRIZ DE CONFUSÃO ===
[[4 0 0 0 2]
 [1 4 1 0 0]
 [0 0 6 0 0]
 [0 0 1 5 0]
 [0 0 0 1 5]]

=== RELATÓRIO DE CLASSIFICAÇÃO ===
                    precision    recall  f1-score   support

logistica_entregas       0.80      0.67      0.73         6
       reclamacoes       1.00      0.67      0.80         6
           suporte       0.75      1.00      0.86         6
 trocas_devolucoes       0.83      0.83      0.83         6
            vendas       0.71      0.83      0.77         6

          accuracy                           0.80        30
         macro avg       0.82      0.80      0.80        30
      weighted avg       0.82      0.80      0.80        30


=== INICIANDO BATERIA DE TESTES (8 INPUTS OBRIGATÓRIOS) ===

[Teste 1/8]
Digite a frase do cliente: reclamacoes
Intenção: trocas_devolucoes
Probabilidade: 100.00%


# - Atividade 3: Relatório Comparativo de Modelos

Modelo          Acurácia Geral         F1-Score (Weighted)     Principais Confusões na Matriz

KNN (K=3)       [Inserir Acurácia]     [Inserir F1-Score]      [Ex: Confundiu 'Troca' com 'Cancelamento' e 'Dúvida' com 'Reclamação']

Decision Tree   [Inserir Acurácia]     [Inserir F1-Score]      [Ex: Maior taxa de erro entre 'Status do Pedido' e 'Rastreio']
