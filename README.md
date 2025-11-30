# Cloud-Download-Tool-
A snappy python and html server to download files and unzip them in your cloud servers of choice. Made for people who have more to download the space on the device their downloading it on!

How To Use: You need 3 files in the same folder:

pcloud_proxy_server.py - The server
pcloud_app.html - The web interface
config.py - Simple configuration (optional)

Step 2: Run the Server
bashpython3 pcloud_proxy_server.py
That's it! The server starts immediately.

☁️ Supported Cloud Services
1. pCloud ✅ (Fully Working)

Users log in with their pCloud email and password
Full upload/download support
Auto-creates folders

2. Google Drive 📁 (User Login)

Users log in with their Google credentials
Recommended: Use App Passwords for security
How to create App Password:

Go to Google Account → Security
Enable 2-Step Verification
Go to "App passwords"
Generate password for "Mail" or "Other"
Use that 16-character password in the app



3. OneDrive 📂 (User Login)

Users log in with their Microsoft account credentials
Works with personal Microsoft accounts

4. Proton Drive 🔒 (Coming Soon)

Waiting for official Proton Drive API
User login ready when API becomes available

5. FTP 🌐 (Fully Working)

Connect to any FTP server
Supports:

NAS devices (Synology, QNAP, etc.)
Web hosting FTP
PS4/PS5 (GoldHEN FTP)
Any standard FTP server




The Cloud Services:
For pCloud:

Open the app
Click Settings
Select "pCloud"
Enter their pCloud email and password
Click "Login to pCloud"
Done! They can now upload files

For Google Drive:

Open the app
Click Settings
Select "Google Drive"
Enter their Gmail and password (or App Password)
Click "Login to Google Drive"
Upload files to their own Drive

For OneDrive:

Open the app
Click Settings
Select "OneDrive"
Enter their Microsoft email and password
Click "Login to OneDrive"
Upload to their OneDrive

For FTP:

Click the "FTP" tab
Enter FTP server details (IP, port, username, password)
Select file to upload
Click "Upload via FTP"
