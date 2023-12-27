# Grafana-Loki-Promtail-Rsyslog
Integration of Rsyslog in Promtail -> Loki -> Grafana. 

This stack makes use of the official Grafana and Loki image.
I have editted the Promtail docker image for rsyslog reception. The rsyslog messages then get tagged and sent to the promtail socket from where they get forwarded to loki to be processed by Grafana. 

<table>
    <tr>
    <th>Name</th>
    <th>Url</th>
    <th>Version</th>
  </tr>
  <tr>
  <tr>
    <th>Grafana</th>
    <th>https://hub.docker.com/r/grafana/grafana</th>
    <th>grafana/grafana:latest</th>
  </tr>
  <tr>
    <th>Loki</th>
    <td>https://hub.docker.com/r/grafana/loki</td>
    <td>grafana/loki:2.9.0</td>
  </tr>
  <tr>
    <th>Promtail</th>
    <td>https://hub.docker.com/r/bloedlink/promtail_rsyslog</td>
    <td>bloedlink/promtail_rsyslog:latest</td>
  </tr>
</table>

