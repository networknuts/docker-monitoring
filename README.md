# docker-monitoring
monitoring docker containers using cadvisor, prometheus,redis and grafana
# run - docker-compose up
if everything is working good, you should see this message <br>
msg="Server is ready to receive web requests." <br>
check three containers are running using docker-compose ps
# accessing cadvisor
http://localhost:8080
# accessing prometheus
http://localhost:9090
# running grafana on docker host
docker run -d --name grafana -p 3000:3000 grafana/grafana <br> <br>
Access grafana using
http://localhost:3000
# configure grafana to use prometheus as data source 


