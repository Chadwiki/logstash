### ZyXel networking CEF/syslog -

Based off of the following CEF example: https://github.com/elastic/examples/tree/master/Common%20Data%20Formats/cef

Cef codec plugin | Logstash Reference [6.2] | Elastic
https://www.elastic.co/guide/en/logstash/current/plugins-codecs-cef.html


#### Kibana dashboard
```
wget https://raw.githubusercontent.com/Chadwiki/logstash/master/zyxel_cef/dashboard.json
```

+ Update template for new types:

+ Logstash:
    Add new fields,
    Internal IP conditions

+ Document:
    next steps more..
