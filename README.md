### World energy consumption

Dado el consumo energ√©tico del mundo y la producci√≥n de energ√≠a proveniente de distintas fuentes. Vamos a predecir la tendencia del crecimiento de la producci√≥n y el consumo de energ√≠a a nivel mundial o por pa√≠s..
vamos a usar el dataset de kaggle esta competici√≥n https://www.kaggle.com/datasets/pralabhpoudel/world-energy-consumption, que tiene 17433 muestras y las siguientes columnas representativas:

## Datos

| Columna                             | Descripci√≥n                                                                    |
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


<<<<<<< HEAD
El objetivo de este proyecto es predecir si un paÌs tiene una alta o baja proporciÛn de energÌa
renovable en su producciÛn total de energÌa. Se utilizar· un conjunto de datos sobre el
consumo de energÌa en todo el mundo. El conjunto de datos contiene varias variables,
incluyendo la producciÛn y el consumo de energÌa renovable, asÌ como la producciÛn y el
consumo de otras fuentes de energÌa.
Se ha cambiado el problema al predecir si un paÌs tiene o no un alto porcentaje de energÌa
renovable en su producciÛn total de energÌa. Por lo tanto, la mÈtrica de desempeÒo que se
utilizar· ahora ser· la precisiÛn, el recall, la F1-score y el ·rea bajo la curva ROC (AUC), en
lugar del error medio absoluto (MAE) utilizado anteriormente para predecir la tendencia del
crecimiento de la producciÛn y el consumo de energÌa a nivel mundial.


