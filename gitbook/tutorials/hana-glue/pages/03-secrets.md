---
icon: lock
---

# Step 3: Configure Secrets Manager

Store SAP HANA credentials securely in AWS Secrets Manager.

## Create Secret

1. Open AWS Secrets Manager
2. Click "Store new secret"
3. Choose "Other type of secret"
4. Paste your complete HANA service key JSON
5. Name it `sap-hana-credentials`

## Access Pattern


import boto3
import json

def get_hana_credentials():
    secret_name = "sap-hana-credentials"
    session = boto3.session.Session()
    client = session.client('secretsmanager')
    secret = client.get_secret_value(SecretId=secret_name)
    return json.loads(secret['SecretString'])
