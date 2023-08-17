# Rusty Bargain: Serviço de carros

## Descrição do projeto
Rusty Bargain é um serviço de venda de carros usados que está desenvolvendo um aplicativo para atrair novos clientes. Nesse aplicativo, podemos descobrir rapidamente o valor de mercado de um carro. Temos acesso a dados históricos, especificações técnicas, versões de acabamento e preços. Precisamos construir o modelo para determinar o valor.

Rusty Bargain está interessado na qualidade da predição,	na velocidade da predição,	no tempo necessário para o treinamento.

## Instruções do projeto
1.	Treinar modelos diferentes com vários hiperparâmetros. O ponto principal desta etapa é comparar métodos de gradient boosting com floresta aleatória, árvore de decisão e regressão linear.
2.	Analisar a velocidade e a qualidade dos modelos.
   
## Descrição de dados
Características
-	DateCrawled — data em que o perfil foi baixado do banco de dados
-	VehicleType — tipo de carroçaria do veículo
-	RegistrationYear — ano de matrícula do veículo
-	Gearbox — tipo de caixa de transmissão
-	Power — potência (hp)
-	Model — modelo do veículo
-	Mileage — quilometragem (medida em km devido às especificidades regionais do conjunto de dados)
-	RegistrationMonth — mês de registro do veículo
-	FuelType — tipo de combustível
-	Brand — marca do veículo
-	NotRepaired — veículo reparado ou não
-	DateCreated — data de criação do perfil
-	NumberOfPictures — número de fotos do veículo
-	PostalCode — código postal do proprietário do perfil (usuário)
-	LastSeen — data da última atividade do usuário
  
Objetivo
- Price — preço (Euro)
