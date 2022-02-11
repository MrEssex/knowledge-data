---
type: article
title: Using a post via email feature in WordPress
slug: using-a-post-via-email-feature-in-wordpress
date_published: 1970-01-01T00:00:00.000Z
date_updated: 2022-01-05T18:28:42.000Z
---

# Using a post via email feature in WordPress

To set up a Post via e-mail functionality for your WordPress installation, you will need to have a valid email account which you can use for it.

Next, you will need to add this account in your WordPress installation. To do this, log in to the WordPress administrative area and go to the Settings area then to Writing and under the Post, via Email section, you will need to enter the below details:

- Mail Server: your domain name (in case your email account is with SiteGround you can use the hostname of the server as Mail server, i.e. siteground123.com)

- Port: 110 (the service requires POP3 access for the email account)

- Login Name: the full email address

- Password: the corresponding password for the mail account above

For example:

- Mail Server: yourdomain.com
- Port: 110
- Login Name: [hidden_wordpress_email@yourdomain.com](mailto:hidden_wordpress_email@yourdomain.com)
- Password: your-password-for-your-email

These are usually all the settings you need to adjust in order for the Post via e-mail functionality to work.

What you need to do after that is to visit the corresponding URL for your WordPress installation so the posts/articles sent to the above email address are parsed. The URL is of type:

http://yourdomain.com/wordpress/wp-mail.php

Where:

yourdomain.com – is your actual domain name

WordPress – is the path to your WordPress installation. This might be skipped if WordPress is installed directly under the public_html document root folder for your domain.

Or if we presume you are using the domain name mentioned in the previous example and the WordPress installation is under directory blog:

http://mywebsite.com/blog/wp-mail.php

Note that by default such posts are not automatically displayed on your WordPress front page. They still need to be published via the WordPress administrative area. Alternatively, you can adjust your WordPress configuration to automatically submit posts without being approved by an administrator. This is up to you and your WordPress configuration.