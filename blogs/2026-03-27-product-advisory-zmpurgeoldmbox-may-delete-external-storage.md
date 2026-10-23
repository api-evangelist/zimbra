---
title: "Product Advisory: zmpurgeoldmbox May Delete External Storage Blobs After Mailbox Migration"
url: "https://blog.zimbra.com/2026/03/product-advisory-zmpurgeoldmbox-may-delete-external-storage-blobs-after-mailbox-migration/"
date: "2026-03-27"
author: "marilyn lee"
feed_url: "https://blog.zimbra.com/feed/"
---
Applies to: Zimbra Collaboration Suite 10.1.15, 10.1.16 with external object storage (Scality, S3, OpenIO) Summary A regression in ZCS 10.1.15 causes zmpurgeoldmbox to delete external blobs (Scality, S3, OpenIO) after mailbox migration, even when zimbraMailboxMoveSkipBlobs=TRUE. This results in permanent, irrecoverable email data loss on the destination server. A fix is targeted for the 10.1.17 patch release.
