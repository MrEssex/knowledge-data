---
type: article
title: Disabling all WordPress plugins directly in the database
slug: disabling-all-wordpress-plugins-directly-in-the-database
date_published: 1970-01-01T00:00:00.000Z
date_updated: 2022-01-05T18:31:43.000Z
---

# Disabling all WordPress plugins directly in the database

It is easy to disable all WordPress plugins directly from your database. This is useful when you have problems with your WordPress installation, such as not being able to log in to the admin Dashboard, or having blank pages on the website.

If you don't know which is the database used by your WordPress website, you can check the DB_NAME variable in the WordPress configuration file - wp-config.php. This file is usually located in the document root directory of your application and can be opened via the File Manager in your cPanel.

To disable all plugins, you will need to go to phpMyAdmin in your cPanel and select your WordPress database from the menu on the left.

Browse the table wp_options and find the option active_plugins. Click the pencil icon to edit the table. Its content will vary, depending on what plugins you have enabled. For example, if you have the Akismet and Hello Dolly plugins enabled, the code there will be:

a:2:{i:0;s:19:"akismet/akismet.php";i:1;s:9:"hello.php";}  -  To disable all plugins, simply delete the code and click the Go button to save the change.

Please note that this table may have a different prefix instead of wp_. You will see the correct prefix of the database once you access the phpMyAdmin tool and select the WordPress database.

Disabling the plugins in this way will not delete them from your WordPress application. They will simply be deactivated. You can easily activate them from your WordPress admin area at any time.