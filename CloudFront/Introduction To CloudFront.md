# Introduction to CloudFront

## What is a CDN?

A content delivery network (CDN) is a system of distributed servers (network) that deliver webpages and other web content to a user based on the geographic locations of the user, the origin of the webpage and a content delivery server.

## CloudFront - Key Terminology

- Edge Location - This is the location where content will be cached. This is separate to an AWS Region/AZ
- Origin - This is the origin of all the files that the CDN will distribute. This can be either an S3 Bucket, an EC2 Instance, an Elastic Load Balancer or Route53.
- Distribution - this is the name given to the CDN which consists of a collection of Edge Locations.
- Web Distribution - Typicall used for Websites
- RTMP - Used for Media Streaming

## What is CloudFront?

Amazon CloudFront can be used to deliver your entire website, including dynamic, static, streaming, and interactive content using a global network of edge locations. Requests for your content are automatically routed to the nearest edge location, so content is delivered with the best possible performance.

Amazon CloudFront is optimized to work with other Amazon Web Services, like S3, EC2, Elastic Load Balancing, and Route53. CloudFront also works seamlessly with any non-AWS origin server, which stores the original, definitive versions of your files.

## Exam Tips

- Edge Location - This is the location where content will be cached. This is separate to an AWS Region/AZ.
- Origin - This is the origin of all the files that the CDN will distribute. This can be either an S3 Bucket, and EC2 Instance, an Elastic Load Balancer, or Route53
- Distribution - Name given to CDN which consists of a collection of Edge Locations
	- Web Distribution - Tyicall used for websites.
	- RTMP - Used for media streaming.
- Edge locations are not just for READ only, you can write to them too (i.e. put an object into them).
- Objects are cached for the life of the TTL (Time To Live).
- You can clear cached objects, but you will be charged.