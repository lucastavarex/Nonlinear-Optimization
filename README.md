# Trabalho Final de Otimização Não Linear

Este repositório contém o trabalho final da disciplina COS360 - Otimização, realizado na Universidade Federal do Rio de Janeiro (UFRJ). O trabalho aborda métodos de descida com busca de Armijo, incluindo o Método do Gradiente, Método de Newton e Quase-Newton (BFGS).

## Estrutura do Repositório

- [`otm_entrega_final.ipynb`](otm_entrega_final.ipynb): Notebook principal contendo a implementação dos métodos de otimização e testes com funções exemplo.

## Conteúdo do Notebook Principal

### Métodos Implementados

1. **Método do Gradiente com Busca de Armijo**
2. **Método de Newton com Busca de Armijo**
3. **Método Quase-Newton (BFGS) com Busca de Armijo**

### Funções Testadas

### Funções Utilizadas

1. **Função 1**  
   \[
   f(x) = \sum_{i=1}^{6} \left[ 100(x_{i+1} - x_i^2)^2 + (1 - x_i)^2 \right]
   \]

2. **Função 2**  
   \[
   f(x) = \sum_{i=1}^{100} \left( x_{i}^4 - 16x_i^2 + 5x_i \right)
   \]

3. **Função 3**  
   \[
   f(x) = (x_1^2 + x_2 - 11)^2 + (x_1 + x_2^2 - 7)^2
   \]


### Estrutura do Notebook

1. **Importação de Bibliotecas**
2. **Configuração de Exibição**
3. **Funções Utilitárias**
   - `plot_function`: Função para plotar gráficos em 2D e 3D.
   - `plot_results`: Função para plotar os resultados das otimizações.
   - `printa_resultados`: Função para exibir os resultados das otimizações.
   - `processa_chutes`: Função para processar diferentes chutes iniciais.
4. **Estudo das Funções**
   - Descrição, cálculo do gradiente, pontos críticos e análise da convexidade.
5. **Implementação dos Algoritmos**
   - Busca de Armijo
   - Método do Gradiente
   - Método de Newton
   - Método Quase-Newton (BFGS)
6. **Testes**
   - Testes dos métodos de otimização nas funções fornecidas.
