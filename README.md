# Backup Assistant
BackupAssistant is a robust .NET Worker Service designed for automating backups of databases, folders, and files. It supports various backup types, including full, differential, and folder-based backups. The application is designed to run as a Windows Service, ensuring consistent and reliable performance for backup operations.

## Technologies Used
* **Programming Language:** C# (.NET 9.0)
* **Framework:** .NET Worker Services
* **Database Management:** SQL Server, SQL Server Management Objects (SMO)
* **Configuration Management:** JSON-based configuration (appsettings.json)
* **Deployment:** Windows Services
* **File I/O:** File compression and recursive directory operations
* **Logging:** .NET integrated logging framework

## Installation
### Download and Run
1. Go to the Releases section of this repository.
2. Download the latest ZIP file containing the published project.
3. Extract the contents of the ZIP file to a directory on your system.
4. Run the 'BackupAssistant.exe' file.
   
#### Register as a Windows Service
[Register the application as a Windows Service using one of these methods](https://learn.microsoft.com/en-us/dotnet/framework/windows-services/how-to-install-and-uninstall-services)

#### Configuration
Before running the application, edit the appsettings.json file located in the extracted folder to set up your backup preferences.


