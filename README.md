# O Modelo de Preço Justo de Benjamin Graham

A fórmula de Benjamin Graham é uma ferramenta para avaliação de ações, que se baseia em informações financeiras, como o valor contábil e os lucros da empresa. Essa fórmula é muito utilizada por investidores que desejam determinar se uma ação está subvalorizada ou sobrevalorizada.

O código que utiliza essa fórmula é dividido em seções específicas, que têm funções distintas. Ele começa importando as bibliotecas necessárias e definindo a taxa Selic e a lista de empresas que serão analisadas. Em seguida, faz uma requisição dos dados financeiros dessas empresas no site do Fundamentus e os organiza em um dataframe.

Depois, o código faz algumas formatações nos dados, como a conversão das colunas LPA, ROE e Div_Yield para floats, a remoção de dados negativos de LPA e a conversão da porcentagem de ROE e Div_Yield para valores decimais. Por fim, é criada uma coluna que representa a taxa de crescimento de lucro, utilizando o ROE e o payout financeiro da empresa.

Esse código pode ser facilmente adaptado para analisar outras empresas ou utilizar outros indicadores financeiros. É uma ferramenta útil para investidores que desejam tomar decisões informadas sobre seus investimentos em ações.

# Agradecimentos

- Bruno Carli
- Trading com Dados
