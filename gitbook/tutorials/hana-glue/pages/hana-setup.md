---
icon: key
---

# Step 1: Prepare HANA Credentials

Learn how to deploy the CAP Flights model and obtain necessary credentials.

## Deploy CAP Flights Model

Follow the official CAP tutorial to deploy the Flights model to SAP BTP:
[CAP Flights Tutorial](https://cap.cloud.sap/docs/get-started/in-a-nutshell)

## Export Service Key

1. Navigate to your BTP Cockpit
2. Locate your HDI Container
3. Create a service key
4. Download the JSON credentials

{% hint style="tip" %}
Save the service key JSON - you'll need it for AWS Secrets Manager later.
{% endhint %}
