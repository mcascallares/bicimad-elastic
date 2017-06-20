# BiciMad

## Overview

BiciMAD is the public bike service in Madrid. It started in 2014 and currently, it is a popular transportation service in the Spanish capital.

In this demo, we are sampling BiciMAD APIs periodically using Logstash, collecting station information like number of bikes/slots in real time, indexing them into Elasticsearch and visualise it using Kibana.


## Requirements

- Elasticsearch v5.4.0+
- Logstash v5.4.0+
- Kibana v5.4.0+
- [logstash-filter-translate](https://www.elastic.co/guide/en/logstash/5.4/plugins-filters-translate.html)
- [(Optional) Elastic Basic License](https://www.elastic.co/subscriptions) for higher zoom levels in Kibana maps


## Usage
```
export API_USER="your_bicimad_api_user"
export API_KEY="your_bicimad_api_key"
logstash -f logstash.conf
```

## Screenshots

## API Information

- [Open Data EMT Madrid](http://opendata.emtmadrid.es/getdoc/2f7fdbf1-f849-4357-9778-cbd5c4ebc27c/default.aspx)