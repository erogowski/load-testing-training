# load-testing-training
The projects is created for the demonstration purposes during load testing training

Used tools:
- Apache JMeter
- JMeter Maven plugin

Use maven command to execute the tests and generate a test result report:
mvn clean verify
-Dprotocol=https
-Devironment=petstore.swagger.io
-Dauth_token=1234567890
-Dusers=1
-DrampUpTime=1
-Dloops=1