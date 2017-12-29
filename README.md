# Elasticsearch with django

##### Made with this [article](https://medium.freecodecamp.org/elasticsearch-with-django-the-easy-way-909375bc16cb) by Adam Watt

### Installing ElasticSearch

```
mkdir elasticsearch

wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-5.1.1.tar.gz

tar -xzf elasticsearch-5.1.1.tar.gz

./elasticsearch-5.1.1/bin/elasticsearch
```
To check that its up and running correctly open up a new terminal window and run this curl command:

```
curl -XGET http://localhost:9200
```

The response should be something like this:

```
{
  "name" : "6xIrzqq",
  "cluster_name" : "elasticsearch",
  "cluster_uuid" : "eUH9REKyQOy4RKPzkuRI1g",
  "version" : {
    "number" : "5.1.1",
    "build_hash" : "5395e21",
    "build_date" : "2016-12-06T12:36:15.409Z",
    "build_snapshot" : false,
    "lucene_version" : "6.3.0"
  },
  "tagline" : "You Know, for Search"
```
