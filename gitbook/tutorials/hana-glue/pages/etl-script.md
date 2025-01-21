---
icon: code
---

# Create ETL Script

Implement the AWS Glue ETL job that will connect to SAP HANA and export tables to S3 in Parquet format.

## Implementation

Check out the complete script in this Gist:

{% embed url="https://gist.github.com/ThePlenkov/ec4310d5781ebc753fb81dc7816b6ec7" %}

## Next Steps

After implementing the script:
1. Create a new Glue Job
2. Configure the job to use the provided script
3. Set up job parameters for table names and S3 paths
4. Run the job to start the replication process
