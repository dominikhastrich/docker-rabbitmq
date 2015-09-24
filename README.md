# docker-rabbitmq

Official RabbitMQ image extended by enabled Mqtt, Stomp and Web-Stomp Plugins  
Optionally the management tag also enables management plugin  
Further uses NGINX as proxy to expose web-stomp via port 80

| port | target |
|------|--------|
| 5672 | AQMP |
| 15672 | Management interface (only with management tag) |
| 61613 | Stomp |
| 15674 | Web-Stomp (SockJS) |
| 80 | Proxy to Web-Stomp (SockJS) |

Uses *latest* tag of the image
