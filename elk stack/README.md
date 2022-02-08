
https://github.com/deviantony/docker-elk 를 참고해서 만든 ELK 스택

ELK 스택


1. ElasticSearch

2. LogStash

3. Kibana

4. Beats


fileBeat는 각 서비스에 설치를 해서 LogStash로 로그를 전달 

Logstash에서 fileBeat에서 보낸 로그들을 처리해서 ElasticSearch로 전달 

ElasticSearch에 저장된 로그 파일들을 Kibana에서 확인
