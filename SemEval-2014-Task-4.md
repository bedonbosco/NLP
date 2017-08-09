[SemEval 2014 Task 4](http://alt.qcri.org/semeval2014/task4/): Sentiment analysis is increasingly viewed as a vital task both from an academic and a commercial standpoint. The majority of current approaches, however, attempt to *detect the overall polarity* of a sentence, paragraph, or text span, regardless of the entities mentioned (e.g., laptops, restaurants) and *their aspects* (e.g., battery, screen; food, service). By contrast, this task is concerned with *aspect based sentiment analysis* (ABSA), where the goal is to *identify the aspects* of given target entities and the sentiment expressed towards each aspect. Datasets consisting of customer reviews with human-authored annotations identifying the mentioned aspects of the target entities and the sentiment polarity of each aspect will be provided.

**Dataset**

* `Laptops` (train: 3045 sentences, test: 800 sentences)
* `Restaurants` (train: 3041 sentences, test: 800 sentences)

**Subtask: Aspect term extraction**

Dataset: `Laptops`

| Method   	| F1     	| Year 	|
|----------	|--------	|------	|
| IHS_RD  	| 74.55* 	| 2014 	|
| DLIREC 	| 73.78* 	| 2014 	|
| DLIREC   	| 70.4  	| 2014 	|
| NRC-Can   	| 68.56  	| 2014 	|

Dataset: Restaurants

| Method   	| F1    	| Year 	|
|----------	|--------	|------	|
| DLIREC  	| 84.01* 	| 2014 	|
| XRCE 	        | 83.98* 	| 2014 	|
| NRC-Can.   	| 80.18  	| 2014 	|
| UNITOR   	| 80.09  	| 2014 	|

**Subtask: Aspect term polarity**

Dataset: `Laptops`

| Method   	| Accuracy     	| Year 	|
|----------	|--------	|------	|
| DCU  	        | 70.48* 	| 2014 	|
| NRC-Can.  	| 70.48* 	| 2014 	|
| SZTE-NLP   	| 66.97 	| 2014 	|
| UBham   	| 66.66  	| 2014 	|

Dataset: `Restaurants`

| Method   	| Accuracy    	| Year 	|
|----------	|--------	|------	|
| DCU    	| 80.95* 	| 2014 	|
| NRC-Can. 	| 80.15* 	| 2014 	|
| UWB   	| 77.68  	| 2014 	|
| XRCE   	| 77.68  	| 2014 	|

**Subtask: Aspect category detection**

Dataset: `Restaurants`

| Method   	| F1     	| Year 	|
|----------	|--------	|------	|
| NRC-Can  	| 88.57* 	| 2014 	|
| UNITOR  	| 85.26* 	| 2014 	|
| XRCE   	| 82.28 	| 2014 	|
| UWB   	| 81.55  	| 2014 	|

**Subtask: Aspect category polarity**

Dataset: `Restaurants`

| Method   	| F1     	| Year 	|
|----------	|--------	|------	|
| NRC-Can.  	| 82.92* 	| 2014 	|
| XRCE   	| 78.14* 	| 2014 	|
| UNITOR   	| 76.29 	| 2014 	|
| SAP_RI   	| 75.6  	| 2014 	|