# AWS LAMBDA - serverless computing service

**Features**
		
		- You don't own a server.
		- No maintenance.
		- Scalability and parallelization. 

**How it is different?**

-	Ec2 is a server and if it is running then you have to pay for the resources like RAM, core, HD
even if you are not utilizing the resources 100%.

-	In case of serverless,there is a lambda function and no server.
You can store code (unlimited storage space), **no chareges will be applicable for storage of code.**

-	You will be charged only for the time, ypur code is running. 


**Scalability**

- 	Suppose 1st time, your code is using 1 Gb space and 1 core.
And next time your code is updated and now it is using 2gb space then you don't need to worry about the storage scalability feature takes care of this. 
**automatic scale up and down.**

**Parallelization**

-	Lambda creates instances of your function as they are requested.
-	At a time millions of requests are served by same Lambda function.

**Fully managed infrastructure**

-	No need to worry about underlying operating system, upgrades, etc.
-	AWS manages this.

---

**Difference between mysql installed on ec2 and RDS**

**EC2**|**RDS**
---|---
EC2 is managed by AWS but any application installed is managed by developer.|MYSQL server here is fully mangaed by AWS.
Backup, scalability and maintenance- everything managed by admin.|Maintenance,scalability and backup managed by AWS.


---


**About S3**

	-	Everything in s3 bucket is an object.
	-  	Objects are immutable.

**Immutable**
	-	Anything created in bucket cannot be updated.

**Example:**

	Bucket 		: 100-bucket1
	Directory	: Test
	File 		: demo.txt
	Content 	: "Welcome"

- demo.txt file is uploaded and now if you want to change the content, then you have to delete the file, make and upload the updated file again, it cannot be updated there.  		



