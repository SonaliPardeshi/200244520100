# Snapshot

-	We can create a snapshot of volume or instance.
-	It can be used as a backup.
-	It can also be used as a format, base line for new volumes.
- 	Snapshots are **incremental** 
		If we take snapshot of same volume multiple times, new snapshots saves the data which is added after previous snapshot.
-	Snapshots taken from encrypted volume are automatically encrypted.






## Creating a Snapshot

Use the following procedure to create a snapshot from the specified volume.

1.	To create a snapshot using the console

2.	Open the Amazon EC2 console at https://console.aws.amazon.com/ec2/.

3.	Choose Snapshots under Elastic Block Store in the navigation pane.

4.	Choose Create Snapshot.

5.	For Select resource type, choose Volume.

6.	For Volume, select the volume.

	- 	(Optional) Enter a description for the snapshot.

	-	(Optional) Choose Add Tag to add tags to your snapshot. For each tag, provide a tag key and a tag value.

7.	Choose Create Snapshot.


Reference : https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-creating-snapshot.html