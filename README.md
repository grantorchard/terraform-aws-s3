# CRAMPS Rating (higher is better)
27/60 - Development use only.

Cost: 9/10
Lack of production concerns in other areas of CRAMPS make this a cost effective deployment.

Resilience: 0/10
Replication is disabled.
Backups are disabled.

Availability: 8/10
s3 buckets are distributed across availability zones by default.

Management: 0/10
Logging is disabled.
Metrics are disabled.

Performance: 6/10
Objects placed in this bucket will sit on standard storage for 30 days then be de-staged to Glacier.
Versioned objects will be de-staged to Glacier once two newer versions of the object have been created.

Security: 4/10
Public access is disabled.
Encryption is disabled.