# Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.



## CREATING A DISK PARTITION:
Step1: Open File Manager
● Right-click This PC → Click Show More Options.

● Select Manage.

Step2: Access Disk Management
● In the new window, select Disk Management.

Step3: Shrink the C Drive to Allocate Space
• Locate C: drive → Right-click → Select Shrink Volume.
• Enter the amount of memory to allocate for the new disk.
• Click Shrink.

Step4: Create a New Volume
• Right-click on the newly unallocated space → Select New Simple Volume.

• Follow the wizard and assign a disk name.

• Click Finish to complete the process.

• The new Disk Partition is created




## ANALYSING FILES USING AUTOPSY:
Step1: Create a Case
• Enter a case name and select a location to store the case data.

• Provide a case number and investigator details if required.

Step2: Add a Data Source
• Click "Add Data Source" and choose the type:

• Select the data source and let Autopsy process it.
Step3: File Analysis
• Application

<img width="1687" height="999" alt="image" src="https://github.com/user-attachments/assets/cbdf6f72-9d0b-4782-9707-71cc096e9689" />



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/618dc9f6-2ae2-4c5b-8587-41645c963e6f" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/169de6ea-abad-4134-86a0-5dc0d4cbcf48" />



• File Metadata



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d149f4ca-7ff0-4e18-9cbb-758753aa3a15" />






## OUTPUT:

• Generate Report

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1681b9a3-170e-4e59-a3bc-f09e0ec36e35" />


## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
