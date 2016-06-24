# ICCSS Datathon Data

The dataset was scrapped for the purpose of ICCSS Conference Datathon. It was parsed to easy to load .csv format. Datasets cover  2008, 2012 and 2016 elections. There are two types of files, one of them contains of url, title, source, candidate and title of candidates' speech, statatemt or press release, the other (_all.csv files) contains additionally of the whole text of speech/press release.   

I recommend to use Python to load it:
```sh
import pandas as pd
speeches = pd.read_csv('2016_all.csv')
```

Source of data: presidency.ucsb.edu