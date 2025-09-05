# 🚀 Secure Cloud Infrastructure Audit

## 📌 Objective
Ensure cloud-based platforms follow industry-standard security measures by auditing, securing, and monitoring **AWS resources**.

---

## 🔹 Key Tasks Performed

### ✅ 1. Audit Cloud Accounts (IAM)
- Reviewed IAM users, groups, and roles.  
- Verified permissions using **IAM Policy Simulator**.  
- Captured audit evidence of **least privilege enforcement**.  
📷 *Screenshot:* `screenshots/iam_audit.png`

---

### ✅ 2. Set Up Multi-Region Backups (S3)
- Created **S3 buckets** in multiple regions for redundancy.  
- Enabled **bucket encryption (AES-256/KMS)**.  
- Enabled **bucket versioning** for recovery.  
📷 *Screenshot:* `screenshots/s3_backup.png`

---

### ✅ 3. Enable Web Application Firewall (WAF)
- Configured **AWS WAF** to filter malicious traffic.  
- Created rules to block common threats (SQLi, XSS, bad IPs).  
- Monitored incoming requests for suspicious activity.  
📷 *Screenshot:* `screenshots/waf_rules.png`

---

### ✅ 4. Security Group Audit (EC2)
- Reviewed inbound/outbound rules for:  
  - **Web Server SG** → HTTP/HTTPS restricted to internal IPs.  
  - **Bastion Host SG** → SSH/RDP allowed only from management network.  
  - **SQL Server SG** → Database access restricted to web server only.  
📷 *Screenshot:* `screenshots/security_groups.png`

---

### ✅ 5. VPC and Network ACL Audit
- Verified **VPC configuration** and subnets.  
- Reviewed **Network ACL inbound/outbound rules**.  
- Ensured segmentation & isolation of resources.  
📷 *Screenshot:* `screenshots/vpc_audit.png`

---

### ✅ 6. CloudWatch Monitoring
- Reviewed **EC2 performance metrics** (CPU, I/O).  
- Checked **EBS volume monitoring**.  
- Confirmed **CloudWatch alarms** for system health.  
📷 *Screenshot:* `screenshots/cloudwatch_metrics.png`

---

### ✅ 7. CloudTrail Logs Audit
- Verified **CloudTrail trails** storing logs in S3.  
- Reviewed **event history** in JSON format.  
- Ensured **traceability** of all account activities.  
📷 *Screenshot:* `screenshots/cloudtrail_logs.png`

---

## 🔹 Data Sources
- **AWS CloudTrail logs**  
- **AWS CloudWatch metrics**  
- **VPC & Security Group configurations**  
- **S3 bucket settings**  
- Public datasets from **AWS Open Data**  

---

## 🔹 Conclusion
This project demonstrates how to:
- ✅ Audit cloud accounts for compliance.  
- ✅ Secure storage with **multi-region backups & encryption**.  
- ✅ Protect workloads using **Web Application Firewall (WAF)**.  
- ✅ Monitor activity via **CloudWatch & CloudTrail**.  
- ✅ Enforce **least privilege & network segmentation**.  

📌 **Result:** A secure and resilient **cloud infrastructure** aligned with best practices.  
