---
title: "Creating Grafana Dashboards to Visualize Alluxio Metrics"
url: "https://www.alluxio.io/blog/creating-grafana-dashboards-to-visualize-alluxio-metric"
date: "2025-05-13"
feed_url: "https://www.alluxio.io/blog/rss.xml"
---
Monitoring metrics is highly important to operate distributed systems in production. Alluxio collects metrics using the Codahale Metrics Library on I/O throughput, RPC throughput, and resource usage. Alluxio metrics are shown in its webUI, but are also available through a REST endpoint or exportable to several third-party sinks in a time-series manner (see docs).
