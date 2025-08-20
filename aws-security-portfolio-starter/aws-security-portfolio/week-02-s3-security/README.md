# Week 02 – S3 Security (Encryption & Policies)

## 🎯 Objectives
- Create a private S3 bucket with default encryption.
- Enforce HTTPS-only access via bucket policy.
- Test presigned URLs and public vs private access safely.

## 🛠 Steps Taken
1. Created bucket `my-secure-bucket-<unique>` with default SSE-S3.
2. Left "Block all public access" ON.
3. Applied bucket policy to deny non-HTTPS requests.
4. Generated a presigned URL to test controlled access.

## 📸 Evidence
- Redacted screenshots in `./screenshots/`.
- Bucket policy used: [bucket-policy.json](bucket-policy.json).

## 🔑 Key Learnings
- Public Access Block is separate from bucket policies.
- Default encryption protects data at rest.
- Presigned URLs provide temporary, least-privilege access to objects.