# COVID-19-CRAWLER-NYS

Web Crawler for the update of COVID-19 data from [New York State Government](https://coronavirus.health.ny.gov/county-county-breakdown-positive-cases)

# Dependencies
```
pip3 install BeautifulSoup
pip3 install PrettyTable
```

# Run
```
python3 main.py & python3 nameMap.py
```

# Sample
Result sample
```
Last Update: March 20, 2020 | 3:25PM
+--------------------------------+----------------+
|             County             | Positive Cases |
+--------------------------------+----------------+
|             Albany             |       61       |
|            Allegany            |       2        |
|             Broome             |       2        |
|            Chenango            |       2        |
|            Clinton             |       2        |
|            Columbia            |       1        |
|            Delaware            |       1        |
|            Dutchess            |       36       |
|              Erie              |       31       |
|             Essex              |       1        |
|             Fulton             |       1        |
|            Genesee             |       1        |
|             Greene             |       2        |
|            Hamilton            |       2        |
|            Herkimer            |       2        |
|           Jefferson            |       1        |
|           Livingston           |       1        |
|             Monroe             |       32       |
|           Montgomery           |       2        |
|             Nassau             |      754       |
|            Niagara             |       3        |
|         New York City          |     4,408      |
|             Oneida             |       2        |
|            Onondaga            |       8        |
|            Ontario             |       3        |
|             Orange             |       84       |
|             Putnam             |       7        |
|           Rensselaer           |       8        |
|            Rockland            |      101       |
|            Saratoga            |       24       |
|          Schenectady           |       21       |
|           Schoharie            |       1        |
|            Suffolk             |      371       |
|            Sullivan            |       8        |
|             Tioga              |       1        |
|            Tompkins            |       7        |
|             Ulster             |       12       |
|             Warren             |       1        |
|           Washington           |       1        |
|             Wayne              |       1        |
|          Westchester           |     1,091      |
|            Wyoming             |       2        |
| Total Number of Positive Cases |     7,102      |
+--------------------------------+----------------+
2020-03-20 19:24:50,500 - Successfully crawled.
```
## To be improved
Currently, it only print the data in the console, I will add the database later.

## Reference and Contribution
This project is based on [DXY-COVID-19-Crawler Project](https://github.com/BlankerL/DXY-COVID-19-Crawler).
All credits to [Jiabao Lin](https://github.com/BlankerL/DXY-COVID-19-Crawler).
