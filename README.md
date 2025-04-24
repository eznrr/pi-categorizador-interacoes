# 🧠 Categorizador de Interações Terapêuticas com Inteligência Artificial

Este projeto integrador tem como objetivo desenvolver um sistema inteligente capaz de categorizar interações entre terapeutas e pacientes utilizando técnicas de aprendizado de máquina. O sistema é treinado com um banco de dados previamente rotulado, baseado no sistema **SiMCCIT**, e funciona em ambiente local para garantir segurança e confidencialidade dos dados.

## 🔍 Objetivo

Classificar falas de terapeutas e pacientes em categorias pré-definidas com base em uma base de dados real, promovendo o uso de IA na análise e compreensão de interações terapêuticas.

## 🛠 Tecnologias Utilizadas

- **Python** 🐍
- **Scikit-learn** e/ou **PyTorch** (dependendo da abordagem escolhida)
- **Pandas**, **NumPy** para manipulação de dados
- **Jupyter Notebook** para testes e prototipagem
- **Matplotlib** / **Seaborn** para visualização de dados
- Treinamento local (offline)

## 📁 Estrutura do Projeto

```
├── data/                     # Conjunto de dados (limitado e anonimizado)
├── notebooks/                # Jupyter notebooks com experimentos
├── src/                      # Código-fonte do sistema de categorização
├── models/                   # Modelos treinados (salvos em .pkl ou .pt)
├── requirements.txt          # Dependências do projeto
└── README.md                 # Este arquivo
```

## 🧪 Metodologia

1. **Pré-processamento dos dados**  
   Limpeza, tokenização, vetorização das falas.

2. **Divisão dos dados**  
   Separação entre treino, validação e teste (quando possível).

3. **Treinamento do modelo**  
   Modelos testados: Regressão Logística, Random Forest, SVM, e Redes Neurais.

4. **Avaliação**  
   Acurácia, F1-score, matriz de confusão.

## 🔐 Considerações Éticas

Todos os dados utilizados foram anonimizados e manipulados localmente, respeitando os princípios de privacidade e confidencialidade dos envolvidos nas interações terapêuticas.

## 📈 Resultados Esperados

- Classificador funcional para auxiliar pesquisas e futuras aplicações na área clínica.
- Visualizações que facilitem a análise qualitativa dos dados.

## 👥 Equipe

- **Otávio Vieira** – Ciência da Computação  
- **Enzo Rodrigues** – Ciência da Computação 
- **Bruno Isaac** – Ciência da Computação
- **Eduardo Silva** – Ciência da Computação
- **Davi Ribeiro** – Ciência da Computação 

## 🎓 Orientação

- **Professor(a): Walner de Oliveira Pessôa**

## 📌 Status do Projeto

> 🚧 Em desenvolvimento  

---

## 📎 Licença

Este projeto é acadêmico e não deve ser utilizado para fins comerciais. O uso dos dados está restrito ao ambiente local autorizado pelo orientador(a).
