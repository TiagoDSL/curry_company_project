# Curry Company analysis project

This repository contains files and script to build a company strategy dashboard. This script was created during the Comunidade DS data analysis course, in order to learn how to use python for data analysis.

## The Business Problem
The Cury Company is a technology company that created an application that connects restaurants, delivery men and people.
Through this application, it is possible to order a meal, in any registered restaurant, and have it delivered at the comfort of your home by a delivery person also registered in the Cury Company application.
The company conducts business between restaurants, delivery drivers, and people, and generates a lot of data about deliveries, types of orders, weather conditions, delivery drivers' ratings, etc. Although the delivery is growing, in terms of deliveries, the CEO does not have complete visibility into the company's growth KPIs.
You have been hired as a Data Scientist to create data solutions for delivery, but before you train algorithms, the company's need is to have the key strategic KPIs organized in a single tool, so that the CEO can consult and make simple but important decisions.
The Cury Company has a business model called Marketplace, which intermediates the business between three main customers: Restaurants, deliverers, and buyers. To track the growth of this business, the CEO would like to see the following growth metrics:

### On the business side:
- Amount of orders per day;
- Number of orders per week;
- Distribution of orders by traffic type;
- Comparison of order volume by city and traffic type;
- The amount of orders per deliverer per week;
- The central location of each city by traffic type.

### On the deliveryman side:
- The lowest and highest age of the deliverers;
- The worst and best condition of vehicles;
- The average rating per delivery person;
- The average rating and standard deviation by traffic type;
- The average rating and standard deviation by weather conditions;
- The 10 fastest delivery drivers by city
- The 10 slowest deliverers by city.

### On the restaurant side:
- The amount of unique deliverers;
- The average distance from restaurants and delivery locations;
- The average delivery time and standard deviation by city;
- The average delivery time and standard deviation by city and order type;
- The average delivery time and standard deviation by city and type of traffic;
- The average delivery time during Festivals.
  
## Objective

 - The goal of this project is to create a set of charts and tables that display these metrics in the best way possible so that the CEO can have clarity of the data and make his decisions.

## Assumptions made for the analysis
- The analysis was performed with data between 11/02/2022 and 06/04/2022.
- Marketplace was the assumed business model.
- The 3 main business views were: Order transaction view, restaurant view and delivery man view.

## Solution Strategy
The strategy dashboard was developed using the metrics that reflect the 3 main views of the company's business model, being:
	1 Company growth view;
	2 Vision of the restaurants' growth;
	3 Vision of the deliverers' growth.
  
## Each view is represented by the following set of metrics:
1. Company growth view;
	- Orders per day;
	- Percentage of orders by traffic conditions;
	- Number of orders by type and by city;
	- Orders by week;
	- Number of orders by delivery type;
	- Number of orders by traffic conditions and city type.
  
2. View of the restaurants' growth
	- Number of unique orders
	- Average distance traveled;
	- Average delivery time during festival and normal days;
	- Standard deviation of delivery time during festivals and normal days;
	- Average delivery time by city
	- Distribution of average delivery time by city;
	- Average delivery time by order type.
  
3. View of the growth of the delivery drivers
	- Age of the oldest and youngest delivery person
	- Evaluation of the best and worst vehicle;
	- Average evaluation per delivery person
	- Average assessment by traffic conditions;
	- Average assessment by weather conditions;
	- Average time of the fastest delivery person;
	- Average time of the fastest delivery person per city.

## The Top 3 Data Insights
1.	The seasonality of the number of orders is daily. There is approximately a 10% variation in the number of orders on sequential days;
2.	Semi-Urban type cities do not have low traffic conditions;
3.  The biggest variations in delivery time, happen during sunny weather.

## The final product of the project
- Online dashboard, hosted in a Cloud and available for access from any internet connected device.
The panel can be accessed through this link: https://tiago-curry-company-project-home-iafxzw.streamlit.app/

## Conclusion
- The goal of this project is to create a set of graphs and tables that display these metrics to best help the CEO's decision making.
According to the data from the Company view, we can conclude that the number of orders grew between week 06 and week 13 of the year 2022.

## Future steps for the project:
- Reduce the number of metrics.
- Create new filters.
- Add new business views.

------------------------------------------------------------------------
Este reposit??rio cont??m documentos e scripts para construir um painel de estrat??gia da empresa. Este script foi criado durante o curso de An??lise de Dados da Comunidade DS, a fim de aprender a utilizar o python para an??lise de dados.

## O Problema de neg??cio
A Cury Company ?? uma empresa de tecnologia que criou um aplicativo que conecta restaurantes, entregadores e pessoas.
Atrav??s desse aplicativo, ?? poss??vel realizar o pedido de uma refei????o, em qualquer restaurante cadastrado, e receb??-lo no conforto da sua casa por um entregador tamb??m cadastrado no aplicativo da Cury Company.
A empresa realiza neg??cios entre restaurantes, entregadores e pessoas, e gera muitos dados sobre entregas, tipos de pedidos, condi????es clim??ticas, avalia????o dos entregadores e etc. Apesar da entrega estar crescento, em termos de entregas, o CEO n??o tem visibilidade completa dos KPIs de crescimento da empresa.
Voc?? foi contratado como um Cientista de Dados para criar solu????es de dados para entrega, mas antes de treinar algoritmos, a necessidade da empresa ?? ter um os principais KPIs estrat??gicos organizados em uma ??nica ferramenta, para que o CEO possa consultar e conseguir tomar decis??es simples, por??m importantes.
A Cury Company possui um modelo de neg??cio chamado Marketplace, que fazer o interm??dio do neg??cio entre tr??s clientes principais: Restaurantes, entregadores e pessoas compradoras. Para acompanhar o crescimento desses neg??cios, o CEO gostaria de ver as seguintes m??tricas de crescimento:

### Do lado da empresa:
- Quantidade de pedidos por dia;
-	Quantidade de pedidos por semana;
-	Distribui????o dos pedidos por tipo de tr??fego;
- Compara????o do volume de pedidos por cidade e tipo de tr??fego;
-	A quantidade de pedidos por entregador por semana;
-	A localiza????o central de cada cidade por tipo de tr??fego.

### Do lado do entregador:
-	A menor e maior idade dos entregadores;
-	A pior e a melhor condi????o de ve??culos;
-	A avalia????o m??dida por entregador;
-	A avalia????o m??dia e o desvio padr??o por tipo de tr??fego;
-	A avalia????o m??dia e o desvio padr??o por condi????es clim??ticas;
-	Os 10 entregadores mais r??pidos por cidade;
- Os 10 entregadores mais lentos por cidade.

### Do lado do restaurantes:
-	A quantidade de entregadores ??nicos;
-	A dist??ncia m??dia dos resturantes e dos locais de entrega;
-	O tempo m??dio e o desvio padr??o de entrega por cidade;
-	O tempo m??dio e o desvio padr??o de entrega por cidade e tipo de pedido;
-	O tempo m??dio e o desvio padr??o de entrega por cidade e tipo de tr??fego;
-	O tempo m??dio de entrega durantes os Festivais.
  
## Objetivo

 - O objetivo desse projeto ?? criar um conjunto de gr??ficos e tabelas que exibam essas m??tricas da melhor forma poss??vel para o CEO poder ter clareza dos dados e tomar suas decis??es.

## Premissas assumidas para a an??lise
-	A an??lise foi realizada com dados entre 11/02/2022 e 06/04/2022.
-	Marketplace foi o modelo de neg??cio assumido.
-	As 3 principais vis??es do neg??cio foram: Vis??o transa????o de pedidos, vis??o restaurante e vis??o entregadores.

## Estrat??gia da solu????o
O painel estrat??gico foi desenvolvido utilizando as m??tricas que refletem as 3 principais vis??es do modelo de neg??cio da empresa, sendo:
	1	Vis??o do crescimento da empresa;
	2	Vis??o do crescimento dos restaurantes;
	3	Vis??o do crescimento dos entregadores.
  
Cada vis??o ?? representada pelo seguinte conjunto de m??tricas:
1. Vis??o do crescimento da empresa;
	- Pedidos por dia;
	- Porcentagem de pedidos por condi????es de tr??nsito;
	- Quantidade de pedidos por tipo e por cidade;
	- Pedidos por semana;
	- Quantidade de pedidos por tipo de entrega;
	- Quantidade de pedidos por condi????es de tr??nsito e tipo de cidade.
  
2. Vis??o do crescimento dos restaurantes
	- Quantidade de pedidos ??nicos;
	- Dist??ncia m??dia percorrida;
	- Tempo m??dio de entrega durante festival e dias normais;
	- Desvio padr??o do tempo de entrega durante festivais e dias normais;
	- Tempo de entrega m??dio por cidade;
	- Distribui????o do tempo m??dio de entrega por cidade;
	- Tempo m??dio de entrega por tipo de pedido.
  
3. Vis??o do crescimento dos entregadores
	- Idade do entregador mais velho e do mais novo;
	- Avalia????o do melhor e do pior ve??culo;
	- Avalia????o m??dia por entregador;
	- Avalia????o m??dia por condi????es de tr??nsito;
	- Avalia????o m??dia por condi????es clim??ticas;
	- Tempo m??dido do entregador mais r??pido;
	- Tempo m??dio do entregador mais r??pido por cidade.

## O Top 3 Insights de dados
1.	A sazonalidade da quantidade de pedidos ?? di??ria. H?? uma varia????o de aproximadamente 10% do n??mero de pedidos em dia sequenciais;
2.	As cidades do tipo Semi-Urban n??o possuem condi????es baixas de tr??nsito;
3.  As maiores varia????es no tempo de entrega, acontecem durante o clima ensoladao.

## O produto final do projeto
- Painel online, hospedado em um Cloud e dispon??vel para acesso em qualquer dispositivo conectado ?? internet.
O painel pode ser acessado atrav??s desse link: https://tiago-curry-company-project-home-iafxzw.streamlit.app/

## Conclus??o
- O objetivo desse projeto ?? criar um conjunto de gr??ficos e tabelas que exibam essas m??tricas que ajudem da melhor forma poss??vel a tomada de decis??o do CEO.
De acordo com os dados da vis??o da Empresa, podemos concluir que o n??mero de pedidos cresceu entre a semana 06 e a semana 13 do ano de 2022.

## Passos futuros para o projeto:
-	Reduzir o n??mero de m??tricas.
-	Criar novos filtros.
-	Adicionar novas vis??es de neg??cio.
