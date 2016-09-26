# Filebeat 介绍
- 虽然Logstash也具有日志收集和传输功能，但对于多数情况下，Logstash显得太笨重（需要跑在JVM中），如果只是简单的传输日志，Filebeat更轻量（由go语言编写）
- Filebeat支持多种输入方式，最常用是文件，通过监控日志文件内容的变化，将最新的记录传输到指定的输出方式
- Filebeat支持多种输出方式，可以输出到文件、redis或者kafka等，使用十分灵活
- Filebeat十分适合部署到日志产生的源服务器上
