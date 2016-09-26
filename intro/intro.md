# ELK stack 总体介绍


- Filebeat 轻量级日志传输agent，可以输出到redis或者kafka进行暂存


- Logstash 读取redis或者kafka中的日志，对日志进行过滤和转换，使用正则表达式实现对日志内容的灵活处理，然后输出到Elasticsearch



- Elasticsearch 对输入的数据进行索引，方便进行各类自定义的搜索，支持集群


- Kibana 提供友好的web界面，调用Elasticsearch的API进行搜索，可以编制各类图形图表，提供dashboard进行展示

