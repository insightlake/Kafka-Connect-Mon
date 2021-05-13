
## Kafka-REST-Monitor
<img style="width:100%;" src="images/restmon.png">


Kafka REST Monitor solution monitors REST endpoints of Connect, Schema Regitry, KSQL, Control Center, REST Proxy. It also monitors Connect task status and generate email alerts on failure. 


To learn more, check out [http://insightlake.com/kafkavalidator.html](http://insightlake.com/kafkavalidator.html)

Installation
------
* Download or clone the repository. 
* Run bin/insightlake command.


## Demo Link
https://insightlake.s3.amazonaws.com/releases/kafka-rest-mon/index.html

License - Free for commercial use
------
InsightLake Data Explorer is a commercial product but distributed to be used freely. Please contact contact@insightlake.com for details.

Getting Help
----------


Installation
------
* Download or clone the repository. 
* Run bin/insightlake command.
* Change configuration in /conf folder to set different ports
* By default H2 database is used, you can change the database details in jdbc.properties file
* After starting Application there is two jobs started one is getting connectors information and secound one is check connector status if connector status fail
  it will send email with stack detail on configured email which can configured in application.properties file in conf folder
* Also we can configure job execution time in milliseconds 

You can get help easily :
Slack Channel - [Join InsightLake Slack Community](https://join.slack.com/t/insightlake/shared_invite/enQtNzQzMDE3MDI4ODA1LWM2YmI5MDUzODM5ZjQzZjE3ZDk1MjhiNThjMTBkODJjMGU2OWJmOWQ0MDE5NGI4YjYyYjVhZjEzYzY3YzIzMjY)

Twitter - https://twitter.com/InsightLake

Facebook - https://www.facebook.com/insightlake/


