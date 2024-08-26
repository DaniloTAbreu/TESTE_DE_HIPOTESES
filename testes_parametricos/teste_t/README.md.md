# Problema de Média de açúcar em refrigerantes
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/DaniloTAbreu/Projeto3?tab=MIT-1-ov-file) 

# Sobre o projeto

Descrição do Problema:
Problema de Teste de Hipótese Paramétrico:

Um fabricante de refrigerantes afirma que a média de açúcar em seus refrigerantes é de 35 gramas por lata. Um grupo de consumidores desconfia dessa afirmação e decide realizar um teste para verificar se a quantidade média de açúcar é realmente diferente de 35 gramas por lata. Eles coletam uma amostra aleatória de 30 latas de refrigerante e medem a quantidade de açúcar em cada uma delas. Com base nesses dados, eles desejam realizar um teste de hipótese para confirmar ou refutar a afirmação do fabricante.

Passos para resolver o problema com Python:

Formulação das Hipóteses:

Hipótese nula (H0: μ=35) A média de açúcar é igual a 35 gramas por lata.
Hipótese alternativa (H1: μ≠35): A média de açúcar não é igual a 35 gramas por lata.


Coleta de Dados e Análise Descritiva:

Coletar os dados da quantidade de açúcar em 30 latas de refrigerante.
Calcular a média amostral e o desvio padrão amostral 


Escolha do Teste Estatístico:

Dado que temos a média amostral e o desvio padrão amostral, podemos usar um teste t de Student para uma amostra, pois estamos testando uma média populacional.


Decisão Estatística:

Comparar o valor calculado de t com o valor crítico da distribuição t de Student para determinar se rejeitamos ou não a hipótese nula.
Definir um nível de significância (α), por exemplo, α=0.05, para tomar a decisão.


Interpretação dos Resultados:

Se o valor absoluto de t calculado for maior que o valor crítico da distribuição t com n-1 graus de liberdade e ao nível de significância escolhido, rejeitamos H0 e concluímos que há evidências estatísticas de que a média de açúcar é diferente de 35 gramas por lata.
Caso contrário, não rejeitamos H0 e não há evidências suficientes para afirmar que a média de açúcar é diferente de 35 gramas por lata.


O conjunto de dados foi criado para este teste.


# Tecnologias utilizadas
## Linguagem
- Python


## Estatística
- Teste de hipóteses
- Teste t de Student


## Ferramenta utilizada
- Jupyter notebook

# Autor

Danilo Temerloglou de Abreu

https://www.linkedin.com/in/danilo-temerloglou-de-abreu-27182950/