> Amazon Elasticsearch Service 에 바로 물릴 수 있는 Logstash 도커 컴포즈 파일.

&nbsp;

## How to Use

1. /logstash/pipeline/logstash.conf 에서 hosts, aws_access_key_id, aws_secret_access_key 설정
   - ( aws_access_key_id, aws_secret_access_key 는 es에 write 권한을 가진 IAM 계정임)

2. docker-compose up

&nbsp;

결과

<img width="1117" alt="스크린샷 2020-04-04 오후 10 04 12" src="https://user-images.githubusercontent.com/25674959/78451381-43b5ae80-76c0-11ea-8e2e-a64bd6edb403.png">

&nbsp;

키바나

<img width="1435" alt="스크린샷 2020-04-04 오후 10 05 14" src="https://user-images.githubusercontent.com/25674959/78451402-5fb95000-76c0-11ea-9d35-2376abab9a38.png">