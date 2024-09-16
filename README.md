# Cronjob-for-scrapy-scripts

CRONTAB settings
***********************************************************
1. This command will run the job for every 15th minute.
2. This command first activate the virtual environment and then runs the script.

*/15 * * * * /usr/bin/env bash -c 'source /home/ubuntu/zomatoHouse/zomatovenv/bin/activate && cd /home/ubuntu/zomatoHouse/zomatoHouse/spiders/ && scrapy runspider zomatoProxies.py' > /dev/null 2>&1

