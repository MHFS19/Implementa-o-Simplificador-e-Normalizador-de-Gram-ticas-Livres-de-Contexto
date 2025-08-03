# Simplificador e Normalizador de Gramáticas Livres de Contexto (CFG)

Este projeto em Python implementa algoritmos para **simplificação** e **normalização** de gramáticas livres de contexto (GLC), abrangendo as formas normais de **Chomsky** e **Greibach**, além de melhorias como **fatoração à esquerda** e **remoção de recursão à esquerda**.

##  Funcionalidades

- ✅ Remoção de símbolos **inúteis** (inalcançáveis e não-produtivos)
- ✅ Eliminação de **produções vazias** (ε)
- ✅ Remoção de **produções unitárias**
- ✅ Conversão para **Forma Normal de Chomsky (CNF)**
- ✅ Conversão para **Forma Normal de Greibach (GNF)**
- ✅ **Fatoração à esquerda**
- ✅ **Remoção de recursão à esquerda** (direta e indireta)

##  Formato de entrada

A gramática é fornecida como string no seguinte formato:

S -> a A a | b B v 

A -> a | a A

B -> b
