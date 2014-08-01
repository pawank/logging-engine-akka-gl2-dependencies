logging-engine-akka-gl2-dependencies
====================================

Logging engine dependencies - elasticsearch, graylog2-server and graylog2-web
You don't need to run these dependencies if you don't want to send log events to graylog2.

Steps to run:
1. cd elasticsearch-0.90.10; ./run.sh
2. cd graylog2-server-0.20.6;./run.sh
3. cd graylog2-web-interface-0.20.6; ./run.sh
(Go to http://localhost:9000 and use admin/admin crendentials to login)
For web interface of graylog2, please add GELF UDP port 12210 through inputs.
