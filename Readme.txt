Base de dados extraída do endereço:
https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition

A base trata da relação de obesidade com hábitos e costumes como hábitos alimentares, consumo de água, meio de trans porte utilizado corriqueiramente, ingestã ode bebida alcoólica, entre outros.

Foi efetuado pre tratamento da base para inclusão de uma coluna (death_risk) para ser analizado o risco de vida em relação aos diversos parâmetros conforme classificação de morbidade em relação ao nivel classificação de peso corporal.
Foi definido risco de vide para os parâmetros de Obesidade niveis I, II e III.

Foram importadas para análise as bibliotecas:
pandas
numpy
matplotlib
seaborn


Informações do dataset


Variables Table						
Variable
Name				Role		Type		Demographic	Description						Units	Missing Values
Gender				Feature		Categorical			Gender								no
Age				Feature		Continuous			Age								no
Height				Feature		Continuous											no
Weight				Feature		Continuous											no
family_history_with_overweight	Feature		Binary				Has a family member suffered or suffers from overweight?	no
FAVC				Feature		Binary				Do you eat high caloric food frequently?			no
FCVC				Feature		Integer				Do you usually eat vegetables in your meals?			no
NCP				Feature		Continuous			How many main meals do you have daily?				no
CAEC				Feature		Categorical			Do you eat any food between meals?				no
SMOKE				Feature		Binary				Do you smoke?							no
CH2O				Feature		Continuous			How much water do you drink daily?				no
SCC				Feature		Binary				Do you monitor the calories you eat daily?			no
FAF				Feature		Continuous			How often do you have physical activity?			no
TUE				Feature		Integer				How much time do you use technological devices such
										as cell phone, videogames, television, computer and others?	no
CALC				Feature		Categorical			How often do you drink alcohol?					no
MTRANS				Feature		Categorical			Which transportation do you usually use?			no
NObeyesdad			Feature		Categorical			Obesity level							no
death_risk			Target		Binario
