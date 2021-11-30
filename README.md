# 6_1_ELK_STACK
## [Full Answer PDF with screenshots](https://github.com/LF-DevOps-Intern/6_1_elk_stack-deesirouss/blob/main/ElasticSearch%26Kibana%20Answer%20in%20PDF.pdf)

A.  Create two linux servers,
     server1 => install and configure kibana and elasticsearch with basic username and password authentication
     server2 => install and configure metricbeat.
## [Answer of Q-A in PDF](https://github.com/LF-DevOps-Intern/6_1_elk_stack-deesirouss/blob/main/A/A-server1%262-setup.pdf)


B.  Collect metric from following sources in server1 and send them to elasticsearch. Store them in an index named "server1-metrics".
    a. Memory usage
    b. Disk usage
    c. Load average
## [Answer of Q-B in PDF](https://github.com/LF-DevOps-Intern/6_1_elk_stack-deesirouss/blob/main/B/B-Collect%20metric.pdf)

  1. Create a dashboard in kibana and generate visual report(line graph) for Memory usage and load average of server1 with relation to time
## [Answer of Q-1 in PDF](https://github.com/LF-DevOps-Intern/6_1_elk_stack-deesirouss/blob/main/1/1-dashboard.pdf)

  2. Generate alerts through kibana system for following thresholds
    a. when memory usage > 80% for last 2 minutes send alert to a slack channel
    b. When Disk usage > 70%   send alert to a slack channel
    c. When load average > 1  for last 2 minutes  send alert to a slack channel
## [Answer of Q-2 in PDF](https://github.com/LF-DevOps-Intern/6_1_elk_stack-deesirouss/blob/main/2/2-alerts.pdf)
