### World energy consumption

Dado el consumo energético del mundo y la producción de energía proveniente de distintas fuentes. Vamos a predecir la tendencia del crecimiento de la producción y el consumo de energía a nivel mundial o por país..
vamos a usar el dataset de kaggle esta competición https://www.kaggle.com/datasets/pralabhpoudel/world-energy-consumption, que tiene 17433 muestras y las siguientes columnas representativas:

| Columna                             | Descripción                                                                    |
|:-----------------------------------:|:------------------------------------------------------------------------------:|
| iso_code                            | ISO 3166-1 alpha-3 three-letter country codes                                  |
| country                             | Geographic location                                                            |
| year                                | Year of observation                                                            |
| biofuel_consumption                 | Primary energy consumption from biofuels, measured in terawatt-hours           |
| coal_consumption                    | Primary energy consumption from coal, measured in terawatt-hours               |
| coal_production                     | Coal production, measured in terawatt-hours                                    |
| electricity_generation              | Electricity generation, measured in terawatt-hours                             |
| biofuel_electricity                 | Electricity generation from biofuels, measured in terawatt-hours               |
| coal_electricity                    | Electricity generation from coal, measured in terawatt-hours                   |
| fossil_electricity                  | Electricity generation from fossil fuels, measured in terawatt-hours.          |
| gas_electricity                     | Electricity generation from gas, measured in terawatt-hours                    |
| hydro_electricity                   | Electricity generation from hydropower, measured in terawatt-hours             |
| nuclear_electricity                 | Electricity generation from nuclear power, measured in terawatt-hours          |
| oil_electricity                     | Electricity generation from oil, measured in terawatt-hours                    |
| other_renewable_electricity         | Electricity generation from other renewable sources, measured in terawatt-hour |
| renewables_electricity              | Electricity generation from renewables, measured in terawatt-hours             |
| solar_electricity                   | Electricity generation from solar, measured in terawatt-hours                  |
| wind_electricity                    | Electricity generation from wind, measured in terawatt-hours                   |
| gas_consumption                     | Primary energy consumption from gas, measured in terawatt-hours                |
| gas_production                      | Gas production, measured in terawatt-hours                                     |
| hydro_consumption                   | Primary energy consumption from hydropower, measured in terawatt-hours         |
| low_carbon_electricity              | Electricity generation from low-carbon sources, measured in terawatt-hours.    |
| low_carbon_consumption              | Primary energy consumption from low-carbon sources, measured in terawatt-hours |
| nuclear_consumption                 | Primary energy consumption from nuclear power, measured in terawatt-hours      |
| oil_consumption                     | Primary energy consumption from oil, measured in terawatt-hours                |
| oil_production                      | Oil production, measured in terawatt-hours                                     |
| other_renewable_consumption         | Primary energy consumption from other renewables, measured in terawatt-hours   |
| population                          | Total population                                                               |
| renewables_consumption              | Primary energy consumption from renewables, measured in terawatt-hours         |
| gdp                                 | Total real gross domestic product, inflation-adjusted                          |


El objetivo de este proyecto es predecir si un país tiene una alta o baja proporción de energía
renovable en su producción total de energía. Se utilizará un conjunto de datos sobre el
consumo de energía en todo el mundo. El conjunto de datos contiene varias variables,
incluyendo la producción y el consumo de energía renovable, así como la producción y el
consumo de otras fuentes de energía.
Se ha cambiado el problema al predecir si un país tiene o no un alto porcentaje de energía
renovable en su producción total de energía. Por lo tanto, la métrica de desempeño que se
utilizará ahora será la precisión, el recall, la F1-score y el área bajo la curva ROC (AUC), en
lugar del error medio absoluto (MAE) utilizado anteriormente para predecir la tendencia del
crecimiento de la producción y el consumo de energía a nivel mundial.

