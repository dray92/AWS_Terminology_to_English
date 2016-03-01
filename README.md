# AWS_to_English
Drawing parallels to make AWS instance names more accessible [[AWS Docs](http://aws.amazon.com/documentation/)]  [[Reference](https://www.expeditedssl.com/aws-in-plain-english)]
===============


## App Service
_______________
###### EC2
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
|  Amazon Virtual Servers      | Host the bits of things you think of as a computer.  | [http://www.linode.com](http://www.linode.com), It's handwavy, but EC2 instances are similar to the virtual private servers you'd get at Linode, DigitalOcean or Rackspace. |
===============
###### IAM
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
| Users, Keys and Certs     | Set up additional users, set up new AWS Keys and policies.   |   |
===============
###### S3
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
| Amazon Unlimited FTP Server     | Store images and other assets for websites. Keep backups and share files between services. Host static websites. Also, many of the other AWS services write and read from S3.    |   |
===============
###### VPC
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
| Amazon Virtual Colocated Rack   | Overcome objections that "all our stuff is on the internet!" by adding an additional layer of security. Makes it appear as if all of your AWS services are on the same little network instead of being small pieces in a much bigger network.    |  For the networking folks, this is like VLAN. |
===============
###### Lambda
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
| AWS App Scripts     | Run little self contained snippets of JS, Java or Python to do discrete tasks. Sort of a combination of a queue and execution in one. Used for storing and then executing changes to your AWS setup or responding to events in S3 or DynamoDB.    |   |
===============
===============

## Web Developer Services
_______________
###### API Gateway
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
|  API Proxy      | Proxy your apps API through this so you can throttle bad client traffic, test new versions, and present methods more cleanly.  | 3Scale |
===============
###### RDS
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
|  Amazon SQL 	| Be your app's Mysql, Postgres, and Oracle database. 	| Heroku Postgres |
===============
###### Route53
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
|  Amazon DNS + Domains 	| Buy a new domain and set up the DNS records for that domain. |DNSimple, GoDaddy, Gandi |
===============
###### SES
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
|  Amazon Transactional Email 	| Send one-off emails like password resets, notifications, etc. You could use it to send a newsletter if you wrote all the code, but that's not a great idea. 	| SendGrid, Mandrill, Postmark |
===============
###### Cloudfront
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
|  Amazon CDN 	| Make your websites load faster by spreading out static file delivery to be closer to where your users are. | MaxCDN, Akamai |
===============
###### CloudSearch
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
|  Amazon Fulltext Search 	| Pull in data on S3 or in RDS and then search it for every instance of 'Jimmy.' 	| Sphinx, Solr, ElasticSearch |
===============
###### DynamoDB
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
|  Amazon NoSQL 	| Be your app's massively scalable key valueish store. 	| MongoLab |
===============
###### Elasticache
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
|  Amazon Memcached 	| Be your app's Memcached or Redis. 	| Redis to Go, Memcachier |
###### Elastic Transcoder
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
|  Amazon Beginning Cut Pro | Deal with video weirdness (change formats, compress, etc.). |  |
###### SQS
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
|  Amazon Queue 	| Store data for future processing in a queue. The lingo for this is storing "messages" but it doesn't have anything to do with email or SMS. SQS doesn't have any logic, it's just a place to put things and take things out. 	| RabbitMQ, Sidekiq |
###### WAF
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
|  AWS Firewall 	| Block bad requests to Cloudfront protected sites (aka stop people trying 10,000 passwords against /wp-admin) 	| Sophos, Kapersky |
===============
===============

## Mobile App Development
_______________
###### Cognito
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
|  Amazon OAuth as a Service 	| Give end users - (non AWS) - the ability to log in with Google, Facebook, etc. 	| OAuth.io |
===============
###### Device Farm
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
|  Amazon Drawer of Old Android Devices 	| Test your app on a bunch of different IOS and Android devices simultaneously. |
MobileTest, iOS emulator |
===============
###### Mobile Analytics
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
|  N/A 	| Track what people are doing inside of your app. | Flurry |
===============
###### SNS
| Really Means        | Purpose           | Reference  |
|:------------: |:-------------:| :-----:|
|  Amazon Messenger 	| Send mobile notifications, emails and/or SMS messages | UrbanAirship, Twilio |
===============
===============

## Ops and Code Deployment Services
_______________
