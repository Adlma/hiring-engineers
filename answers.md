
Collecting Metrics:

Add tags in the Agent config file and show us a screenshot of your host and its tags on the Host Map page in Datadog.
=> see screenshot tags_host and tags_host2

Install a database on your machine (MongoDB, MySQL, or PostgreSQL) and then install the respective Datadog integration for that database.
=> see screenshot mysql

Create a custom Agent check that submits a metric named my_metric with a random value between 0 and 1000.
=> see code.

Change your check's collection interval so that it only submits the metric once every 45 seconds.
=> screenshot my_metric2
=> => screenshots metrics1 and my_metric show the integration of the code in the datadog web interface.


Bonus Question Can you change the collection interval without modifying the Python check file you created?
maybe change it in the main check run loop.


links to Dashboards :
Mysql : https://app.datadoghq.com/dash/integration/12/mysql---overview?live=true&page=0&is_auto=false&from_ts=1527499338475&to_ts=1528104138475&tile_size=m 
