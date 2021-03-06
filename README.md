# a_master_of_go
an iOS App of a strong Go AI

## Requests for Helps of Locatlizations
I make current (version 3.8.0) localization files.
Any volunteers for improvements and localizations for other languages are welcome.
Please make pull requests!

## Downloadable extra weights
Please copy one of URLs below and paste "DL weight from:" field in the setting modal on the app.

### [KataGo](https://github.com/lightvector/KataGo) middle-size(15b) weight
#### 19x19
URL: https://github.com/new3Rs/a_master_of_go/releases/download/g170e-b15c192-s1672170752-d466197061/KataGoG170e_b15c192_fp16.json

Alternative URL: https://files.fm/down.php?i=t33nmyx5&n=KataGoG170e_b15c192_fp16.json

#### 13x13
URL: https://github.com/new3Rs/a_master_of_go/releases/download/g170e-b15c192-s1672170752-d466197061/KataGoG170e_b15c192_13_fp16.json 

Alternative URL: https://files.fm/down.php?i=t33nmyx5&n=KataGoG170e_b15c192_13_fp16.json 

#### 9x9
URL: https://github.com/new3Rs/a_master_of_go/releases/download/g170e-b15c192-s1672170752-d466197061/KataGoG170e_b15c192_9x9_fp16.json

Alternative URL: https://files.fm/down.php?i=t33nmyx5&n=KataGoG170e_b15c192_9x9_fp16.json

### [Leela Zero](https://github.com/leela-zero/leela-zero/issues/2192) a recent light-weight(15b) weight
URL: https://github.com/new3Rs/a_master_of_go/releases/download/LeelaZero_15b_a4b5/LeelaZero_15b_a4b5_fp16.json

Alternative URL: https://files.fm/down.php?i=7rbzwqsf&n=LeelaZero_15b_a4b5_fp16.json

### [PhoenixGo](https://github.com/Tencent/PhoenixGo) v1 weight

#### for iOS 13 or later (It needs version 3.11.0 or later.)
URL: https://github.com/new3Rs/a_master_of_go/releases/download/PhoenixGo_v1_for_iOS13/PhoenixGo_v1_fp16.json

Alternative URL: https://files.fm/down.php?i=sp7e9uhn&n=PhoenixGo_v1_fp16.json

#### for iOS 12 or earlier
URL: https://github.com/new3Rs/a_master_of_go/releases/download/PhoenixGo_v1/PhoenixGo_v1_fp16.json

Alternative URL: https://files.fm/down.php?i=t4qk726v&n=PhoenixGo_v1_fp16.json

This weight works on iOS 13 but runs slowly. Please use the above weight for iOS 13.

### [ELF](https://github.com/pytorch/ELF) v2 weight
URL: https://github.com/new3Rs/a_master_of_go/releases/download/ELFOpenGo_v2/ELFOpenGo_v2.json

Alternative URL: https://files.fm/down.php?i=cj62qz7k&n=ELFOpenGo_v2.json

### [minigo](https://github.com/tensorflow/minigo) v17 weight(001003-leviathan)
URL: https://github.com/new3Rs/a_master_of_go/releases/download/minigo_v17/minigo_v17_fp16.json

Alternative URL: https://files.fm/down.php?i=9ms8d6kc&n=minigo_v17_fp16.json

WARNING: Version 3.4.0 or later is required. This weight is very heavy even if you use A12 processor (less than 30 nps).

## How to make your own downloadable weights
See https://github.com/new3Rs/a_master_of_go/blob/master/LZ2mlmodel/README.md.
