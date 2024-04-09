# Projeto de Otimização de Função Contínua utilizando Algoritmos Genéticos

Este repositório contém um projeto desenvolvido durante a disciplina de Inteligência Artificial do curso de Engenharia de Computação na UTFPR.

O projeto consiste em implementações de algoritmos genéticos para otimização de funções contínuas. O código está dividido em três partes, cada uma correspondendo a um arquivo de notebook Jupyter:

## GA X².ipynb

Este notebook implementa um algoritmo genético para otimização de uma função contínua simples. Ele inclui:

- Implementação de um algoritmo genético básico para otimização de uma função de conversão de bits para um número inteiro.
- Utilização de seleção por torneio para escolha dos indivíduos mais aptos.
- Implementação de cruzamento (crossover) e mutação para evoluir a população.
- Função `objective` para avaliar a aptidão (fitness) dos indivíduos.
- Exibição dos resultados da otimização e do processo evolutivo.

## GA xSin(10xPI) print after exec.ipynb

Neste notebook, a otimização é aplicada em uma função mais complexa, \(x \sin(10\pi x) + 1\), utilizando algoritmos genéticos. Destaques incluem:

- Implementação da função objetivo `objective_Sen` para avaliar o desempenho dos indivíduos.
- Utilização de métodos para gerar e evoluir a população, como crossover, mutação e elitismo.
- Visualização dos resultados da otimização ao longo das gerações.
- Plotagem iterativa dos resultados para acompanhar a convergência do algoritmo.

## GA xSin(10xPI).ipynb

Neste notebook, há uma abordagem similar à anterior, porém com implementações adicionais e refinamentos. Destaques incluem:

- Utilização de classes e métodos para facilitar a implementação do algoritmo genético.
- Plotagem iterativa dos resultados para análise da convergência.
- Utilização de estratégias como elitismo e controle de convergência.

Cada notebook representa uma etapa do desenvolvimento do projeto, abordando desde conceitos básicos de algoritmos genéticos até implementações mais sofisticadas para resolver problemas de otimização de funções contínuas.
