# Estatísticas e Distribuições Probabilísticas

Este repositório contém notebooks que abordam diferentes testes estatísticos e distribuições probabilísticas. Cada notebook fornece uma explicação teórica, exemplos práticos e código para executar análises específicas.

## Conteúdo

### 1. Teste t de Student (`1.t_student_[1].ipynb`)
- **Introdução ao teste t de Student**: Explicação teórica do teste e seus fundamentos.
- **Importação de bibliotecas**: Código para importar bibliotecas essenciais como numpy, scipy, pandas, etc.
- **Carregamento de dados**: Código para carregar os dados a serem analisados.
- **Análise exploratória dos dados**: Estatísticas descritivas e visualizações para entender os dados.
- **Execução do teste t de Student**: Código para realizar o teste.
- **Interpretação dos resultados**: Discussão sobre os resultados obtidos e sua significância.
- **Conclusão**: Resumo dos achados do teste.

### 2. Distribuição Binomial (`2.binomial_[1].ipynb`)
- **Introdução à distribuição binomial**: Explicação teórica da distribuição binomial e seus usos.
- **Importação de bibliotecas**: Código para importar bibliotecas como numpy, scipy, etc.
- **Definição de parâmetros binomiais**: Código para definir os parâmetros n (número de ensaios) e p (probabilidade de sucesso).
- **Geração de dados binomiais**: Código para gerar dados com base na distribuição binomial.
- **Visualização dos dados**: Gráficos para ilustrar a distribuição dos dados.
- **Cálculos de probabilidades**: Código para calcular probabilidades específicas usando a distribuição binomial.
- **Exemplos práticos**: Aplicação da distribuição binomial em cenários do mundo real.
- **Conclusão**: Resumo dos achados e da aplicação da distribuição binomial.

### 3. Distribuição de Poisson (`3.poisson_[1].ipynb`)
- **Introdução à distribuição de Poisson**: Explicação teórica da distribuição de Poisson e suas aplicações.
- **Importação de bibliotecas**: Código para importar bibliotecas como numpy, scipy, etc.
- **Definição de parâmetros de Poisson**: Código para definir o parâmetro λ (taxa média de ocorrências).
- **Geração de dados de Poisson**: Código para gerar dados com base na distribuição de Poisson.
- **Visualização dos dados**: Gráficos para ilustrar a distribuição dos dados.
- **Cálculos de probabilidades**: Código para calcular probabilidades específicas usando a distribuição de Poisson.
- **Exemplos práticos**: Aplicação da distribuição de Poisson em cenários do mundo real.
- **Conclusão**: Resumo dos achados e da aplicação da distribuição de Poisson.

### 4. Teste Qui-Quadrado (`4.chi_squared_[1].ipynb`)
- **Introdução ao teste Qui-Quadrado**: Explicação teórica do teste e seus fundamentos.
- **Importação de bibliotecas**: Código para importar bibliotecas essenciais como numpy e scipy.
- **Criação de matrizes de dados e execução do teste**:
  - Exemplo 1: Matriz `[[19, 6], [43, 32]]` com p-valor maior que 0,05, indicando não haver diferença significativa.
  - Exemplo 2: Matriz `[[22, 3], [43, 32]]` com p-valor menor que 0,05, indicando uma diferença significativa.
- **Conclusão**: Discussão sobre os resultados obtidos e sua significância.

### 5. ANOVA (`5.anova_[1].ipynb`)
- **Introdução à ANOVA**: Explicação teórica da análise de variância e suas aplicações.
- **Importação de bibliotecas**: Código para importar bibliotecas como pandas, scipy, statsmodels, etc.
- **Carregamento de dados**: Código para carregar os dados a serem analisados (`anova.csv`).
- **Análise exploratória dos dados**: Visualização de dados usando boxplots.
- **Criação de modelos de regressão e execução do teste**:
  - Modelo 1: `Horas ~ Remedio`, mostrando p-valor maior que 0,05.
  - Modelo 2: `Horas ~ Remedio * Sexo`, mostrando ausência de p-valores significativos.
- **Execução do teste de Tukey**: Aplicação do teste de Tukey e visualização dos resultados.
- **Conclusão**: Discussão sobre os resultados obtidos e sua significância.

