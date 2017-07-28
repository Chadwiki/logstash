# logstash
1. Download, Logstash 5.5.1
          https://www.elastic.co/downloads/logstash
2. Edit/Add auto create index to ES Config (elasticsearch.yml) => 
          action.auto_create_index: logstash*
3. Update the logstash conf for your IIS log path and ES instance
4. Run logstash => logstash agent -f logstash_iis_all_fields.conf OR configure to run as SERVICE

