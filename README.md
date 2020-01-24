# subreddit_twitter_scrape

Getting data from reddit, twitter and allow user to search

# technologies used
**Scrapy & Scrapyd** to get data from reddit

**GetOldTweets3** accessing old tweets

**Celery & Rabbitmq** schedule jobs to get data from twitter

**Elasticsearch** to allow user search on data

**Flask**  for rest endpoints

**Angular** for frontend

### Example

requires [Docker Compose](https://docs.docker.com/compose/) to run.

### Run example.

``` sh
cd subreddit_twitter_scrape
./run --normal # to run example
./run --test # to run backend testing
# press D at any time to stop
```

navigate to [http://localhost/](http://localhost/) to start adding jobs for collecting data and search.
