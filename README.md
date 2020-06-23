# Olist


#Objetivo

O objetivo do trabalho é prever se uma entrega ocorrerá dentro do prazo ou não.

A predição será realizada utilizando dados históricos transacionais e modelos estatísticos e algoritmos de Machine Learning, para obter os eventos ligados a compra para saber se haverá atrasos ou não de uma entrega.
 
Desta forma, a empresa poderá traçar estratégias de relacionamento, desenvolver procedimentos operacionais e ações preventivas para identificar eventuais gargalos e deficiência.

------
#Entrega 1

Análise detalhada das variáveis
• Para as variáveis qualitativas fazer tabelas de frequência
• Para as variáveis quantitativas calcular as medidas de posição (média, quartis),
de dispersão (desvio padrão e coeficiente de variação) e análise gráfica
(Boxplot e Histograma).

-----
#Entrega 2

Ajustar todas as técnicas que forem compatíveis com Business Case definido.
Possíveis técnicas: Regressão linear, Regressão logística, Análise de cluster,
Árvore de decisão, Análise de cesto de compras, Text mining.

Tratamento das base de dados para modelagem

Dividimos a base final em 80% para treino e 20% para teste.
Devido a grande diferença entre as categorias 0 e 1, foram utilizadas técnicas de oversampling e undersampling na base de treino para balancear as categorias perdendo o mínimo de informações possíveis.
Para a categoria 1, triplicamos os dados.
Para a categoria 0, dividimos a base em 4 partes, sendo que fizemos testes com todas elas para utilizar a que apresentasse os melhores resultados de treino.
A base de treino final ficou balanceada com aproximadamente 50% dos dados cada categoria.


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



-----

Utilizar as plataforma databricks para importar os arquivos
https://community.cloud.databricks.com/

Referência:
https://www.kaggle.com/olistbr/brazilian-ecommerce



