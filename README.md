### Title

* Docker Container Administration - Linux (Ubuntu) and Windows (MS SQL Server) Images

### About / Synopsis

* The purpose of this project is to demonstrate the ease of administrating containers using Docker by installing a variety of images including a Linux Ubuntu server as well as a Windows SQL server that MS SQL Server Management Studio application can connect to and build a database upon.

### Detailed Description 

* Docker Desktop (for Windows) is installed and setup without any issues
![image](https://user-images.githubusercontent.com/46364751/179987165-445e3450-dfcc-4a8e-bb9f-3ba49ef3090d.png)

* Using Command Prompt (cmd), the version of Docker is reviewed
![image](https://user-images.githubusercontent.com/46364751/179987222-51d26e44-2e56-46f6-8b43-e2a830ebf3b4.png)

* Docker commands to install a Linux server are run, tested and validated to confirm Linux container is operational as expected

![image](https://user-images.githubusercontent.com/46364751/180000683-cb94b42a-8a2a-4d6c-b9f0-28a913fee6d8.png)

  ![image](https://user-images.githubusercontent.com/46364751/180000889-561897f0-b8b6-412b-861b-a475413ee273.png)

* The Linux container is renamed from the random name selected by Docker to a project-relevant name - "deepto_dockr_linux_contanr"
![image](https://user-images.githubusercontent.com/46364751/180000990-025976b1-801b-437d-a2d8-f69a5ecaf0f9.png)

* The "deepto_dockr_linux_contanr" is re-attached, re-entered into to validate no issues in server functionality, stopped and finally removed, demonstrating ease of administration

![image](https://user-images.githubusercontent.com/46364751/180005268-16e69c5a-84bf-416c-80ec-51d35964df95.png)


* Within Docker Desktop application, the "Switch to Windows containers" option is selected next

![image](https://user-images.githubusercontent.com/46364751/180002298-fcad4b54-c298-40fe-843e-19b95e079286.png)

* Within the Docker Hub Marketplace, a free MS SQL Server image is found - "spring2/sqlserver" and downloaded

![image](https://user-images.githubusercontent.com/46364751/180005483-13a31f8a-a550-4a0f-90c9-d0af281358f2.png)


![image](https://user-images.githubusercontent.com/46364751/180003475-4478821a-4791-41f4-aef9-6d0c1f289100.png)

* Upon completion of downloading, the SQL Server container is triggered by connecting the ports of the virtual container to the physical computer via the hypervisor, along with system administrator login credentials
![image](https://user-images.githubusercontent.com/46364751/180005634-4a3ebbea-f194-42a1-a9e8-acd890dd2422.png)

* The IP address of the Docker Windows container is retrieved and leveraged within the MS SQL Server Managment Studio (SSMS) application

![image](https://user-images.githubusercontent.com/46364751/180005803-d3689e71-995e-45d2-a75f-800a77fe778e.png)

![image](https://user-images.githubusercontent.com/46364751/180006006-d1d58e60-32fc-4d1c-a71d-86f5b65e335e.png)


* A database [Deepto_Shop.] is created on the Docker SQL Server image along with some custom sample tables via some INSERT SQL statements run in SSMS [e.g. dbo.Product]

![image](https://user-images.githubusercontent.com/46364751/180006147-c6e7496d-dba9-439d-851f-9ed15cef9675.png)


* The Powershell instance of the Docker MS SQL Server container is entered into using a "docker exec" commands and all the databases in this SQL Server are copied over to the shared folder between the Docker image and the physical computer
![image](https://user-images.githubusercontent.com/46364751/180004398-083aa071-2edd-43bf-ad38-f86a43f08bd9.png)

* Finally, the Docker container image is removed/uninstalled
![image](https://user-images.githubusercontent.com/46364751/180004500-2ddb0d05-4240-48b7-a3a5-85284ad8472b.png)

* The log files for the Docker Windows container and Powershell shell instance within have been made available for download/review

* The databases within the MS SQL Server container, inclduing the custom "Deepto_Shop" database have been made available along with "Deepto_Shop_INSERT.sql" script


### Installation / Software Requirements

* The following tool was used in this project:

	* Docker 20.10.17
	

### License / Citation

* Docker Subscription Agreement: https://www.docker.com/legal/docker-software-end-user-license-agreement/
* Docker Hub Marketplace: https://hub.docker.com


### Support

* This project is a standalone development initiative without any ongoing support

