---
type: article
title: Troubleshooting WordPress blank page issues
slug: troubleshooting-wordpress-blank-page-issues
date_published: 1970-01-01T00:00:00.000Z
date_updated: 2022-01-05T18:30:36.000Z
---

# Troubleshooting WordPress blank page issues

The majority of the time the "white screen of death" can occur if certain plugins are not functioning properly. This could also be caused by a poorly coded theme that your website is using. Below are a few steps that will help you to troubleshoot this problem.

Change PHP Version

In case you've performed any recent theme or plugin updates, you should change the PHP version of your website in order to check if this will have any effect on your pages. This can be done easily via cPanel -> PHP Version Manager.

Modify PHP variables

Depending on your WordPress set up your website might require higher PHP server resources. You can increase the value of memory_limit and enable output_buffering at your host in order to verify if this was causing the issue.

You can do that from your cPanel, under PHP Variables Manager.

Disable all plugins

You can deactivate your website plugins via FTP. Navigate to the WordPress plugins folder on your hosting account:

/path_to_your_application/wp-content/plugins

and rename it (e.g. to plugins.back) so you can deactivate your plugins temporary. After that, you can test your website.

If the website starts working correctly this means that one or more of your plugins are causing the issue. In order to fix it rename the plugins folder from plugins.back/ to plugins/ and open the folder itself. Once you are within this directory you should move one by one the subfolders of each plugin out of the plugins/ folder - then test your application. If the issue is resolved this means that the plugin that you have moved out has been causing all the troubles.

After the problematic plugin is found check whether it is compatible with your version of WordPress. If you plan to use it contact the plugin's developers and report the issue.