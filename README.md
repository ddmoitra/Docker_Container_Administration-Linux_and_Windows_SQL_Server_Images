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

* The Linux container is renamed from the random name selected by Docker to a project-relevan name - "deepto_dockr_linux_contanr"

* The "deepto_dockr_linux_contanr" is re-attached, re-entered into to validate no issues in server functionality, stopped and finally removed, demonstrating ease of administration


* Within Docker Desktop application, the "Switch to Windows containers" option is selected next

* Within the Docker Hub Marketplace, a free MS SQL Server image is found - "spring2/sqlserver" and downloaded

* Upon completion of downloading, the SQL Server container is triggered by connecting the ports of the virtual container to the physical computer via the hypervisor, along with system administrator login credentials

* The IP address of the Docker Windows container is retrieved and leveraged within the MS SQL Server Managment Studio (SSMS) application


* A database [Deepto_Shop.] is created on the Docker SQL Server image along with some custom sample tables via some INSERT SQL statements run in SSMS [e.g. dbo.Product]

* The Powershell instance of the Docker MS SQL Server container is entered into using a docker exec" commands and all the databases in this SQL Server are copied over to the shared folder between the Docker image and the physical computer

* Finally, the Docker container image is removed/uninstalled

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

