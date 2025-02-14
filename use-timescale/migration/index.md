---
title: Migrate your data to Timescale
excerpt: Migrate existing database to Timescale Cloud
products: [cloud]
keywords: [data migration, postgresql, hypershift, RDS]
tags: [ingest, migrate, RDS]
---

# Migrate your data to Timescale Cloud

You can migrate data from another database into Timescale Cloud
using Timescale Hypershift. You can also use hypershift to migrate your data
from Managed Service for TimescaleDB, from a self-hosted Timescale instance, or
from another PostgreSQL database, including Amazon RDS.

*   [Understand how hypershift works][about-hypershift] before you begin using it.
*   [Migrate your data with hypershift][migrate-hypershift].
*   [Configure hypershift][configure-hypershift].

If you want to import data from another format, such as a `.csv` file, into a
new Timescale Cloud service, see the [data ingest section][data-ingest].

If you want to migrate existing data into a self-hosted Timescale installation,
see the [self-hosted data migration section][self-hosted-migration].

If you want to migrate existing data into Managed Service for TimescaleDB, see
the [Managed Service for TimescaleDB migration section][mst-migration].

[data-ingest]: /use-timescale/:currentVersion:/ingest-data/
[self-hosted-migration]: /self-hosted/:currentVersion:/migration/
[mst-migration]: /mst/:currentVersion:/migrate-to-mst/
[about-hypershift]: /use-timescale/:currentVersion:/migration/about-hypershift/
[migrate-hypershift]: /use-timescale/:currentVersion:/migration/migrate-hypershift/
[configure-hypershift]: /use-timescale/:currentVersion:/migration/hypershift-config/
