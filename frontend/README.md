# Vote app && Result app

Both are part of front-end where vote-app used for voting process to choose A or B.
Result app displays resoult of voting.

## Docker image build & run & publish to repository

```
docker build -t vote-app:v1 .
docker run -d -p 80:80 vote-app:v1 
docker publish
```