# Logstash OSS

Logstash is part of the [Elastic Stack](https://www.elastic.co/products) along with Beats, Elasticsearch and Kibana. Logstash is a server-side data processing pipeline that ingests data from a multitude of sources simultaneously, transforms it, and then sends it to your favorite "stash." (Ours is Elasticsearch, naturally.). Logstash has over 200 plugins, and you can write your own very easily as well.

For more info, see <https://www.elastic.co/products/logstash>

## Documentation and Getting Started

You can find the documentation and getting started guides for Logstash
on the [elastic.co site](https://www.elastic.co/guide/en/logstash/current/getting-started-with-logstash.html)

For information about building the documentation, see the README in https://github.com/elastic/docs

## Downloads

You can download officially released Logstash binaries, as well as debian/rpm packages for the
supported platforms, from [downloads page](https://www.elastic.co/downloads/logstash).

## Need Help?

- [Logstash Forum](https://discuss.elastic.co/c/logstash)
- [Logstash Documentation](https://www.elastic.co/guide/en/logstash/current/index.html)
- [#logstash on freenode IRC](https://webchat.freenode.net/?channels=logstash)
- [Logstash Product Information](https://www.elastic.co/products/logstash)
- [Elastic Support](https://www.elastic.co/subscriptions)


## Docker file

```sh
.
├── docker-compose.yml
├── logstash
    ├── config
    │   └── logstash.yml
    └── pipeline
        └── pipeline.conf
```