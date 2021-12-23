# Live Twitter Analysis with PySpark
This repository includes projects about real-time analysis of tweets.

### Project 01 - Real-time tweet counter
Every day there are many highly commented arguments on Twitter becoming trending topics. The aim of the project is to observe in which time slot the most tweets about a chosen topic are sent.

Here's an example of output:
![hawkeye_output](https://github.com/DanielDaduyo/tweets_analysis/blob/main/01%20-%20Real-time%20tweet%20counter/output/hawkeye.jpg)

### Project 02 - Who is the most tweeted?
Within every TV show, there are always people and characters who are highly commented on Twitter. The aim of the project is to create a ranking of the cast of the chosen show based on the amount of tweets about them within the official hashtag.

Here's an example of output:
![GFVIP_output](https://github.com/DanielDaduyo/tweets_analysis/blob/main/02%20-%20Who%20is%20the%20most%20tweeted%3F/output/GFVIP_2021_12_19_cont.jpg)

## Requirements
* Python 3.7.3 or greater
* Java Development Kit 8
```bash
sudo apt-get install openjdk-8-jdk
```
* Scala
```bash
sudo apt-get install scala
```
* Libraries: ```py4j```, ```numpy``` (project 01), ```pandas```, ```matplotlib```, ```seaborn``` (project 02).
* Spark 3.2.0 or greater: Download [here](https://spark.apache.org/downloads.html).
* Consumer key, consumer secret, access token, access secret: Create a [Twitter Developer account](https://developer.twitter.com/en), get your API keys and put them in [tweets_stream.py](https://github.com/DanielDaduyo/tweets_analysis/blob/main/01%20-%20Real-time%20tweet%20counter/tweets_stream.py).

## References
* Recommended courses: [ProfessionAI](https://www.profession.ai) (Italian).
* You can find me on [Twitter](https://twitter.com/DaniDaduyo).
