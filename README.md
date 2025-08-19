Análise de Churn de Clientes

Este projeto tem como objetivo analisar o comportamento de cancelamento de clientes (churn) de uma empresa de serviços de internet, identificando padrões e fatores que influenciam a fidelização. A análise foi realizada utilizando Python, pandas, Matplotlib e Seaborn.

Objetivos:

Avaliar a taxa de churn em diferentes grupos de clientes.
Identificar fatores que contribuem para o cancelamento de serviços.
Gerar insights acionáveis que ajudem a empresa a reduzir a taxa de churn.

O dataset utilizado contém informações sobre os clientes, incluindo:

Churn: indica se o cliente cancelou o serviço (Yes/No).
Contract: tipo de contrato (mensal, anual, etc.).
Charges.Monthly: valor da mensalidade.
PaymentMethod: método de pagamento.
SeniorCitizen: indica se o cliente é idoso (1) ou não (0).
InternetService: tipo de serviço de internet (fibra, DSL, etc.).

A partir da análise, foram identificados os seguintes pontos:

Clientes mensais: apresentam maior taxa de churn (42,7%).
Clientes idosos: apesar de serem minoria, têm uma taxa de churn elevada (41,7%).
Mensalidades mais altas: clientes nos quartis mais altos de valor de mensalidade somam mais de 60% de churn.
Método de pagamento: clientes que utilizam cheque eletrônico têm churn mais elevado.
Tipo de serviço de internet: clientes com fibra ótica apresentam maior taxa de churn.

Conclusão:
O estudo indica que a empresa enfrenta um problema de fidelização, principalmente entre clientes mais novos, que pagam mensalmente e possuem maiores mensalidades. Esses clientes apresentam maior insatisfação e menor incentivo para permanecer no serviço a longo prazo, o que gera uma taxa de churn elevada.

Tecnologias Utilizadas:
-Python
-Pandas
-Matplotlib
-Seaborn

Como Executar:

Clonar o repositório.
Instalar as dependências necessárias:
pip install pandas matplotlib seaborn
Executar o notebook principal churn_analysis.ipynb.
Explorar os gráficos e tabelas gerados para análise detalhada do churn.

Feito por Caio Hernandes
