---
title: "Agent state and ticket retrieval failures"
url: "https://status.assembled.com/incidents/czc1yyzr7dl3"
date: "2026-04-24"
feed_url: "https://status.assembled.com/history.atom"
---
Apr 24 , 18:21 UTC Resolved - Between 10:56 AM and 11:09 AM PT, a subset of sync jobs responsible for retrieving agent states and ticket updates experienced intermittent failures. The underlying issue has been identified and resolved, and we have verified that all affected ticket updates are now backfilling any data. We've also added a system-level agent state exclusion to ensure that these failures do not affect adherence and are conducting a postmortem to identify any system improvements that can be made.
