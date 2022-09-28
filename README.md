# Projeto de vendas de lojas no ano de 2019

- Acabei pegando um exemplo de um banco de dados de 2019 onde contem o codigo da venda,  data da venda, identificador da loja, produto quantidade, valor unitário, valor final e para treinar acabei criando uma nova coluna de comissão(5% do valor final).
- Acabei vendo os tipos de cada variável utilizando dtypes, e acabaei verificando que a data estava realmente datetime, então não foi preciso fazer a conversão de int para datetime.
- Fiz um value counts dos produtos para descobrir a quantidade de produtos que são vendidos e suas respectivas quantidades de venda.
- Treinei uma filtragem do meu df filtrando somente para pegar os dados do Norte Shopping
- Após essa filtragem escolhi por pegar somente as colunas ID Loja, Produto e Quantidade
- Criei uma coluna comissão com 5% do valor final
- Verifiquei se tinha algum dado nulo(Mão teve nesse cao), caso tivesse seria interessante preencher com a média
- Fiz uma filtragem para saber quantas transações cada loja realizou, utilizando um gráfico de barras horizontal é possivel perceber que o shopping Vila Velha doi o que mais teve venda, enquanto o Shopping Midway Mall foi o que vendeu menos.
- Fiz um faturamento total de cada produto e podemos ver que o terno listrdo é o que mais possui faturamento enquanto a meia é o que menos vende.
- Descobri em qual mês teve o maior vende que foi em outubro de 2019 enquanto e menor faturamento ocorreu no mês 5 do produto meia
- Fiz um gráfico vendo qual foi o faturamento total por mês e pode-se notar que o melhor mês foi em abril enqaunto o pior foi em agosto.
- filtrei as vendas apenas do shopping midway mall e salvei em uma variável e fiz um grafico de dispersão.
