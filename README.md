ifood
==============================

Uma empresa bem estabelecida opera no setor de alimentos de varejo e tem cerca de várias centenas de milhares de clientes registrados, atendendo a quase um milhão de consumidores por ano. Apesar de ter tido receitas sólidas e uma boa linha de fundo nos últimos 3 anos, as perspectivas de crescimento de lucro para os próximos 3 anos não são animadoras.

O departamento de marketing está sob pressão para gastar seu orçamento anual de maneira mais sábia. O CMO percebe a importância de ter uma abordagem mais quantitativa ao tomar decisões, motivo pelo qual uma pequena equipe de cientistas de dados foi contratada com um objetivo claro em mente: construir um modelo preditivo que apoiará as iniciativas de marketing direto. Desejavelmente, o sucesso dessas atividades provará o valor da abordagem e convencerá os mais céticos dentro da empresa.

O objetivo da equipe é construir um modelo preditivo que produza o maior lucro para a próxima campanha de marketing direto, agendada para o próximo mês. A nova campanha, sexta, visa vender um novo gadget para a base de dados de clientes. Para construir o modelo, uma campanha piloto envolvendo 2.240 clientes foi realizada. Os clientes foram selecionados ao acaso e contatados por telefone sobre a aquisição do gadget. Durante os meses seguintes, os clientes que compraram a oferta foram devidamente rotulados. O objetivo da equipe é desenvolver um modelo que prevê o comportamento do cliente e aplicá-lo ao resto da base de clientes. Espera-se que o modelo permita à empresa escolher os clientes que têm mais probabilidade de adquirir a oferta, deixando de lado os não-respondentes, tornando a próxima campanha altamente rentável. Além disso, além de maximizar o lucro da campanha, o CMO está interessado em entender e estudar as características dos clientes.



|Feature | Descrição |
|:------:|:----------|
|AcceptedCmp1| 1 se o cliente aceitou a oferta na 1ª campanha. 0 caso contrário |
|AcceptedCmp2| 1 se o cliente aceitou a oferta na 2ª campanha, 0 caso contrário |
|AcceptedCmp3| 1 se o cliente aceitou a oferta na 3ª campanha, 0 caso contrário |
|AcceptedCmp4| 1 se o cliente aceitou a oferta na 4ª campanha, 0 caso contrário |
|AcceptedCmp5| 1 se o cliente aceitou a oferta na 5ª campanha. 0 caso contrário |
|Response (target) | 1 se o cliente aceitou a oferta na última campanha. 0 caso contrário |
|Complain| 1 se o cliente reclamou nos últimos 2 anos |
|DtCustomer| Data de inscrição do cliente na empresa |
|Education| Nível de educação do cliente |
|Marital| Estado civil do cliente |
|Kidhome| Número de crianças pequenas na casa do cliente |
|Teenhome| Número de adolescentes na casa do cliente |
|Income| Renda anual da casa do cliente |
|MntFishProducts| Valor gasto em produtos de peixe nos últimos 2 anos |
|MntMeatProducts| Valor gasto em produtos de carne nos últimos 2 anos |
|MntFruits| Valor gasto em frutas nos últimos 2 anos |
|MntSweetProducts| Valor gasto em produtos doces nos últimos 2 anos |
|MntWines| Valor gasto em vinhos nos últimos 2 anos |
|MntGoldProds| Valor gasto em produtos de ouro nos últimos 2 anos |
|NumDealsPurchases| Número de compras realizadas com desconto |
|NumCatalogPurchases| Número de compras realizadas com o catálogo |
|NumStorePurchases| Número de compras realizadas diretamente nas lojas |
|NumWebPurchases| Número de compras realizadas através do site da empresa |
|NumWebVisitsMonth| Número de visitas ao site da empresa no último mês |
|Recency| Número de dias desde a última compra |