# Grafana-Loki-Promtail-Rsyslog
Integration of Rsyslog in Promtail -> Loki -> Grafana. 

This stack makes use of the official Grafana and Loki image.
I have editted the Promtail docker image for rsyslog reception. The rsyslog messages then get tagged and sent to the promtail socket from where they get forwarded to loki to be processed by Grafana. 

<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
<p>Grafana image:  https://hub.docker.com/r/grafana/grafana:latest</p>
<p>Loki https://hub.docker.com/r/grafana/loki image: grafana/loki:2.9.0</p>
<p>Promtail image: https://hub.docker.com/r/bloedlink/promtail_rsyslog:latest</p>
