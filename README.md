# AWS-IAM-Overview-for-Secure-Environment-Segmentation
🔐 AWS IAM: Structuring Access for Dev and Prod Environments

This project demonstrates how to organize and manage user access in AWS using **IAM Users**, **User Groups**, and **Account Aliases**. It focuses on applying **environment-based access control** to securely separate development and production environments.

Ideal for anyone looking to understand or showcase secure AWS practices in real-world scenarios.

---

## 📁 What This Covers

### ✅ IAM Users
Individual identities in AWS with specific credentials and permissions.  
Used to securely access AWS resources either programmatically or through the AWS Management Console.

### ✅ IAM User Groups
Logical groups that allow you to assign common permissions to multiple users.  
Great for applying consistent policies across teams like developers, testers, or admins.

### ✅ 🔄 Dev vs Prod Segmentation
A best practice to reduce risk in cloud environments.

Example setup:
- **DevGroup** → Full access to development resources (e.g., EC2, S3 buckets for dev).
- **ProdGroup** → Limited or read-only access to production resources.

<img width="1606" height="1258" alt="image" src="https://github.com/user-attachments/assets/7cd6df79-f2cc-4d8a-9d85-e7b6f3c480b9" />

This ensures:
- Developers can innovate safely.
- Production remains stable and secure.

### ✅ Account Alias
Simplifies the AWS login URL by replacing the default 12-digit account ID with a recognizable alias (e.g., `https://yourteam.signin.aws.amazon.com/console`).  
Useful for branding and user-friendly access.

---

## 🚀 Why It Matters

In any AWS environment, **security and structure** are key. This setup:
- Enhances security through access control.
- Makes permission management scalable.
- Reduces human error in critical environments like Development and Production.

Perfect for:
- Teams adopting AWS best practices.
- Developers showcasing real-world AWS knowledge.
- Anyone preparing for AWS certifications (e.g., Solutions Architect, SysOps).

---

## 🛠️ Tools & Concepts Used

- AWS IAM (Identity and Access Management)
- Policy-based permission management
- Least privilege principle of Security in AWS
- Environment segmentation strategy

---

## 📚 Resources

- [AWS IAM Official Docs](https://docs.aws.amazon.com/iam/)
- [AWS Best Practices for IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)

---
