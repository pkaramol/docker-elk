# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:5.6.1

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-input-syslog

EXPOSE 5151 5152 5153 5154 5155 5156 5157 5158
