# S3 - Security & Encryption

## Securing your buckets

- By default, all newly created buckets are PRIVATE
- You can setup access control to your buckets using:
	- Bucket Policies
	- Access Control Lists (ACL)
- S3 buckets can be configured to create access logs which log all requests made to the S3 buckeet. This can be done to another bucket.

## Encryption

- In transit:
	- SSL/TLS
- At Rest
	- Server-side encyption
		- S3 Managed Keys - **SSE-S3**
		- AWS Key Management Service, Managed Keys - **SSE-KMS**
			- Advantage of SSE-KMS: Provides you with an audit trail (Helps understand when keys were used and by whom); can manage encryption keys yourself or use auto-generated key
		- Server-side Encryption w/ Customer Provided keys - **SSE-C**
	- Client-side Encryption
		- You encrypt data on client-side and then upload to S3