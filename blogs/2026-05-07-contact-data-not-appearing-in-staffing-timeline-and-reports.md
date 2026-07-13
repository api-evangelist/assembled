---
title: "Contact data not appearing in staffing timeline and reports"
url: "https://status.assembled.com/incidents/2ptv3qqx2xls"
date: "2026-05-07"
feed_url: "https://status.assembled.com/history.atom"
---
May 7 , 11:15 UTC Resolved - Between 6:30pm ET on May 6th and 7am ET on May 7th, some customers saw missing or zero values in reporting surfaces (including support volume and queue/exclusion views) for data values that appeared after 6:30pm ET on 5/6/2026 due to delayed replication in one of our data-processing tasks. Data ingestion itself continued normally and no conversation data was lost, the issue was isolated to metric freshness/display. We restored the task, backfilled dependent metrics, and service is now operating normally, with additional monitoring improvements underway to prevent r
