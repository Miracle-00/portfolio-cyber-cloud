
## Objectives
- Enable MFA on root account
- Create IAM admin user
- Implement least-privilege IAM policies

## Steps Taken
1. Enabled MFA for root user
2. Created IAM admin user `MiracleAdmin`
3. Configured IAM password policy
4. Wrote S3 read-only policy

## Key Learnings
- MFA protects root account
- Least privilege is essential
- IAM groups simplify user management

## Evidence
- Admin policy.json
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Action": "*",
            "Resource": "*"
        }
    ]
}
- Redacted screenshots in `/screenshots/`
