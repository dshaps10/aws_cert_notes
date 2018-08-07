# Snowball

## Import/Export Disk

AWS Import/Export Disk accelerates moving large amounts of data into and out of the AWS cloud using portable storage devices for transport. AWS Import/Export Disk transfers your data directly onto and off of storage devices using Amazon's high-speed internal network and bypassing the internet.

## Types of Snowball

- Snowball
- Snowball Edge
- Snowmobile

## Snowball

- Petabye-scale data transport that uses secure appliances to transfer large amounts of data into and out of AWS. 
- Address common challenges with large-scale data transfers (e.g. network costs, long transfer times, and security concerns)
- Simple, fast, secure, and can be as little as 1/5 cost of high-speed internet.
- 80TB snowball in all regions
- Uses multiple layers of security designed to protect data
	- Tamper resistant enclosures
	- 256-bit encryption
	- Industry-standard Trusted Platform Module (TPM) ensures security and chain-of-custory of data
- AWS performs software erasure of Snowball appliance after successful data transfer

## Snowball Edge

- Contains 100TB of data
- on-board storage *and* compute capabilities
- Can be used to move large amounts of data in and out of AWS as temporary storage tier for large datasets or to support local workloads in remote or offline locations
- Connects existing applications and infra using standard storage interfaces
	- This streamlines data transfer process and minimizes setup and integration
- Can cluster together to fomr local storage tier and process data on-premises, off-line

## Snowmobile

- Exabyte-scale data transfer services
- Used to move extremely large amounts of data to AWS.
- Can transfer up to 100PB per Snowmobile, a 45-foot long ruggedized shipping container, pulled by a semi-trailer truck.
- Makes it easy to move massive volumes of data to the cloud
	- Video libraries
	- Image repositories
	- Complete data center migration
- Secure, fast, and cost-effective

## Exam Tips

- Understand what Snowball is
- Understand what Import/Export is (legacy product)
- Snowball can:
	- Import to S3
	- Export from S3
