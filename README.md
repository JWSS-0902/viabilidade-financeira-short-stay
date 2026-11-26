# viaiblidade-financeira-short-stay
Modelagem financeira, analise de sensibilidade para investimento imobiliário em Python. 
São premissas adotadas, de forma teórica, a partir de analise de mercado. 
Modelo com premissas, sensibilidade de retorno.
O modelo assume algumas premissas, que estão no dicionário "Premissas".
Em cima disso, a partir da biblioteca pandas e numpy, são criados fluxos que representam um opex e capex num imóvel, com a consequencia expectativa de retorno. 
São realizados testes de monte carlo com o intuito de gerar possíveis retorno e observar quantas vezes aparece retorno abaixo do custo de capital. 
