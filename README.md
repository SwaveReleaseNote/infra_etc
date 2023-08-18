# infra_etc

우리누리 서비스 설정에 필요한 기타 설정 파일입니다.

opensearch 의 인덱스 매핑 정보 (nori 형태소 분석기와 ngram이 적용되어 있습니다)
Kafka connector의 설정 (Mysql -> Opensearch)

그리고 해당 설정 정보를 적용하기 위해 opensearch에 nori plug-in을 설치한 opensearch docker image와
debezium connector와 opensearch sink connector를 설치한 kafka docker image를 생성하는 Dockerfile도 포함 되어 있습니다.
