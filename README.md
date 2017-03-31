# Logstash Configuration File Samples

## Dataset Specific Configurations

**datasets/nyc-taxi-yellow-logstash.conf**: Import New York city yewllow cab pick-up and drop-off data set.

**datasets/nyc-taxi-yellow-logstash-translate.conf**: Import New York city yewllow cab pick-up and drop-off data set. Logstash [translate filter](https://www.elastic.co/guide/en/logstash/current/plugins-filters-translate.html) is needed.

## Misc

**misc/reindex.conf**: Perform a reindexing job for Elasticsearch indices

**misc/performance-metrics.conf**: Show performance metrics while processing data

**misc/environment-variables.conf**: Pass an environment variable to the Logstash metadata object

**misc/export-to-csv.conf**: Export indexed documents to a CSV file

**misc/plain-codec.conf**: Convert EUC-JP inputs by plain codec
