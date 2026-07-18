# Risk Acceptance and Limitations

Certain findings remained unresolved due to project scope and AWS Free Tier additional cost considerations.

### Finding : Hardware MFA 

Prowler recommended the use of hardware MFA devices for IAM accounts.

Current implementation includes Virtual MFA, which provides strong authentication protection. Hardware MFA was not implemented due to additional hardware costs.

---

### Finding : AWS KMS Encryption Findings

Prowler recommended AWS KMS-based encryption.

Current implementation uses SSE-S3 encryption, which provides encryption at rest. Migration to AWS KMS was not performed due to potential additional AWS charges.

---

### Additional Findings

Remaining findings primarily relate to:
-	Hardware MFA requirements
-	AWS Organizations controls
-	SNS notifications
-	SQS integrations
-	CloudWatch Monitoring.
-	Bedrock and sagemaker AI services.
-	KMS encryption recommendations


### These Controls typically require,

- Additional AWS services
- Multi-Account Architecture
- Paid AWS features
- Enterprises level governance feature
