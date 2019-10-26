# Fluentbit Cloudwatch Dockercompose Example
Just playing around with fluentbit.
This example defines two outputs:
- cloudwatch
- stdout

`docker-compose up` then hit `http://<docker-host>|localhost:8000/`


you need these aws env variables defined with valid creds:
- AWS_ACCESS_KEY_ID
- AWS_SECRET_ACCESS_KEY