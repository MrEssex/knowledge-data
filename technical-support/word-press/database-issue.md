---
type: article
title: Database issue
slug: database-issue
date_published: 1970-01-01T00:00:00.000Z
date_updated: 2022-01-05T18:22:47.000Z
---

# Database issue

If you are using WordPress 3.1.x, incorrect information in your wp-config.php file can cause a white page to appear. If the MySQL username or MySQL password in this file are incorrect, a white page will appear. In previous versions of WordPress this would appear as an "Error establishing a database connection" message, but that is no longer the case with version 3.1.x.

To fix this issue you must create a new MySQL user and update the wp-config.php file to have the new MySQL username and MySQL Password. Simply locate the following information in that file, and update the bold sections with your new information:

/** MySQL database username */

define('DB_USER', 'user_wp1');

/** MySQL database password */

define('DB_PASSWORD', 'password');