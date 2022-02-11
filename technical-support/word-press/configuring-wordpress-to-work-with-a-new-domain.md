---
type: article
title: Configuring WordPress to work with a new domain
slug: configuring-wordpress-to-work-with-a-new-domain
date_published: 1970-01-01T00:00:00.000Z
date_updated: 2022-01-05T18:30:51.000Z
---

# Configuring WordPress to work with a new domain

There are few ways to change the domain name on your WordPress application:

Using phpMyAdmin

You should change the site url and home options in your WordPress database. You can do this using the phpMyAdmin tool available in your cPanel.

Once in phpMyAdmin, select your WordPress database and browse the table wp_options. Find the options site url and home and change their values to the new domain you want to use.

Make sure that you clear the cache of your browser and verify if your website is functional.

From the WordPress admin Dashboard

Access your WordPress Dashboard (e.g. http://yourdomain.com/wp-admin) -> Settings -> General.

Under the WordPress address (URL) and the Site address (URL) fields enter the domain that you wish your application to work with and save the changes.

The same modification is valid if you want to add "www" to your domain.

Using WP-CLI over SSH

SiteGround customers can benefit from WP-CLI (WordPress Command line interface) which is installed on their hosting accounts by default.

You need to connect to your hosting server via SSH, navigate to your WordPress installation folder and execute the following commands:

> wp db export

This command will create a backup of your database into an SQL file. After that execute:

> wp search-replace 'http://olddomain.com' 'http://newdomain.com'

The search-replace command replaces all occurrences of http://olddomain.com with http://newdomain.com in the database of your application. Note that http://olddomain.com is the current domain configured on your WordPress and http://newdomain.com is the new domain that you wish to use.

> wp cache flush

This is the last command that you should execute, so you can flush the object cache of your WordPress.