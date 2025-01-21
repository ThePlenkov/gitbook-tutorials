---
icon: bucket
---

# Step 4: Create S3 Bucket

Set up storage for your replicated data.

## Create Bucket

1. Open S3 Console
2. Create new bucket: `hana-replication-data`
3. Enable versioning
4. Configure lifecycle rules (optional)

## Folder Structure


hana-replication-data/
├── raw/
│   ├── flights/
│   ├── bookings/
│   └── passengers/
└── processed/
