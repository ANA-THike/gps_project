# GPS Location Services Project

This project includes scripts and resources to enable location services on a Windows machine and retrieve GPS coordinates. 

## Files in this Repository

1. **file_links.txt**  
   Contains direct download links for the following files:
   - `gps_on.reg` - Registry script to enable location services.
   - `gps.ps1` - PowerShell script to retrieve GPS coordinates.

2. **gps_on.reg**  
   A registry script that enables location services on Windows. This is essential for retrieving GPS coordinates.

3. **gps.ps1**  
   A PowerShell script that fetches the current GPS coordinates of the machine.

## How to Use

### 1. Enable Location Services
- Download the `gps_on.reg` file from the `file_links.txt`.
- Open PowerShell with administrator privileges.
- Run the script using the following command:
  ```powershell
  regedit /s gps_on.reg

### 2. Retrieve GPS Coordinates
- Download the `gps.ps1` file from the `file_links.txt`.
- Open PowerShell with administrator privileges.
- Run the script using the following command:
  ```powershell
  .\gps.ps1
