# FILE-RECOVERY-USING-AUTOPSY-SOFTWARE

## AIM
To use **Autopsy Digital Forensics Tool** to retrieve deleted files from a disk image.

---

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tool**: [Autopsy Digital Forensics](https://www.autopsy.com/)  
- **Test Data**: Disk image file (`disk.dd`, `disk.img`, `.E01`)

---

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Run File System & Data Recovery Modules"]
    E --> F[Locate Deleted Files in Results]
    F --> G[Recover and Export Deleted Files]
```
## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:

### Create a New Case

![alt text](<Screenshot 2025-09-10 083741.png>)

![alt text](<Screenshot 2025-09-10 083757.png>)

### Add Disk Image

![alt text](<Screenshot 2025-09-10 083812.png>)

### Run Ingest Modules

![alt text](<Screenshot 2025-09-10 083852.png>)

### Locate Deleted Files

![alt text](<Screenshot 2025-09-10 084039.png>)

### Export Deleted Files

![alt text](<Screenshot 2025-09-10 084900.png>)

## OUTPUT:

![alt text](<Screenshot 2025-09-10 084900.png>)

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
