[SemEval 2014 Task 4](http://alt.qcri.org/semeval2014/task4/): Sentiment analysis is increasingly viewed as a vital task both from an academic and a commercial standpoint. The majority of current approaches, however, attempt to detect the overall polarity of a sentence, paragraph, or text span, regardless of the entities mentioned (e.g., laptops, restaurants) and their aspects (e.g., battery, screen; food, service). By contrast, this task is concerned with aspect based sentiment analysis (ABSA), where the goal is to identify the aspects of given target entities and the sentiment expressed towards each aspect. Datasets consisting of customer reviews with human-authored annotations identifying the mentioned aspects of the target entities and the sentiment polarity of each aspect will be provided.

**Dataset**

* `Laptops` (train: 3045 sentences, test: 800 sentences)
* `Restaurants` (train: 3041 sentences, test: 800 sentences)

**Subtask: Aspect term extraction**

Dataset: Laptops

| Method   	| Result (F1) 	| Year 	|
|----------	|--------	|------	|
| IHS_RD  	| 74.55* 	| 2014 	|
| DLIREC 	| 73.78* 	| 2014 	|
| DLIREC   	| 70.4  	| 2014 	|
| NRC-Can   	| 68.56  	| 2014 	|

Dataset: Restaurants

| Method   	| Result (F1) 	| Year 	|
|----------	|--------	|------	|
| IHS_RD  	| 74.55* 	| 2014 	|
| DLIREC 	| 73.78* 	| 2014 	|
| DLIREC   	| 70.4  	| 2014 	|
| NRC-Can   	| 68.56  	| 2014 	|


