# seattle gov data
1. Download, Logstash 5.5.1
          https://www.elastic.co/downloads/logstash
2. Update the logstash conf for your specific data paths and ES instance
3. Import templates 
3. Run logstash => logstash -f <logstash_conf_name>.conf

## Information on data source fields, etc
[Seattle_data.txt](https://github.com/Chadwiki/logstash/blob/master/seattle_gov/Seattle_data.txt)

## To Do:

1) Add conf listing/index
2) Resolve FIXes listed in Conf files
3) FIX data issue
4) FIX common ID field name