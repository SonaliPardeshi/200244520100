# Comparison between AMI and Snapshot

- 	Snapshots are associated with EBS and you can create multi-volume snapshots, AMIs are associated with ec2 instances.

-	You can launch multiple instances from a single AMI when you need multiple instances with the same configuration.

- 	AMI can include one or more snapshots.

-	When you create a snapshot for an EBS volume that serves as a root device, you should stop the 	instance before taking the snapshot.

-	If we snapshot of instance, we get copy of all softwares, applications installed in it already.

-	Snapshots are the backup of the data on EBS volumes, whereas AMIs are bootable copy of the whole EC2 instances.
