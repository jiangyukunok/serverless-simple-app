# serverless-simple-app

After running through a few samples through serverless API, it's not hard to figure out the mechanism it works.<br/>
When we create a service, it actually sets up a bunch of aws services, like s3, lambda and so on, and when invoke a method,<br/>
it will trigger the corresponding lambda function in aws.<br/>
The advantage of serverless API is it wraps a lot of manual process together into few commands, which saves efforts to open different<br/>
services in aws management console.

A complete workflow using aws serverless can be like: create database using dynamoDB or RDS, and set up lambda function to access<br/>
or process the db. Then using API Gateway to create handler for http requests.
