#Day2  
28/04/2020


- 3 Models of cloud services : 		
	1) SaaS	(Software as a Srvice)
	2) PaaS	(Platform as a Service)
	3) IaaS 	(Infrastructure as a Service)


**SaaS**
	
- Different softwares are provided directly, no need to download and install at client side.
- User is not responsible for hardware or software update.
- Can be used for short term projects that require quick and affordable collaboration. 

Examples : 
	Tableau, 
	Splunk,
	Storm,etc.
---

**PaaS**

- Instead of providing software, it provides platform for software creation.
- Developer has to focus only on software development without the worrying about O.S., Storage, Saoftware updates, etc.

Examples :
	Hosted db RDS.,
	AWS Elastic Beanstalk,etc.

---

** IaaS**

- Raw computing resources.
- Provides access to resources like - servers,storage and netwroking.

Examples :
	VM: Ec-2
	Volume

---

** Firewall **

- Monitors all incoming and outgoung traffic and accepts, rejests or drops the traffic based on predefined security rules.
- Designed to prevent unautorized access to or from a private network.
- It can be hardware or software based.
- Creates a barrier between private network and outside untrusted networks.

**AWS Firewall - Security Groups **

![Security group](images/sec_group.png)

2 Sets of rules 
	1. Inbound		- Controls incoming traffic
	2. Outbound	- Controls outgoing traffic

- These rules can be used for open/close port while remotely accessing the system.
- We can create different security groups and can manage ports.
- We can use same security group for different instances if needed or can create new group for new instance.


---

**Service 2 : S3** 
S3 - Storage Secured Service
 
- We can store any type of data in form of object.
- Unlimited storage space available.
- **Bucket** needs to be created where we can store our data.
- ** S3 does not require region separation.**
- Bucket name has to be unique across AWS.
- Bucket is like a folder, we can create folders inside it.
- We can upload or download files to or from these folders, but we cannot create a file here.
- **Guarantee of backup** from AWS.
- Can connect with EC2 also.
- We can host a website here.



