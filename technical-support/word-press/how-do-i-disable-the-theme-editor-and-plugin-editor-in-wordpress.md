---
type: article
title: How do I disable the theme editor and plugin editor in WordPress?
slug: how-do-i-disable-the-theme-editor-and-plugin-editor-in-wordpress
date_published: 1970-01-01T00:00:00.000Z
date_updated: 2022-01-05T18:28:59.000Z
---

# How do I disable the theme editor and plugin editor in WordPress?

WordPress allows you to edit your plugin and theme files directly through its admin panel. Although handy, this is dangerous because a single typo can render your website blank. Moreover, you may want to give admin access to people that don't need to edit code.

All you need to do is to disable the Theme Editor and the Plugin Editor. To do that, open your wp-config.php file and add the following code to it:

define( 'DISALLOW_FILE_EDIT', true );

define( ‘DISALLOW_FILE_MODS’, true );

That's all you need to do in order to disable those editors from the WordPress backend.