Mongodb (mongodbMonitor) Release Notes
Last Updated Aug 16, 2020

The MongoDB Monitoring (mongodbMonitor) probe allows you to monitor real-time events occurring in the Mongodb server. 
The probe provides parameters to measure the real-time database operations.
You can then diagnose and resolve these issues, and take preventive measures to ensure an optimal server run time.

Probe Specific Hardware Requirements
	Memory: 2-4 GB RAM

Probe Specific Software Requirements
	Install mongodb client in directory C:\MongoDB\Server\4.2\bin.(Link to download https://fastdl.mongodb.org/windows/mongodb-windows-x86_64-4.4.0-signed.msi)
	Robot 7.97HF3 or later (recommended)
The probe must be configured on Windows.
 
Installation Considerations
	Install on Hub 


mongodbMonitor Configuration

	robot.cfg 
		add	robotname = <your local robot name>
			os_user2 = <Your site Name>

	mongodbMonitor.dat
		add
		myip = <IP your MongoDB>
		myport = <Port to connection to your MongoDB>
		user = <root>
		pass = <password>
		mongolocate = C:\MongoDB\Server\4.2\bin
		
Drag the file to the archive.
 
