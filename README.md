Machine Learning - Aprendizagem não supervisionada
------------------------------------------------------------------------------------------------------------------------------------------
- Após carregar o dataset eu inicio o projeto tratando os dados fazendo um loop for onde eu vou ter os valores unicos de itens e transacoes feitas e verificando se os dados que eu tenho contém null, o que pode trazer viés quando rodar o codigo

Escolho aplica o algoritmo de regra de associação nesses dados de transações e itens, pois partir disso consigo identificar alguns pontos importantes pro negocio como (comportamento de compra dos cliente ou disposicao de itens na loja)
para fazer isso eu gero um conjunto de dados frequentes e faço um contagem para entender quais produtos são mais vendidos, quantas transações foram feitas apartir e depois  disso e gero regras nesses conjuntos para entender se existe relações entre esses dados 

#### Vou utilizar duas métricas para essa análise suport e confiança

- Suport: número de itens vendidos divido por transações (uma porcentagem), vou estipular que será um conjunto frequente se tiver 3 conjuntos
- Confiança: mede a frequencia que os itens do conjunto X apareceu na transações dos conjuntos X
