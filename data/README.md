# Codebook
<br>

### Regional Data

**Dataset:** dpc-covid19-ita-regioni.csv<br>
**Notebook:** dpc-covid19-regions.ipynb

<br>

| Field Name                       | Description                                                                                                    | Format                                      | Example             |
| -------------------------------- | -------------------------------------------------------------------------------------------------------------- | ------------------------------------------- | ------------------- |
| **data**                         | Date of notification                                                                                           | YYYY-MM-DDTHH:MM:SS (ISO 8601) Ora italiana | 2020-03-05T12:15:45 |
| **stato**                        | Country of reference                                                                                           | XYZ (ISO 3166-1 alpha-3)                    | ITA                 |
| **codice_regione**               | Code of the Region (ISTAT 2019)                                                                                | Integer                                     | 13                  |
| **denominazione_regione**        | Name of the Region                                                                                             | String                                      | Abruzzo             |
| **lat**                          | Latitude                                                                                                       | WGS84                                       | 42.6589177          |
| **long**                         | Longitude                                                                                                      | WGS84                                       | 13.70439971         |
| **ricoverati_con_sintomi**       | Hospitalised patients with symptoms                                                                            | Integer                                     | 3                   |
| **terapia_intensiva**            | Intensive Care                                                                                                 | Integer                                     | 3                   |
| **totale_ospedalizzati**         | Total hospitalised patients                                                                                    | Integer                                     | 3                   |
| **isolamento_domiciliare**       | Home confinement                                                                                               | Integer                                     | 3                   |
| **totale_positivi**              | Total amount of current positive cases (Hospitalised patients + Home confinement)                              | Integer                                     | 3                   |
| **variazione_totale_positivi**   | News amount of current positive cases (totale_positivi current day - totale_positivi previous day)             | Integer                                     | 3                   |
| **nuovi_positivi**               | News amount of current positive cases (totale_casi current day - totale_casi previous day)                     | Integer                                     | 3                   |
| **dimessi_guariti**              | Recovered                                                                                                      | Integer                                     | 3                   |
| **deceduti**                     | Deaths                                                                                                         | Integer                                     | 3                   |
| **casi_da_sospetto_diagnostico** | Positive cases emerged from clinical activity **No longer populated**                                          | Integer                                     | 3                   |
| **casi_da_screening**            | Positive cases emerging from surveys and tests, planned at national or regional level  **No longer populated** | Integer                                     | 3                   |
| **totale_casi**                  | Total amount of positive cases                                                                                 | Integer                                     | 3                   |
| **tamponi**                      | Tests performed   (processed with molecular tests)                                                             | Integer                                     | 3                   |
| **casi_testati**                 | Total number of people tested                                                                                  | Integer                                     | 3                   |
| **note**                         | Notes                                                                                                          | String                                      | Lorem ipsum...      |
| **ingressi_terapia_intensiva**   | Daily admissions to intensive care                                                                             | Integer                                     | 3                   |
| **note_test**                    | Notes on the tests carried out                                                                                 | String                                      | Lorem ipsum...      |
| **note_casi**                    | Notes on the cases tested                                                                                      | String                                      | Lorem ipsum...      |



*The Autonomous Provinces of Trento and Bolzano are indicated in 'Region Name' and with the code 04 for Trentino Alto Adige.* 
<br>

<br>

### Provincial Data

**Dataset:** dpc-covid19-ita-province.csv<br>
**Notebook:** dpc-covid19-province.ipynb

| Field Name                  | Description                     | Format                                      | Example             |
| --------------------------- | ------------------------------- | ------------------------------------------- | ------------------- |
| **data**                    | Date of notification            | YYYY-MM-DD HH:MM:SS (ISO 8601) Ora italiana | 2020-03-05 12:15:45 |
| **stato**                   | Country of reference            | ISO 3166-1 alpha-3                          | ITA                 |
| **codice_regione**          | Code of the Region (ISTAT 2019) | Integer                                     | 13                  |
| **denominazione_regione**   | Name of the Region              | String                                      | Abruzzo             |
| **codice_provincia**        | Code of the Province            | Integer                                     | 067                 |
| **denominazione_provincia** | Name of the Province            | String                                      | Teramo              |
| **sigla_provincia**         | Province abbreviation           | String                                      | TE                  |
| **lat**                     | Latitude                        | WGS84                                       | 42.6589177          |
| **long**                    | Longitude                       | WGS84                                       | 13.70439971         |
| **totale_casi**             | Total amount of positive cases  | Integer                                     | 3                   |
| **note**                    | Notes in italian language       | String                                      | Lorem ipsum...      |


<br>

*The Autonomous Provinces of Trento and Bolzano are indicated in 'Region Name' and with the code 04 for Trentino Alto Adige.*<br>
Each Region has two provinces' called *'Fuori Regione / Provincia Autonoma'*, with the province code from **879 to 899**, useful to indicate data on subjects outside the Region or Autonomous Province, and *'In fase di definizione/aggiornamento'*, with the province code from **979 to 999**, useful to indicate data not yet assigned to the Provinces.<br>

***


