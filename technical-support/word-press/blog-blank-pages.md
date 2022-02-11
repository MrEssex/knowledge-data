---
type: article
title: Blog blank pages
slug: blog-blank-pages
date_published: 1970-01-01T00:00:00.000Z
date_updated: 2022-01-05T18:22:31.000Z
---

# Blog blank pages

If you are experiencing issues or WordPress is not responding, this could be the result of a corrupted theme.

If you have a Database Issue, Plugin Issues or Theme Issue, the below articles should assist in resolving these problems

Database Issue - If you are using WordPress 3.1.x, incorrect information in your wp-config.php file can cause a white page to appear. If the MySQL username or MySQL password in this file are incorrect, a white page will appear. In previous versions of WordPress this would appear as an "Error establishing a database connection" message, but that is no longer the case with version 3.1.x.

Plugin Issue - You can easily determine if it is a plugin causing the issue by disabling the plugins temporarily. When a plugin is tthe issue, it is unlikely you will be able to obtain access to the WordPress Admin Dashboard to disable the plugin. The Dashboard can be accessed by going to your WordPress blog and adding /wp-admin/ onto the end of the URL.

Theme Issue - If it is not a plugin issue, it may be a theme related issue. If you have access to the WordPress Admin Dashboard, it is recommended that you simply log in and change your default theme. Some issues can cause you to lose access to the WordPress Admin Dashboard; so, in order to change the theme in this case, you should access the database directly using phpMyAdmin.