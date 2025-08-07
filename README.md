# Detecção de Comportamento de Direção Anormal com Machine Learning e Deep Learning

Este repositório contém o código-fonte, resultados e análises do miniprojeto de Inteligência Artificial da Universidade Católica de Pernambuco (UNICAP), desenvolvido no semestre 2025.1. O projeto tem como objetivo aplicar técnicas de Machine Learning e Deep Learning para detectar comportamentos de direção anormais a partir do conjunto de dados UAH-DriveSet.

A proposta foi baseada no artigo científico “Abnormal Driving Behavior Detection: A Machine and Deep Learning Based Hybrid Model” (Uddin et al., 2025), com adaptações para execução em ambiente computacional acadêmico.

## Autor

- Maria Clara Soares  

**Orientador:** Prof. Francisco Madeiro

## Artigo de Referência

**Título:** Abnormal Driving Behavior Detection: A Machine and Deep Learning Based Hybrid Model  
**Autores:** Md. Ashraf Uddin et al.  
**Publicado em:** International Journal of Intelligent Transportation Systems Research  
**Ano:** 2025  
**DOI:** https://doi.org/10.1007/s13177-025-00471-2

## Tecnologias e Bibliotecas

- Python 3.10  
- Pandas, NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib, Seaborn

## Modelos Utilizados

**Machine Learning:**
- Random Forest
- Gradient Boosting
- Support Vector Machine (RBF)
- K-Nearest Neighbors
- Decision Tree
- Logistic Regression

**Deep Learning:**
- CNN Base (desenvolvida do zero)
- ResNet50 (pré-treinada com fine-tuning)
- EfficientNetB6 (não treinada por limitação computacional)

## Resultados

- O modelo Random Forest obteve o melhor desempenho geral, com acurácia de aproximadamente 67%.
- A CNN Base, embora funcional, apresentou acurácia inferior (57%) e viés para a classe majoritária.
- O treinamento da ResNet50 foi interrompido na segunda época por inviabilidade de tempo em CPU, mesmo após diversas otimizações.

## Considerações Técnicas

- Todas as execuções foram realizadas em ambiente local com CPU (Intel i3, 8 GB RAM), sem acesso a GPU.
- O conjunto de dados de imagens foi reduzido em aproximadamente 50% para viabilizar o treinamento dos modelos de Deep Learning.
- Todas as adaptações feitas no código foram documentadas e justificadas no relatório final.

---
## Link para DataSet!
https://drive.google.com/drive/folders/1SWqoTEbu9_8MnbO6_Zx_5gXnh8R-D0s-?usp=sharing
## Licença

Este repositório tem fins exclusivamente acadêmicos. O uso dos dados, códigos e análises deve citar o artigo original como referência primária.

