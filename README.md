# logstash v1.0
1) Download, Config Logstash 1.4.2
2) Add auto create index to ES Config (elasticsearch.yml)
          action.auto_create_index: logstash*
3) Update the logstash conf for your IIS log path and ES instance
4) Run logstash > logstash agent -f logstash_iis.conf OR configure to run as SERVICE

