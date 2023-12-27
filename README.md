# Grafana-Loki-Promtail-Rsyslog
Integration of Rsyslog in Promtail -> Loki -> Grafana. 

This stack makes use of the official Grafana and Loki image.
I have editted the Promtail docker image for rsyslog reception. The rsyslog messages then get tagged and sent to the promtail socket from where they get forwarded to loki to be processed by Grafana. 
