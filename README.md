# rabiitmq-docker


docker run -d -p 25671:5672 -p 25672:15672 --name jbilling-rabbit-test -e RABBITMQ_DEFAULT_USER=admin -e RABBITMQ_DEFAULT_PASS=admin -e RABBITMQ_DEFAULT_VHOST=apigw rabbitmq:3.6.8-management
