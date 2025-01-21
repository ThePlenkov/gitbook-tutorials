---
icon: aws
---

# Step 2: Prepare AWS Glue

Set up the necessary AWS components for the ETL process.

## Create Service Role

1. Go to IAM Console
2. Create new Role for AWS Glue
3. Add these policies:
   - AWSGlueServiceRole
   - AmazonS3FullAccess
   - SecretsManagerReadWrite

{% hint style="warning" %}
For production environments, follow the principle of least privilege and restrict access accordingly.
{% endhint %}
