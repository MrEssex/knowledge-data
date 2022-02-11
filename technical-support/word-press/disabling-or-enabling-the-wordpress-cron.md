---
type: article
title: Disabling or enabling the WordPress cron
slug: disabling-or-enabling-the-wordpress-cron
date_published: 1970-01-01T00:00:00.000Z
date_updated: 2022-01-05T18:29:56.000Z
---

# Disabling or enabling the WordPress cron

To disable the internal WordPress cron job system, open the wp-config.php file in the root of your WordPress installation and locate the following line:

define('DB_COLLATE', '');  -  Right under it, add the following code: define('DISABLE_WP_CRON', true);

If you want to enable the WordPress cron, you will need to change it to:

define('DISABLE_WP_CRON', false);

Note: You can modify the wp-config.php file via FTP, SSH or File Manager in cPanel.