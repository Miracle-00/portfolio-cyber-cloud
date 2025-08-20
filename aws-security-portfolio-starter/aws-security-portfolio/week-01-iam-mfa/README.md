# Week 01 – IAM & MFA Setup

## 🎯 Objectives
- Create an IAM admin user (stop using root).
- Enable MFA on root and admin users.
- Enforce a strong password policy.
- Practice least-privilege with a read-only S3 policy.

## 🛠 Steps Taken
1. Logged in as root → created IAM user `AdminUser` and group `AdminGroup` with `AdministratorAccess`.
2. Enabled MFA on root and on `AdminUser` using an authenticator app.
3. Set account password policy (length ≥12, symbols, rotation).
4. Wrote an S3 read-only policy and attached it to a test user `analyst-readonly`.

## 📸 Evidence
- Redacted screenshots in `./screenshots/`.
- IAM policy used: [policy.json](policy.json).

## 🔑 Key Learnings
- Root account should not be used daily; keep MFA enabled.
- Groups + managed policies simplify permission management.
- Least privilege limits blast radius if credentials are compromised.