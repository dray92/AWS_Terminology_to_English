# AWS_to_English
Drawing parallels to make AWS instance names more accessible [[Reference](https://www.expeditedssl.com/aws-in-plain-english)]
_______________


### App Service
===============
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
