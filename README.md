## Dataset

The datasets were collected from **33 water purification plants* in the four major rivers of South Korea **(Han River, Geum River, Nakdong River, and Seomjin River)**.

The dataset includes three water quality monitoring indicators: 
hydrogen ion concentration (ph), turbidity (tb), and residual chloride (rc). 

* The water quality data is provided by K-water.
* We collected nine years (2014-2022) of hourly water quality data (approximately 2.46 million water quality data points) from 33 large water purification plants.
* For the study period, we selected 2017 as the base year and included approximately six years up to 2022.
* Preprocessed the data, dropped the rows with null values, unnecessary columns

The original data source can be downloaded [here](https://www.data.go.kr/data/15057290/openapi.do)


The data directory structure is shown as follows. 
```
./
└── datasets/
    ├── preprocessing-data
    │   ├── Geum
    │   │   ├── Asan.csv
    │   │   ├── Boryeong.csv
    │   │   ├── Buan.csv
    │   │   ├── Cheonan.csv
    │   │   ├── Cheongju.csv
    │   │   ├── Geumsan.csv
    │   │   ├── Gongju.csv
    │   │   ├── Gosan.csv
    │   │   ├── Sanseong.csv        
    │   │   └── Seokseong.csv
    │   ├── Hangang
    │   │   ├── Banwol.csv
    │   │   ├── Chungju.csv
    │   │   ├── Deokso.csv
    │   │   ├── Goyang.csv
    │   │   ├── Hwangji.csv
    │   │   ├── Iisan.csv
    │   │   ├── Seongnam.csv
    │   │   ├── Siheung.csv
    │   │   ├── Suji.csv
    │   │   ├── Songjeon.csv     
    │   │   └── Wabu.csv
    │   ├── Nakdong
    │   │   ├── Bansong.csv
    │   │   ├── Gucheon.csv
    │   │   ├── Hakya.csv
    │   │   ├── Miryang.csv
    │   │   ├── Sacheon.csv
    │   │   ├── Unmun.csv
    │   │   ├── Yangsan.csv
    │   │   └── Yeoncho.csv
    │   └── Seomjin
    │       ├── Byeollyang.csv
    │       ├── Deokjeong.csv
    │       ├── Donghwa.csv
    │       └── Pyeongnim.csv
    └── raw-data
```
