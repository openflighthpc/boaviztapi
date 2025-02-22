# Usage methodology

Usage impacts can be assessed at device or component level from usage configuration. 

Usage impacts are measured by multiplying a **[duration, a ratio of usage](duration.md)**, an **[impact factor](elec_factors.md)**, and an **[electrical consumption](elec_conso.md)** :

```impact = electrical_consumption * (duration * use_time_ratio) * impact_factor```

## Characteristics

| Name            | Unit                         | Description                                                      | Example         |
|-----------------|------------------------------|------------------------------------------------------------------|-----------------|
| hours_use_time  | hours                        | Number of hours considered in the evaluation                     | 2               |
| hours_life_time | hours                        | Lifespan of the element                                          | 35040 (4 years) |
| usage_location  | trigram                      | See [available country codes](countries.md)                      | FRA             |
| avg_power       | Watt/hour                    | Average electrical consumption per hour                          | 120             |
| time_workload   | %workload or %time:%workload | See usage                                                        | ..              |
| use_time_ratio  | /1                           | Proportion of time the device is used during the given duration. | 0.5             |

