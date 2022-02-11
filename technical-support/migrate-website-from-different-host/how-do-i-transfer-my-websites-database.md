---
type: article
title: How do I transfer my website's database
slug: how-do-i-transfer-my-websites-database
date_published: 1970-01-01T00:00:00.000Z
date_updated: 2022-01-05T17:57:38.000Z
---

# How do I transfer my website's database

Websites use databases to store data such as product listings and comments. To fully migrate from your previous host, you will need to export your database from your old provider and upload it to HostGrid servers.

Within this article you will learn:

- [How to export my websites database from my old host](https://support.hostgrid.com/en/kb/article/247/how-do-i-transfer-my-website-s-database#How%20to%20export%20my%20websites%20database%C2%A0)
- [How to import my website's database to HostGrid](https://support.hostgrid.com/en/kb/article/247/how-do-i-transfer-my-website-s-database#How%20to%20import%20my%20website's%20database%20to)

---

### [How to export my websites database](How to export my websites database)

To export your database, you will need to access the ****phpMyAdmin ****account from your old hosting provider.

Once you have access follow these instructions to export your database:

- Access**** phpMyAdmin**** from your ****Old Hosting Account****
- Click the ****Database ****you wish to export from**** The Sidebar****
- Click ****Export****
- Make sure the format is set to**** SQL****
- Click**** Go****

![](https://storage.googleapis.com/cdn.hostgrid.com/knowledge/Transfer%20my%20database%201.png)
Your database will be saved on your computer. Move this file to a safe location as you will need it to import your database to HostGrid
![](https://storage.googleapis.com/support-image/Warning-12345.png)
****Note - ****If your previous hosting solution does not use phpMyAdmin please contact them and ask ****"How do I export my websites database in SQL format"****

---

### [How to import my website's database to HostGrid](How to import my website's database to HostGrid)

- Go to ****My Sites****
- Click ****Login to Plesk ****on the site you want to ****Import Your Database****

![](https://storage.googleapis.com/cdn.hostgrid.com/knowledge/Transfer%20my%20database%202.png)
- Click ****Databases****
- Click ****Add Database****

![](https://storage.googleapis.com/cdn.hostgrid.com/knowledge/Transfer%20my%20database%203.png)
- Create your ****Database Name****
- Create your ****Database User Name****
- Create database ****Password****
- Confirm your database**** Password****
- Click**** OK****

![](https://storage.googleapis.com/cdn.hostgrid.com/knowledge/Transfer%20my%20database%204.png)
- Locate the ****Database ****that you have ****Just Created****
- Click ****phpMyAdmin****

![](https://storage.googleapis.com/cdn.hostgrid.com/knowledge/Transfer%20my%20database%205.png)
- Click ****Import****
- Click ****Choose File****
- Upload ****The File ****that you ****Exported From Your Previous Host****
- Click ****Go****

![](https://storage.googleapis.com/cdn.hostgrid.com/knowledge/Transfer%20my%20database%206.png)
Your website's database will now be successfully uploaded. The next step to fully migrate your website to HostGrid's server is to [****Point Your Domain To HostGrid's Name Servers****](https://support.hostgrid.com/en/kb/article/11/how-do-i-point-my-website-to-hostgrid.com)