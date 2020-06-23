# Olist

#Entrega 1

Análise detalhada das variáveis
• Para as variáveis qualitativas fazer tabelas de frequência
• Para as variáveis quantitativas calcular as medidas de posição (média, quartis),
de dispersão (desvio padrão e coeficiente de variação) e análise gráfica
(Boxplot e Histograma).

#Entrega 2

Ajustar todas as técnicas que forem compatíveis com Business Case definido.
Possíveis técnicas: Regressão linear, Regressão logística, Análise de cluster,
Árvore de decisão, Análise de cesto de compras, Text mining.

-------
**Faturamento Trimestral no Estado de São Paulo**

*_Tudo que for SP 0 e o que não for é 1_*

*_Order Dataset_*
*_Order Items Dataset_*
*_Order Reviews Dataset_*
*_Sellers Dataset_*
*_Payments Dataset_*

-----
**Variáveis**

**Tabela :** orders 
orders_status 97% dos casos são entregues
order_approved_at

**Tabela :** Order Items Dataset
price
freight_value


**Tabela :** Payments Dataset
payment_value



**Tabela :** Order Reviews Dataset
review_score


**Tabela :** Sellers Dataset
seller_state

---

**Dúvidas sobre Regras de Negócios**

Para calcular o faturamento bruto da empresa (indústria, comércio e prestador de serviços) é necessário multiplicar o preço de venda do produto, mercadoria e/ou serviço pelo total de produtos, mercadorias e/ou serviços vendidos em determinado período

-----

**Definição Grupo**

*_-Qtde Produto  x Valor do Produto + (Frete)_*
ou
*_-Valor da transação_* 


-----

**Previsão; se o produto será entregue dentro do prazo**

*_-Variáveis:_*

cliente mesmo estado que fornecedor (0 ou 1)
Volume do produto	
valor item
valor frete item
data estimada de entrega
data de entrega


#Entrega 3

Ajustar ao menos 3 técnicas de Machine Learning.



####
Utilizar as plataforma databricks para importar os arquivos
https://community.cloud.databricks.com/



