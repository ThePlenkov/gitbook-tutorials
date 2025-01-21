---
icon: spider
---

# Step 5: Configure Glue Crawler

Set up automated table discovery in AWS Glue.

## Create Crawler

1. Open AWS Glue Console
2. Create new Crawler
3. Configure source: `s3://hana-replication-data/raw/`
4. Create new database: `hana_replica`
5. Set schedule (optional)

## Run Crawler

After data is loaded:
1. Run crawler manually or wait for schedule
2. Verify tables in Glue Catalog
3. Query data using Athena

{% hint style="info" %}
Crawlers automatically detect schema changes in your S3 data.
{% endhint %}
