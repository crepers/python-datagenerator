# python-datagenerator

Bastion host에서 pyhton을 이용하여 Amazon Kinesis Data Streams 또는 Amazon Kinesis Data Firehose로 데이터를 전송할 수 있습니다.

- 사용방법
```
python3 gen_kinesis_data.py -I clickstream-feed-generated.csv \
--service-name kinesis \
--out-format json \
--stream-name ug2-clickstream
```
