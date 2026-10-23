---
title: "Data Consistency Model in Alluxio"
url: "https://www.alluxio.io/blog/data-consistency-model-in-alluxio"
date: "2025-05-13"
feed_url: "https://www.alluxio.io/blog/rss.xml"
---
Unlike HDFS which provides one-copy update semantics or AWS S3 which provides eventual consistency, data consistency in Alluxio is a bit more complicated and depends on the configuration. In short, when clients are only reading and writing through Alluxio, the Alluxio file system provides strong consistency. However, when clients are writing data across both Alluxio and under storage, the consistency may depend on the write type and under storage type.
