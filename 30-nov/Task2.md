## 1. Securing Confidential Documents
**Scenario:**  
You’re managing a folder containing sensitive employee records. Only the HR manager (owner) should have full access, while team leads (group) can only view the files. Others should have no access.  

**Task:**  
- Create a directory called `employee_records` with a file named `salary_details.txt`.  
- Set permissions so:  
  - Owner can read and write.  
  - Group can only read.  
  - Others have no access.  
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 2. Deploying a Website
**Scenario:**
You’re preparing a folder for a website deployment. The web server must execute scripts and read static files, but no one should modify the files directly.

**Task:**  

Create a folder website with files index.html and deploy.sh.
Set permissions so:
All users can read index.html, but only the owner can write.
Only the owner can execute deploy.sh.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 3. Configuring Log Files
**Scenario:**
Log files should be readable by system administrators but not modified or viewed by anyone else.

**Task:**

Create a logs directory with a file system.log.
Set permissions so:
The owner can read and write.
The group can only read.
Others have no access.
