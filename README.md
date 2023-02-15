# Covid19
A Web Scrapping project

## Overview
The project focus on get data from internet and transfer data to a file in GDrive. The script is scheduled on crontab running 8/8h and sending to GDrive file at midnight all information ready, sanitized, and in good shape.

Outuput is a .csv file.

### There are 3 steps in this project:

1st - Data Web Scrapping from internet.

2nd - Sanitize data preparing the file

3rd - Connect to GDrive and append the data in a file to be read later

Stacks:
- Linux (Shell Scripting/Bash) and Cron
- Python

