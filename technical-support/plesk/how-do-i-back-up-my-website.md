---
type: article
title: How do I back up my website?
slug: how-do-i-back-up-my-website
date_published: 1970-01-01T00:00:00.000Z
date_updated: 2022-01-05T18:15:47.000Z
---

# How do I back up my website?

One of the most important things in hosting is to make sure you regularly backup your website. If you make a change or update to your website and it causes an error, using a backup will make sure you can have your website back online working again almost immediately.

From the first setup, Plesk has been configured to automatically create a daily backup and store them for up to 4 weeks.

Every 7 days a complete backup is taken, and every day an incremental backup is saved.

You can access the Backup Manager by navigating to ‘Websites & Domains’ and then selecting ‘Backup Manager’.

## Restoring, using a backup

To restore to a backup, select the backup and click it to open the backup
![](https://lh4.googleusercontent.com/9C5Tn7RuZyv02Gb25B4Aqm13w0DAI_FNBAv61sjh2IMTHzYuBpbwk9_n61wXvxDAEr1o9pcjfUT8uX56q79B9E-CZRBH5VopCL6FycD0LYSRBatK145kmsOOz4NzkOpGViFXSDku)
Once on the backup page, it will provide you the information at the top and let you select what backup content you wish to restore. You can either do this for particular parts or for the entire system.

Select the particular parts of the service you wish to restore under each ‘Type of object to restore’ in the drop down. Selections are remembered. This is useful if you only want to backup one website and its respective databases if you have several.
![](https://lh5.googleusercontent.com/5VSJfK5cGCJJaD-43IZOcxxHVEcMXyTKakZi6K8HPlqONpRrRSBxJRibWr3PvWzoHsc2VelaSAKuDAyV0aWodZsjulUG11r_erqbSzXI7dhi7Y4e6BR93qoTvBv1lfK0dO7hrNLL)
To then restore, hit the restore button at the bottom.

Alternatively, you can select ‘All objects (entire system)’ to restore the whole system, or the whole parts of a system (i.e. just databases), if you wanted to keep all your websites intact but wanted to roll back all databases.