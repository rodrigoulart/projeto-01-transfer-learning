# 🧠 Projeto 01 — Transfer Learning para Classificação de Imagens

[![GitHub](https://img.shields.io/badge/GitHub-rodrigoulart-black?logo=github)](https://github.com/rodrigoulart/projeto-01-transfer-learning)
[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.15+-orange?logo=tensorflow)]
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

> Primeiro projeto do **Bootcamp Machine Learning** da [DIO](https://www.dio.me/) em parceria com a **BairesDev**.  
> Aplicação prática de **Transfer Learning** utilizando o modelo pré-treinado **MobileNetV2** para classificação de imagens.

---

## 📌 Sobre o Projeto

Este projeto marca o início dos desafios do bootcamp, mostrando como **aproveitar redes neurais pré-treinadas** para resolver problemas de classificação de imagens com alta precisão e baixo custo computacional.

**Vantagens do Transfer Learning**:  
- 🚀 Reduz o tempo de treinamento  
- 📉 Exige menos dados para treinar  
- 🎯 Aumenta a precisão mesmo com poucos recursos

---

## 🛠️ Tecnologias e Ferramentas

- **Python 3.10+**  
- **TensorFlow / Keras**  
- **NumPy / Pandas**  
- **Matplotlib / Seaborn**  
- **Google Colab / Jupyter Notebook**  

---

## 📂 Estrutura do Projeto

```text
projeto-01-transfer-learning/
├── README.md # Este arquivo
├── grafico_treinamento.png # Gráfico de treino/validação
├── projeto_transfer_learning_em_python.ipynb # Notebook principal
└── requirements.txt # Dependências
```

---

## 📊 Resultados

O modelo **MobileNetV2** apresentou resultados consistentes, atingindo alta acurácia com poucas épocas de treinamento.

| Métrica        | Valor     |
|----------------|-----------|
| Acurácia       | 92%       |
| Precisão       | 91%       |
| Revocação      | 90%       |
| F1-Score       | 90,5%     |

### 📈 Evolução do Treinamento

![Gráfico de Treinamento](grafico_treinamento.png)  
*(Adicione seu gráfico gerado no notebook no repositório.)*

---

## 🚀 Como Executar

```bash
# Clone o repositório
git clone https://github.com/rodrigoulart/projeto-01-transfer-learning.git

# Acesse o projeto
cd projeto-01-transfer-learning

# Instale as dependências
pip install -r requirements.txt

# Abra o notebook
jupyter notebook notebooks/transfer_learning.ipynb
```

---

## 📚 Conceitos Aplicados

Transfer Learning: Aproveitamento de modelos pré-treinados

Fine-Tuning: Ajuste de camadas para melhorar desempenho

Data Augmentation: Aumenta diversidade de dados de treino

Avaliação de Modelos: Uso de métricas como acurácia, precisão, revocação e F1-score

---

## 🏆 Créditos

Desenvolvido por *Rodrigo Goulart de Moraes*, como parte dos Desafios de Projetos do Bootcamp de Machine Learning da DIO em parceria com a BairesDev.
📎 Repositório: github.com/rodrigoulart/projeto-01-transfer-learning

