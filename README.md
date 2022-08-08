# Analise_Financeira_comSQLe_RegressaoLinear

Problema de negócio:

Uma rede de hospitais gostaria de compreender as variáveis relacionadas aos gastos com internações hospitalares de pacientes.

Usaremos  dados  de  uma pesquisa  nacional  de  custos  hospitalares  realizada  pela  US Agency  for  Healthcare que consiste  em  registros  hospitalares  de  amostras  de  pacientes internados. Os dados fornecidos são restritos à cidade de Wisconsin e referem-se a pacientes na faixa etária de 0 a 17 anos.

Este trabalho será separado em duas fazes. Na etapa 1 vamos explorar os dados usando Linguagem  SQL  e  responder  10  perguntas  de  negócio.  Na  etapa  2  vamos  realizar  análise estatística com Linguagem R através do Teste ANOVA e Regressão Linear e responder 7 perguntas de negócio.

O dataset foi gerado a partir dos seguintes links: 

https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Cost-Report/HospitalCostPUF

https://healthdata.gov/

Abaixo as perguntas que serão respondidas na análise exploratória dedados com Linguagem SQL:

1-Quantas raças estão representadas no dataset?

2-Qual a idade média dos pacientes?

3-Qual a moda da idade dos pacientes?4-Qual a variância da coluna idade?

5-Qual o gasto total com internações hospitalares por idade?

6-Qual idade gera o maior gasto total com internações hospitalares?

7-Qual o gasto total com internações hospitalares por gênero?

8-Qual a média de gasto com internações hospitalares por raça do paciente?

9-Para  pacientes  acima  de  10  anos,  qual  a  média  de  gasto  total  com  internações hospitalares?

10-Considerando o item anterior, qual idade tem média de gastos superior a 3000?

Abaixo as perguntas que serão respondidas na análise estatística com regressão:

1-Qual a distribuição da idade dos pacientes que frequentam o hospital?

2-Qual faixa etária tem o maior gasto total no hospital?

3-Qual grupo baseado em diagnóstico (Aprdrg) tem o maior gasto total no hospital?

4-A raça do paciente tem relação com o total gasto em internações no hospital?

5-A combinação de idade e gênero dos pacientes influencia no gasto total em internações no hospital?

6-Como o tempo de permanência é o fator crucial para pacientes internados, desejamos descobrir se o tempo de permanência pode ser previsto a partir de idade, gênero e raça.

7-Quais variável têm maior impacto nos custos de internação hospitalar?

ESPAÑOL:

problema de negocios:

A una red de hospitales le gustaría conocer las variables relacionadas con el gasto en ingresos hospitalarios de pacientes.

Usaremos datos de una encuesta nacional de costos hospitalarios realizada por la Agencia de Atención Médica de EE. UU. que consta de registros hospitalarios de muestras de pacientes hospitalizados. Los datos proporcionados están restringidos a la ciudad de Wisconsin y se refieren a pacientes de 0 a 17 años.

Este trabajo se dividirá en dos fases. En el paso 1, exploraremos los datos usando lenguaje SQL y responderemos 10 preguntas comerciales. En el paso 2 realizaremos análisis estadísticos con Language R a través de la Prueba ANOVA y Regresión Lineal y responderemos 7 preguntas de negocios.

El conjunto de datos se generó a partir de los siguientes enlaces:

https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Cost-Report/HospitalCostPUF

https://healthdata.gov/

A continuación se presentan las preguntas que serán respondidas en el análisis exploratorio de datos con lenguaje SQL:

1-¿Cuántas razas están representadas en el conjunto de datos?

2-¿Cuál es la edad promedio de los pacientes?

3-¿Cuál es la moda de la edad de los pacientes? 4-¿Cuál es la varianza de la columna de edad?

5-¿Cuál es el gasto total en ingresos hospitalarios por edad?

6-¿Qué edad genera el mayor gasto total en ingresos hospitalarios?

7-¿Cuál es el gasto total en ingresos hospitalarios por género?

8-¿Cuál es el gasto promedio con ingresos hospitalarios por raza del paciente?

9-Para pacientes mayores de 10 años, ¿cuál es el gasto medio total en ingresos hospitalarios?

10-Considerando el ítem anterior, ¿qué edad tiene un gasto promedio superior a 3000?

A continuación se presentan las preguntas que serán respondidas en el análisis estadístico con regresión:

1-¿Cuál es la distribución por edades de los pacientes que asisten al hospital?

2-¿Qué grupo de edad tiene el mayor gasto hospitalario total?

3-¿Qué grupo basado en diagnóstico (Aprdrg) tiene el gasto hospitalario total más alto?

4-¿La raza del paciente está relacionada con el total gastado en ingresos hospitalarios?

5-¿La combinación de edad y sexo de los pacientes influye en el gasto total en ingresos hospitalarios?

6-Como la duración de la estancia es el factor crucial para los pacientes hospitalizados, queríamos averiguar si la duración de la estancia se puede predecir a partir de la edad, el sexo y la raza.

7-¿Qué variable tiene mayor impacto en los costes de ingreso hospitalario?

