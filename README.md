# Correlation: Linear vs Monotonic Relationships  
# Correlação: Relações Lineares vs Monotônicas

This repository reproduces classic examples of correlation from a well-known reference in environmental statistics.

Este repositório reproduz exemplos clássicos de correlação de uma referência consagrada em estatística ambiental.

---

## 📊 Purpose | Objetivo

This is a **study-oriented repository** created to better understand how different correlation coefficients behave under different types of relationships between variables.

Este é um repositório com foco em **estudo**, criado para compreender melhor como diferentes coeficientes de correlação se comportam sob diferentes tipos de relações entre variáveis.

---

## 📚 Source | Fonte

The examples presented here are **reproductions of figures** from:

Os exemplos apresentados aqui são **reproduções de figuras** de:

Helsel, D. R., & Hirsch, R. M. (2002).  
*Statistical Methods in Water Resources*.  
U.S. Geological Survey.  

Chapter 8 – Correlation.

---

## ⚠️ Disclaimer | Aviso

This repository is intended for **educational purposes only**.

Figures were recreated using Python based on the original examples from the reference above.  
All conceptual credit belongs to the original authors.

Este repositório tem **fins exclusivamente educacionais**.

As figuras foram recriadas em Python com base nos exemplos originais da referência acima.  
Todo o crédito conceitual pertence aos autores originais.

---

## 📈 Examples | Exemplos

We reproduce three classical cases discussed in the reference:

Reproduzimos três casos clássicos discutidos na referência:

### 1. Monotonic but nonlinear  
### 1. Monotônica, mas não linear  

- Strong relationship  
- Pearson underestimates association  
- Rank-based methods perform better  

---

### 2. Linear (monotonic)  
### 2. Linear (monotônica)  

- All coefficients are high  
- Similar results across methods  

---

### 3. Nonmonotonic  
### 3. Não monotônica  

- Clear structure in the data  
- Correlation coefficients are near zero  

---

## 🔬 Methods | Métodos

We compute three correlation coefficients:

Calculamos três coeficientes de correlação:

- Pearson’s r (linear correlation)  
- Spearman’s rho (rank-based, monotonic)  
- Kendall’s tau (rank-based, monotonic)  

---

## 🐍 How to run | Como executar

```bash
pip install -r requirements.txt
python correlation_examples.py
