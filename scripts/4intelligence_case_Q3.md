# 4intelligence - Business Case

# Questão 3:

### A métrica utilizada para a seleção do modelo foi o erro médio absoluto. Diante disso, os 5 melhores modelos em ordem de melhor _performance_ para pior:

## 1 - XGBoost - Gradient Descent

Selecionei esse modelo pela sua alta capacidade de diminuição do erro, por ser a combinação de árvores de decisão com a descida do gradiente, esse modelo tem performado muito bem e ganho diversas competições no Kaggle. Porém, tem que tomar cuidado com o overfitting.

## 2 - Random Forest

Visto que Random Forest é um modelo bastante robusto para a presença de _outliers_, decidi experimentá-lo, principalmente observando, como já mencionado, a aleatoriedade da tendência principal da variável alvo.

## 3 - Linear Regression

Observei que diversas variáveis tinham alto coeficiente de correlação com a variável predita, por isso decidi experimentar um modelo linear e analisar a _performance_.

## 4 - ElasticNet

Experimentei pelo mesmo motivo do modelo anterior.

## 5 - SVR

Testei esse modelo por já ter usado em outras situações e ter percebido bastante potencial.


