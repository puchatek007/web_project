# web_project
Web project to learning django, html, css, js  
Django Headless API for managment device with Linux. 
Three User:
  * main user can create and send command.
  * base user can only read data form device.
  * device  

## Assumptions of the project
Colect data from linux device: 
  * get device information
  * get device performance information
  * get network information (ip, mask, dns)
  * get information about RAM, CPU
  * get information form config file

Interaction with device:
  * send command to execute
  * Prepare command for multiple device

Securyti of communication:
  * device connect to django with TOKEN
  * device will be a user
  * device can only read, send, update. Can't create new instance of data

DB:
  * ?

Docker: 
  * Run all in docker
  * Nginx - gunicorn




