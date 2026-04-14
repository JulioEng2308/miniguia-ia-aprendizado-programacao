# 🤖 Miniguia: Aprendendo Inteligência Artificial com Python

## 📌 Sobre o Projeto

Este repositório foi desenvolvido como parte de um desafio prático da DIO, com o objetivo de explorar o uso da Inteligência Artificial como ferramenta de aprendizado ativo, utilizando Python como principal linguagem.

---

## 🎯 Objetivos

- Compreender os conceitos básicos de Inteligência Artificial
- Aprender como utilizar Python para aplicações em IA
- Explorar bibliotecas importantes
- Utilizar IA para auxiliar no aprendizado

---

## 📚 Curadoria de Fontes

- https://www.python.org/
- https://scikit-learn.org/stable/
- https://www.tensorflow.org/
- https://www.kaggle.com/learn/intro-to-machine-learning
- https://www.freecodecamp.org/

---

## 🤖 Engenharia de Prompts

### Prompts utilizados:

- "Explique o que é Inteligência Artificial"
- "O que é Machine Learning?"
- "Me mostre exemplos de IA em Python"

---

## 📘 Miniguia de Estudo

### 📌 Resumo

- IA permite que máquinas aprendam
- Python é a principal linguagem usada em IA
- Machine Learning é um tipo de IA

---

### 📖 Glossário

- IA: Inteligência Artificial  
- Machine Learning: aprendizado com dados  
- Modelo: algoritmo treinado  

---

## 💻 Exemplo em Python

```python
from sklearn.linear_model import LinearRegression
import numpy as np

X = np.array([[1], [2], [3]])
y = np.array([2, 4, 6])

modelo = LinearRegression()
modelo.fit(X, y)

print(modelo.predict([[4]]))
