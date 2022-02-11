---
type: article
title: Enabling the manual statistics update within Awstats
slug: enabling-the-manual-statistics-update-within-awstats
date_published: 1970-01-01T00:00:00.000Z
date_updated: 2022-01-05T18:17:49.000Z
---

# Enabling the manual statistics update within Awstats

To enable the manual statistics update in Awstats, you will need to edit the following file:

tmp/awstats/awstats.yourdomain.com.conf (substitute yourdomain.com with your domain)

You will update the following line:

> AllowToUpdateStatsFromBrowser=0

update this to:

> AllowToUpdateStatsFromBrowser=1