---
type: article
title: How do I transfer my files with FTP
slug: how-do-i-transfer-my-files-with-ftp
date_published: 1970-01-01T00:00:00.000Z
date_updated: 2022-01-05T17:56:55.000Z
---

# How do I transfer my files with FTP

There are 4 steps needed to transfer your website using FTP (File Transfer Protocol)

- [Find your FTP login from your old hosting solution](https://support.hostgrid.com/en/kb/article/245/how-do-i-transfer-my-files-with-ftp#Find%20your%20FTP%20Login%20From%20Your%20Old%20Hosting%20Solution%C2%A0)
- [Download your files using FTP](https://support.hostgrid.com/en/kb/article/245/how-do-i-transfer-my-files-with-ftp#Download%20your%20files%20using%20FTP%C2%A0)
- [Create your FTP login with HostGrid](https://support.hostgrid.com/en/kb/article/245/how-do-i-transfer-my-files-with-ftp#Create%20your%20FTP%20login%20detail%20with%C2%A0HostGrid)
- [Upload your files via FTP to HostGrid servers](https://support.hostgrid.com/en/kb/article/245/how-do-i-transfer-my-files-with-ftp#Upload%20your%20files%20via%20FTP%20to%20HostGrid%C2%A0servers%C2%A0)

### ****[Find your FTP login from your old hosting solution](Find your FTP login from your old hosting solution)****

For you to be able to access the files of your website, you will need the following information from your last provider:

- ****Host Name****
- ****FTP User Name****
- ****FTP Password****

If you do not know where to find this information, please contact your old provider.

---

### ****[Download your files using FTP](Download your files using FTP)****

Once you have your FTP login details from your old host, you will need to log in to your FTP via an FTP client. We recommend ****FileZilla.****

- Open ****FileZilla****
- Enter the ****Host Name, Username, & Password ****from your old hosting solution
- Click ****Quick Connect****

![](https://storage.googleapis.com/support-image/Warning-12345.png)
****Note:**** If your previous host provides a port, use this number, otherwise leave it blank.
![](https://storage.googleapis.com/cdn.hostgrid.com/knowledge/Filezilla%20Download%20files%20Image%201.png)
- Select the ****Folder ****destination that you want the files to be downloaded to on the left-hand pane (The left-hand Pane represents your PC)
- Right Click and ****Download ****the ****Highest-Level Folder**** on the right-hand pane (The right-hand pane represents the server your files are hosted on)

![](https://storage.googleapis.com/cdn.hostgrid.com/knowledge/Filezilla%20download%20files%20image%202.png)
Your websites files will now be saved on your PC.

---

### ****[Create your FTP login detail with HostGrid](Create your FTP login detail with HostGrid)****

Before you can upload your files to you to HostGrids servers you will need to create an ****FTP Login ********[More Info](https://support.hostgrid.com/en/kb/article/159/how-to-set-up-and-access-my-main-ftp-account)****

---

### ****[Use FTP to upload files to the HostGrid's servers](Use FTP to upload files to the HostGrid's servers)****

Once you have created an FTP Login you will be able to upload your website's files to HostGrids servers. To do so, follow these instructions:

- Open ****FileZilla****
- Enter the ****Host Name, Username, Password ****that you created when setting up an ****FTP Login**** with ****HostGrid****
- Click ****Quick Connect****

![](https://storage.googleapis.com/cdn.hostgrid.com/knowledge/Filezilla%20Download%20files%20Image%201.png)
- Select the folder ****httpdocs ****within the right-hand pane
- Find the ****Folder ****on ****Your Computer ****where your ****Websites Files Are Stored****
- Find the ****Root Folder ****(Typically called httpdocs or public httpdocs)
- Right-click and select ****Upload****
- Overwrite all ****Duplicated Documents****

![](https://storage.googleapis.com/cdn.hostgrid.com/knowledge/FileZilla%20Upload%20Files%20Image%203.png)![](https://storage.googleapis.com/support-image/Tick-123456.png)
********Tip ****- The correct root folder to upload will at least include a file named ****index.php, index.html, home.html********

You have now successfully uploaded your website's files via FTP to the HostGrid's servers. The next step to fully migrating your website to HostGrid is to [****Transfer Your Websites DataBase****](https://support.hostgrid.com/en/kb/article/247/how-do-i-transfer-my-website-s-database)