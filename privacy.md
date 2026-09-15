---
layout: default
title: Privacy policy
permalink: /privacy/
---
# Privacy policy

*claude-status — last updated 15 September 2026*

claude-status is a single-user personal tool. Its author is its only user. There is no sign-up, no account, no server and no service.

**What it does.** It uploads a small status file from the author's own computer to the author's own Google Drive, using the open-source program [rclone](https://rclone.org/), and reads that file back to confirm the upload worked.

**What it asks Google for.** One OAuth scope, `drive.file`. Under that scope the tool can see and change only files it created itself. It cannot see, read, change or delete anything else in the Google Drive account.

**What it stores.** No data about anyone. The only thing it keeps is the OAuth token that Google issues to the author, held on the author's own computer and used solely to upload the status file.

**Who it talks to.** Exactly one service: the Google Drive API, over Google's own OAuth. There are no third parties, there is no analytics, and nothing is shared with anyone.

**Revoking access.** Open [myaccount.google.com/permissions](https://myaccount.google.com/permissions), find claude-status, and remove it. That invalidates the token immediately.

**This website.** These pages are static files served by GitHub Pages. They set no cookies and run no scripts.

Contact: the author, via the [GitHub repository](https://github.com/Audiotox/claude-status).
