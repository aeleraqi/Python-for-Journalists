# Data for the book

The data files used in *The Code Behind the Story: Data Skills with Python for Journalists*,
second edition. In Colab, download a file with this cell, putting its name after `data/`:

```python
repo = ("https://raw.githubusercontent.com/"
        "aeleraqi/Python-for-Journalists/main")
!wget -q {repo}/data/Housing.csv
```

| File | Chapter | What it holds | Source and license |
|---|---|---|---|
| `Electric_Vehicle_Population_Data.csv` | 3 | Washington State register of electric vehicles, 150,482 rows (a copy from August or September 2023) | Washington State Department of Licensing, data.wa.gov dataset f6w7-q2d2 (Open Database License); copy uploaded to Kaggle by Sahil Raj (ssrai7, CC BY-SA 4.0) |
| `Housing.csv` | 4 | 545 house sales | Kaggle "Housing Prices Dataset" by yasserh (CC0); the rows match the 1987 Windsor, Canada sales of Anglin and Gençay (1996), with prices multiplied by 70 |
| `Egyptian Doctors Data.csv`, `.xlsx` | 2 | 1,210 listings of doctors in Egypt | github.com/aeleraqi/Data (MIT License) |
| `Donald Trump.txt` | 2 | Transcript of a speech of 6 November 2024 | github.com/aeleraqi/Data (MIT License) |
| `user_behavior_dataset.csv` | 2 | 700 rows about smartphone use, for practice only | Kaggle "Mobile Device Usage and User Behavior Dataset" by valakhorasani (Apache 2.0); its page says it is not a reliable source for an article |
| `interactive_data.csv` | 2 | US gun deaths, 2012 to 2014 | FiveThirtyEight guns-data (github.com/fivethirtyeight/guns-data); FiveThirtyEight data is CC BY 4.0 unless noted |

Chapter 2 downloads its files from where they are published; the copies here are for when a
source is out of reach. Each file keeps the license of its source.
