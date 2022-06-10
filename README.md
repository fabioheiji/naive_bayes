# naive_bayes

Código em Python que implementa o modelo de Naive Bayes sem o uso de bibliotecas estatísticas com as implementações prontas (por exemplo: sklearn).

Os resultados aqui foram gerados com base em 1 semana de emails coletados, onde eu rotulei cada email como SPAM ou NAO_SPAM

O resultado foi bem surpreendente já que o modelo conseguiu prever todos os emails corretamente, sendo que em apenas 1 caso o modelo teve dificuldade em prever já que o cálculo dos produtos de probabilidades resultou em um número muito pequeno o qual o python identificou como score zero tanto para estimar o valor se o email seria SPAM quanto para NAO_SPAM.

Como desdobramento, a ideia seria implementar o cross validation e aumentar o conjunto de dados para testar o modelo.