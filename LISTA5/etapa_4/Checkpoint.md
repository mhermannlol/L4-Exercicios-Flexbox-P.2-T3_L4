1. Com temperatura = 20, qual mensagem aparece? E com 30? Por quê?
R: Com temperatura = 20, aparece “Agradável”: a primeira condição (>= 30) é falsa, e a segunda (>= 20) é verdadeira. Com 30, aparece “Calor”, porque a primeira condição já é verdadeira.

2. Quais as saídas das quatro últimas linhas? Por que recomendamos ===?
R: As saídas são true, false, true e false. Recomenda-se === porque == converte os tipos antes de comparar, o que gera resultados inesperados (por exemplo, 0 == false dá true). Com ===, valor e tipo precisam ser iguais.

3. Escreva uma condição que seja verdadeira apenas quando a variável nota estiver entre 0
e 10 (inclusive):
R: if (nota >= 0 && nota <= 10) {
}