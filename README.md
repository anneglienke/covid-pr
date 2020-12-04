# COVID-19 Brazil/State of Paraná

This is a data repository for COVID-19 related information (cases, deaths, demographics of the patients etc) in the State of Paraná (Brazil).

| File                          | Description                                                                     |
|-------------------------------|---------------------------------------------------------------------------------|
| covid_etl.py                  | script (extracts the data, transforms it and load it to a SQLite database)      |
| covid_dag.py                  | script that creates airflow dag                                                 |
| covid_pr_temp                 | SQLite database template created by covid_etl.py                                |
| covid_pr.rar                  | sample of the data insert into SQLite database created by the covid_etl.py      |


Data source: https://www.saude.pr.gov.br/Pagina/Coronavirus-COVID-19
