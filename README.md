# viabilidade-financeira-short-stay

Modelo de viabilidade financeira de um imóvel para locação por temporada (short-stay), construído em Python, com análise de sensibilidade e simulação de Monte Carlo.

> **Aviso:** as premissas são hipotéticas e ilustrativas. Este material não é recomendação de investimento.

## O que o modelo faz
- Monta o fluxo de caixa mensal (receitas, custos, reforma e venda do imóvel) com pandas e numpy
- Calcula o financiamento no sistema SAC
- Calcula a TIR do projeto e do acionista
- Análise de sensibilidade: diária × dias ocupados e ano de saída
- Monte Carlo: 1.000 cenários, para observar a distribuição da TIR e quantas vezes o retorno fica abaixo de 12% a.a. (custo do financiamento)

## Premissas (caso ilustrativo)
Imóvel de R$ 375 mil, 70% financiado em SAC (420 meses, 12% a.a.), reforma de 30% do valor em 12x, taxa de administração de 17%, custos gerais de R$ 1.250/mês, diária de R$ 500 com 24 dias ocupados, valorização de 5% a.a. e venda após 11 anos. Todas ficam no dicionário `premissas`.

## Como executar
Abra o notebook no Google Colab e rode as células em ordem. Bibliotecas: pandas, numpy, matplotlib, seaborn e numpy-financial (`pip install numpy-financial`).

## Autor
Jan Souza | linkedin.com/in/souzajan
