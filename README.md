# Modelo-preditivo-de-desgaste-de-ferramenta
Modelo em Python para prever o desgaste de ferramentas de corte (Vb) em processos de usinagem, usando aprendizado de máquina supervisionado e semi-supervisionado. Inclui otimização de hiperparâmetros, pseudo-rotulagem e comparação entre Random Forest, Gradient Boosting e KNN.

Modelo Preditivo de Desgaste de Ferramentas de Corte (Vb)

Este repositório contém o código desenvolvido para o estudo sobre **previsão da vida útil de ferramentas de usinagem** utilizando aprendizado de máquina semi-supervisionado**.  
O projeto tem como objetivo investigar o impacto da quantidade de dados rotulados no desempenho de modelos preditivos aplicados à estimativa do desgaste da ferramenta (Vb), considerando a dificuldade de coleta de dados em ambientes produtivos.

---

Funcionalidades principais

- Leitura e tratamento de dados experimentais de usinagem;  
- Otimização de hiperparâmetros com **validação cruzada (K-Fold)** e **RandomizedSearchCV**;  
- Implementação de abordagem **semi-supervisionada** com pseudo-rotulagem;  
- Comparação de desempenho entre diferentes modelos:  
  - Random Forest  
  - Gradient Boosting  
  - K-Nearest Neighbors (KNN)  
- Geração de **tabelas e gráficos** de desempenho (R² e RMSE) em função da porcentagem de dados rotulados.  

---

Base de dados utilizada

O conjunto de dados utilizado neste trabalho foi obtido a partir do estudo:

> DE BARRENA, T. F.; FERRANDO, J. L.; GARCÍA, A. *et al.*  
> *Tool remaining useful life prediction using bidirectional recurrent neural networks (BRNN).*  
> *International Journal of Advanced Manufacturing Technology*, v. 125, p. 4027–4045, 2023.  
> Disponível em: <https://doi.org/10.1007/s00170-023-10811-9>.  
> Acesso em: 2 ago. 2025.

Este dataset apresenta medições de desgaste de ferramentas (Vb) e variáveis de força de corte, coletadas experimentalmente em diferentes condições de operação.

---

Tecnologias utilizadas

- **Python 3.10+**  
- **pandas** – manipulação e análise de dados  
- **numpy** – cálculos numéricos  
- **matplotlib** – visualização de gráficos  
- **scikit-learn** – modelagem e otimização de algoritmos  
- **scipy** – distribuição estatística para Random Search  

---
