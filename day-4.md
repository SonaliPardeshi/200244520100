# Day-4 

Communication Between Services in AWS

- Direct communication between EC2 and S3 is not provided by default in AWS.
- We can establish a connection by **attaching policies to roles and roles to EC2.**
- After establishing comminication we can use 
		
		aws cli (Linux)
		sdk (Java,Python,C++,NodeJs)

1. Inside AWS
2. Outside AWS

---

**IAM Roles :  Identity Access Management**

- We can attach IAM roles with any service.
- These roles are nothing but policies.

## Inisde AWS :

**Steps To establish connection:**
		
		1. Create IAM Role
				**Attach existing policy to role**, or we can also create a new policy if needed.
		2. Attach IAM Role to Service i.e.,EC2.

**Command :** 
	
	aws <service_name> [command_option]


**Example :**

Suppose we want to establish connection betweeen EC2 and S3, command would be:

	aws s3 ls

- The above command will list the directory contents/bucket of s3.
- Suppose we have a bucket named 100-bucket1, and want to list the bucket content, then command would be:
	
		aws s3 ls s3://100-bucket1
		OR
		aws s3 ls 100-bucket1

		(The first one is better as it adds readability)

---

**What is Region?**
- Physical location where data center is located.
- Each Region has multiple,isolated and physically separated Availability Zones within a geographic area.


**Availability Zone?**
- Group of logical data center is called as availability zone(AZ).

---

