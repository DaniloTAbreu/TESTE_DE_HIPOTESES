# Problema de diferentes métodos de ensino de matemática
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/DaniloTAbreu/Projeto3?tab=MIT-1-ov-file) 

# Sobre o projeto

Descrição do Problema:
Problema de Teste de Hipótese Paramétrico

Problema:

Imagine que você é um pesquisador interessado em investigar se diferentes métodos de ensino têm um impacto significativo no desempenho dos alunos em uma prova de matemática. Você tem três métodos diferentes de ensino (A, B e C) e deseja determinar se há diferenças estatisticamente significativas nas médias das notas dos alunos entre esses métodos.

Solução em Python utilizando ANOVA:

Para resolver esse problema utilizando ANOVA (Análise de Variância), você pode seguir os passos abaixo:

Coleta dos Dados:
O conjunto de dados foi criado para este teste.
Coletar as notas dos alunos para cada um dos métodos de ensino (A, B e C).
Formulação das Hipóteses:

Hipótese Nula (H0): Não há diferença significativa nas médias das notas entre os métodos de ensino (μA = μB = μC).
Hipótese Alternativa (H1): Pelo menos uma média das notas é significativamente diferente das outras.
Importação das Bibliotecas:

Importar as bibliotecas necessárias, como scipy.stats para realizar o teste ANOVA e numpy para manipulação dos dados.
Execução do Teste ANOVA:

Utilizar a função f_oneway da biblioteca scipy.stats para realizar o teste de ANOVA. Esta função calcula a estatística F e o valor-p associado.
Interpretação dos Resultados:

Comparar o valor-p obtido com um nível de significância escolhido (por exemplo, α = 0.05). Se o valor-p for menor que α, rejeitamos a hipótese nula e concluímos que há pelo menos uma diferença significativa nas médias das notas entre os métodos de ensino.



# Tecnologias utilizadas
## Linguagem
- Python


## Estatística
- Verificação de suposições para testes estatísticos
- Teste de hipóteses
- Teste ANOVA


## Ferramenta utilizada
- Jupyter notebook

# Autor

Danilo Temerloglou de Abreu

https://www.linkedin.com/in/danilo-temerloglou-de-abreu-27182950/