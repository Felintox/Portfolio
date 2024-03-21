# Portfólio de Ciência de Dados

![97f3a141-7c1b-4178-8b03-713efd450ed5](https://github.com/Felintox/Portfolio/assets/129033082/8af2b6a0-bd8d-4a97-a505-ad5d1b8f13c5)



# 1) Inferência Estatística 


# Resumo:

A inferência estatística é um ramo da estatística que se dedica a tirar conclusões sobre uma população a partir de uma amostra. Em outras palavras, é o processo de usar os dados coletados de uma amostra menor para fazer generalizações ou previsões sobre uma população maior.
<br>

O desafio proposto trata sobre o transtorno depressivo, um problema multifatorial que pode ter várias possíveis combinações de situações como causa.


## Apartir dos dados foram feitas algumas Inferencia atraves de teste de hipoteses:

1. Há associação entre gênero e depressão?

2. As médias de idade são as mesmas para os três grupos de depressão?

3. As médias de renda familiar são as mesmas para os três grupos de depressão?

## Banco de Dados


Os dados disponíveis são resultados da NHNES (National Health and Nutrition Examination Survey), realizada anualmente nos EUA para avaliar a saúde e nutrição de adultos e crianças;

DEMO_PHQ.csv: banco de dados contendo 5334 observações de adultos pesquisados no NHANES 2005-2006

PAG_HEI.csv: banco de dados contendo 9424 observações de crianças e adultos pesquisados no NHANES 2005-2006

## Mais Detalhes:
## <a href="https://github.com/Felintox/Tera_Desafio_Inferencia">Link para o Projeto</a>

#


# 2) Regressão ( em finalização )

A regressão é uma técnica estatística e de aprendizado de máquina amplamente usada para analisar a relação entre variáveis. Em sua essência, a regressão busca entender como o valor de uma variável dependente (ou variável de resposta) muda em relação a uma ou mais variáveis independentes (ou preditores). 

O objetivo principal é modelar a relação entre essas variáveis para fazer previsões ou entender a dinâmica subjacente do fenômeno em estudo.

## RESUMO:

Construir um modelo com alto poder preditivo, com mais variáveis, visando um bom desempenho e com o intuito de ser usado em uma página web como preditora de desempenho. Note que, em casos como esse, queremos ter o menor erro possível, mesmo que o modelo seja complexo e tenha uma interpretação mais difícil.<br>

## Base de dados:

O conjunto de dados descreve o desempenho de candidatos do ENEM, no ano de 2021. Ele contém 168.979 observações e um 76 variáveis explicativas provenientes do questionário socioeconômico preenchido pelos candidatos antes do exame, além da nota média (a target) dos candidatos. 

## Mais Detalhes:
## <a href="https://github.com/Felintox/Tera_Desafio_Regressao">Link para o Projeto</a>


# 3) Análise Exploratória de Dados para a Área de Varejo

Este projeto tem como objetivo responder dez perguntas de negócio para entender melhor sobre um conjunto de dados de uma rede de varejo que comercializa diversos produtos em diversas cidades dos EUA.

## Perguntas de Negócio

As perguntas de negócio que serão respondidas neste projeto são as seguintes:

* **Pergunta de Negócio 1:** Qual Cidade com Maior Valor de Venda de Produtos da Categoria 'Office Supplies'

  
* **Pergunta de Negócio 2:** Qual o Total de Vendas Por Data do Pedido?
* **Pergunta de Negócio 3:** Qual o Total de Vendas por Estado?
* **Pergunta de Negócio 4:** Quais São as 10 Cidades com Maior Total de Vendas?
* **Pergunta de Negócio 5:** Qual Segmento Teve o Maior Total de Vendas?
* **Pergunta de Negócio 6:** Qual o Total de Vendas Por Segmento e Por Ano?
* **Pergunta de Negócio 7:** Quantas Vendas Receberiam 15% de Desconto?
* **Pergunta de Negócio 8:** Qual Seria a Média do Valor de Venda Antes e Depois do Desconto?
* **Pergunta de Negócio 9:** Qual o Média de Vendas Por Segmento, Por Ano e Por Mês?
* **Pergunta de Negócio 10:** Qual o Total de Vendas Por Categoria e SubCategoria, Considerando Somente as Top 12 SubCategorias?

## Base de Dados:

O dataset usado neste projeto está disponível no seguinte link:

[https://community.tableau.com/community/samples/sample-superstore-sales-excelxls](https://community.tableau.com/s/question/0D54T00000CWeX8SAL/sample-superstore-sales-excelxls)

Foram feitas algumas alterações, mas o arquivo usado no projeto está no Github.

## Mais Detalhes:
## <a href="https://github.com/Felintox/Curso-DSA">Link para o Projeto</a>

# 4) Análise de Dados de E-Commerce com SQL
A análise de dados se tornou essencial na maioria das empresas hoje em dia. Os insights derivados da análise de dados podem resultar em melhorias significativas em várias indústrias e áreas de negócios. 

Neste artigo irei realizar uma análise em um conjunto de dados de bem conhecido de E-Commerce do Brasil, o que nos permitirá compreender melhor o comportamento do consumidor, avaliar o desempenho de produtos e funcionários, entre outras informações, utilizando a linguagem SQL.

SQL, ou Linguagem de Consulta Estruturada, é uma linguagem de programação destinada a gerir e manipular sistemas de banco de dados relacionais. É vastamente empregada para consultas, inserções, atualizações e exclusões de dados em um banco de dados. A SQL é vital para a análise de dados, pois habilita os usuários a realizar consultas complexas e extrair insights de grandes conjuntos de dados de maneira eficaz.

# Fonte dos Dados

Vamos realizar a análise através de um conjunto de dados muito famoso na plataforma do Kaggle, o "Brazilian E-Commerce Public Dataset by Olist". 

O conjunto de dados contém informações de 100 mil pedidos de 2016 a 2018, feitos em vários marketplaces no Brasil. Seus recursos permitem visualizar um pedido em múltiplas dimensões: desde status do pedido, preço, desempenho de pagamento e frete até a localização do cliente, atributos do produto e, finalmente, avaliações escritas pelos clientes. 

O conjunto de dados é constituído por 9 tabelas diferentes, cada uma com particularidades específicas, e segue o diagrama de relacionamento abaixo:

![1_aXTlOcs3-l0L4Bi_pyiADA](https://github.com/Felintox/Sql_Olist_Analise/assets/129033082/8d16ad80-0849-4786-92d6-b7932b2ed3a1)

## Tabelas do nosso Conjunto de Dados:

olist_customers_dataset.csv : Tabela com informação dos Clientes

olist_geolocation_dataset.csv: Tabela com informações de Localização dos clientes.

olist_order_items_dataset.csv: Tabela com os pedidos feitos.

olist_order_payments_dataset.csv: Tabela com informação dos pagamentos.

olist_order_reviews_dataset.csv: Tabela com as avaliações.

olist_orders_dataset.csv: Informações mais detalhadas sobre os pedidos.

olist_orders_sellers_dataset.csv: Tabela com informações do vendedor.

olist_products_dataset.csv: Tabela com informações dos produtos e suas categorias.


## Mais Detalhes:
## <a href="https://github.com/Felintox/Sql_Olist_Analise">Link para o Projeto</a>


