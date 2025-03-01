
---

## GPS Location Services Project

This project contains scripts and resources that enable location services on a Windows machine and allow retrieval of GPS coordinates.

## Files in this Repository

1. **file_links.txt**  
   Contains direct download links for the following files:
   - `gps_on.reg` - Registry script to enable location services.
   - `gps.ps1` - PowerShell script to retrieve GPS coordinates.

2. **gps_on.reg**  
   A registry script to enable location services on Windows. This is essential for retrieving GPS coordinates.

3. **gps.ps1**  
   A PowerShell script to fetch the current GPS coordinates of the machine.

## How to Use

### 1. Enable Location Services
To enable location services on your Windows machine:

- **Step 1**: Download the `gps_on.reg` file from the `file_links.txt`.
  
- **Step 2**: Open **PowerShell** with **Administrator** privileges. You can do this by:
  - Pressing `Win + X`, then selecting **Windows PowerShell (Admin)**.
  
- **Step 3**: Run the registry script using the following command:
  ```powershell
  regedit /s gps_on.reg
  ```
  This will modify the system registry to enable location services.

- **Step 4**: You can now verify that the location service is enabled by checking your system settings, or you can proceed to fetch GPS coordinates.

### 2. Retrieve GPS Coordinates
Once the location services are enabled, you can retrieve the current GPS coordinates by:

- **Step 1**: Download the `gps.ps1` file from the `file_links.txt`.
  
- **Step 2**: Open **PowerShell** with **Administrator** privileges again, if not already open.
  
- **Step 3**: Run the script using the following command:
  ```powershell
  .\gps.ps1
  ```
  The script will fetch and display the current GPS coordinates of your machine.

## Video Guide
For a visual guide, check out the following YouTube video:

[Watch the GPS Location Services Setup Guide on YouTube](https://www.youtube.com/watch?v=ZmH4ldojlcY&t)
