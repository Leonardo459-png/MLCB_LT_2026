# - LAB 01 - Carregando modelo morfológico SpaCy (pt_core_news_sm)
Carregando espaço vetorial denso de embeddings modelo GloVe
[==================================================] 100.0% 66.0/66.0MB downloaded
Dataset carregado com 20 mensagens divididas em 4 intenções.
Dimensão da matriz X: (20, 50)
Dimensão do vetor y: (20,)
Modelo supervisionado treinado com Árvore de Decisão!

# - LAB 02 - carregando modelo Spacy...
Carregando GloVe...
Modelos carregados!
Dataset carregado: 20 mensagens
Intenções: 4
Vetores criados!
Formato de X: (20, 50)
Modelo supervisionado treinado!

TESTE DO MODELO

Intenção: comprar_imovel
Confiança: 99.2%
Status: IDENTIFICADO (comprar_imovel) | Confiança: 99.2% | Corte mínimo: 65%

# - LAB 03 - Carregando modelo morfológico Spacy...
Carregando espaço vetorial denso de embeddings GloVe...
Modelos carregados!

DATASET

Dataset carregado com 25 mensagens divididas em 5 intenções.

Quantidade por intenção:
intencao
comprar_imovel          5
alugar_imovel           5
suporte_manutencao      5
2via_boleto_contrato    5
cancelar_contrato       5
Name: count, dtype: int64


VECTORIZATION

Formato de X: (25, 50)
Quantidade de rótulos: 25


TREINAMENTO DO MODELO

Modelo supervisionado treinado!

Classes aprendidas pelo modelo:
- 2via_boleto_contrato
- alugar_imovel
- cancelar_contrato
- comprar_imovel
- suporte_manutencao


TESTE DA NOVA INTENÇÃO

Intenção: cancelar_contrato
Confiança: 92.7%
Status: IDENTIFICADO (cancelar_contrato) | Confiança: 92.7% | Corte mínimo: 65%
