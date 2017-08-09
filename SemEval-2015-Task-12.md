[SemEval-2015 Task 12](http://alt.qcri.org/semeval2015/task12/), a continuation of SemEval-2014 Task 4, aimed to foster research beyond sentence- or text-level sentiment classification towards Aspect Based Sentiment Analysis. The goal is to identify *opinions expressed* about *specific entities* (e.g., laptops) and *their aspects* (e.g., price). The task provided manually annotated reviews in three domains (restaurants, laptops and hotels), and a common evaluation procedure. It attracted 93 submissions from 16 teams.

**Dataset**

* `Laptops` (train: 277 review texts, test: 173 review texts)

Aspect Categories: 23 entity labels (LAPTOP, DISPLAY, KEYBOARD, MOUSE, MOTHERBOARD, CPU, FANS& COOLING, PORTS, MEMORY, POWER SUPPLY, OPTICAL DRIVES, BATTERY, GRAPHICS, HARD DISK, MULTIMEDIA DEVICES, HARDWARE, SOFTWARE, OS, WARRANTY, SHIPPING, SUPPORT, COMPANY), 9 attribute labels (GENERAL, PRICE, QUALITY, OPERATION&PERFORMANCE, USABILITY, DESIGN& FEATURES, PORTABILITY, CONNECTIVITY, MISCELLANEOUS)

* `Restaurants` (train: 254 review texts, test: 96 review texts)

Aspect Categories: 6 entity labels (RESTAURANT, FOOD, DRINKS, AMBIENCE, SERVICE, LOCATION), 5 attribute labels (GENERAL, PRICES, QUALITY, STYLE & OPTIONS, MISCELLANEOUS)

**Subtask: Aspect category identification slot**

Dataset: `Laptops`

| Method   	| F1            | Year 	|
|----------	|--------	|------	|
| [NLANGP](http://www.aclweb.org/anthology/S15-2083)   	| 50.86* 	| 2015 	|
| [Sentiue](http://alt.qcri.org/semeval2015/cdrom/pdf/SemEval130.pdf)  	| 50.00* 	| 2015 	|
| IHS-RD   	| 49.59  	| 2015 	|
| NLANGP   	| 49.06  	| 2015 	|
| TJUdeM   	| 46.49  	| 2015 	|
| UFRGS    	| 44.95  	| 2015 	|
| UFRGS    	| 44.73  	| 2015 	|
| V3       	| 24.94  	| 2015 	|

Dataset: `Restaurants`

| Method    | F1     | Year |
|-----------|--------|------|
| [NLANGP](http://www.aclweb.org/anthology/S15-2083)    | 62.68* | 2015 |
| [NLANGP](http://www.aclweb.org/anthology/S15-2083)    | 61.94* | 2015 |
| [UMDuluthC](http://alt.qcri.org/semeval2015/cdrom/pdf/SemEval126.pdf) | 57.19  | 2015 |
| [UMDuluthT](http://alt.qcri.org/semeval2015/cdrom/pdf/SemEval126.pdf) | 57.19  | 2015 |
| SIEL      | 57.14  | 2015 |
| Sentiue   | 54.10  | 2015 |
| LT3       | 53.67  | 2015 |
| TJUdeM    | 52.44  | 2015 |

**Subtask: OTE slot**

Dataset: `Restaurants`

| Method    | F1     | Year |
|-----------|--------|------|
| [EliXa](https://aclweb.org/anthology/S/S15/S15-2127.pdf)    | 70.05* | 2015 |
| [NLANGP](http://www.aclweb.org/anthology/S15-2083)    | 67.11* | 2015 |
| IHS-RD. | 63.12  | 2015 |
| Lsislif | 62.22  | 2015 |

**Subtask: Sentiment polarity**

Dataset: `Laptops`

| Method    | Accuracy | Year |
|-----------|--------|------|
| Sentiue   | 79.34* | 2015 |
| ECNU   | 78.29* | 2015 |
| Lsislif | 77.87  | 2015 |
| ECNU| 74.49  | 2015 |

Dataset: `Restaurants`

| Method    | Accuracy | Year |
|-----------|--------|------|
| Sentiue   | 78.69* | 2015 |
| ECNU   | 78.10* | 2015 |
| Lsislif | 75.50  | 2015 |
| LT3| 75.02  | 2015 |

Dataset: `Hotels`

| Method    | Accuracy | Year |
|-----------|--------|------|
| lsislif | 85.84* | 2015 |
| LT3 | 80.53* | 2015 |
| EliXa  | 79.64  | 2015 |
| sentiue | 78.76  | 2015 |
