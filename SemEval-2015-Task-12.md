**SemEval-2015 Task 12** <sup><sub>16 results collected</sub></sup>

[SemEval-2015 Task 12](http://alt.qcri.org/semeval2015/task12/), a continuation of SemEval-2014 Task 4, aimed to foster research beyond sentence- or text-level sentiment classification towards Aspect Based Sentiment Analysis. The goal is to identify *opinions expressed* about *specific entities* (e.g., laptops) and *their aspects* (e.g., price). The task provided manually annotated reviews in three domains (restaurants, laptops and hotels), and a common evaluation procedure. It attracted 93 submissions from 16 teams.

**Aspect category identification slot**

Dataset: Laptops (train: 277 review texts, test: 173 review texts)

Domain: `Technology > Laptop`

Aspect Categories: 23 entity labels (LAPTOP, DISPLAY, KEYBOARD, MOUSE, MOTHERBOARD, CPU, FANS& COOLING, PORTS, MEMORY, POWER SUPPLY, OPTICAL DRIVES, BATTERY, GRAPHICS, HARD DISK, MULTIMEDIA DEVICES, HARDWARE, SOFTWARE, OS, WARRANTY, SHIPPING, SUPPORT, COMPANY), 9 attribute labels (GENERAL, PRICE, QUALITY, OPERATION&PERFORMANCE, USABILITY, DESIGN& FEATURES, PORTABILITY, CONNECTIVITY, MISCELLANEOUS)

| Method   	| Result 	| Year 	|
|----------	|--------	|------	|
| [NLANGP](http://www.aclweb.org/anthology/S15-2083)   	| 50.86* 	| 2014 	|
| [Sentiue](http://alt.qcri.org/semeval2015/cdrom/pdf/SemEval130.pdf)  	| 50.00* 	| 2014 	|
| IHS-RD   	| 49.59  	| 2014 	|
| NLANGP   	| 49.06  	| 2014 	|
| TJUdeM   	| 46.49  	| 2014 	|
| UFRGS    	| 44.95  	| 2014 	|
| UFRGS    	| 44.73  	| 2014 	|
| V3       	| 24.94  	| 2014 	|

Dataset: Restaurants (train: 254 review texts, test: 96 review texts)

Domain: `Restaurants`

Aspect Categories: 6 entity labels (RESTAURANT, FOOD, DRINKS, AMBIENCE, SERVICE, LOCATION), 5 attribute labels (GENERAL, PRICES, QUALITY, STYLE & OPTIONS, MISCELLANEOUS)

| Method    | Result | Year |
|-----------|--------|------|
| [NLANGP](http://www.aclweb.org/anthology/S15-2083)    | 62.68* | 2014 |
| [NLANGP](http://www.aclweb.org/anthology/S15-2083)    | 61.94* | 2014 |
| [UMDuluthC](http://alt.qcri.org/semeval2015/cdrom/pdf/SemEval126.pdf) | 57.19  | 2014 |
| [UMDuluthT](http://alt.qcri.org/semeval2015/cdrom/pdf/SemEval126.pdf) | 57.19  | 2014 |
| SIEL      | 57.14  | 2014 |
| Sentiue   | 54.10  | 2014 |
| LT3       | 53.67  | 2014 |
| TJUdeM    | 52.44  | 2014 |
