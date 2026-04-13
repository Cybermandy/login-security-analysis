# 🔐 Login Security Analysis

## Overview
This project simulates authentication logs to perform security analysis and detect suspicious behavior patterns such as brute force attempts, repeated login failures, and unusual access times.

It is designed as an entry-level cybersecurity portfolio project focused on log analysis and data-driven security insights.

## Objectives
- Analyze login success and failure patterns
- Detect possible brute force attacks
- Identify suspicious login behavior by IP and user
- Understand how security logs are structured and analyzed in real-world systems

## Cybersecurity Concepts Applied
- Log analysis (Security Event Monitoring)
- Brute force detection logic
- Behavioral anomaly detection
- Basic SOC (Security Operations Center) thinking
- Data-driven security monitoring

## Tools Used
- SQLite (via SQLite Online)
- SQL (Structured Query Language)
- CSV (data export for logs simulation)

## Dataset Structure
The dataset simulates authentication logs with the following fields:

- `user_id` → identifier of the user
- `login_time` → timestamp of login attempt
- `ip_address` → source IP of access
- `status` → result of login attempt (success / fail)


## 🔍 Key Analyses Performed

### 1. Failed Login Attempts by User
Identifies users with the highest number of failed logins.

### 2. Brute Force Detection
Detects repeated failed login attempts from the same IP and user combination.

### 3. Suspicious Login Time Analysis
Identifies login attempts during unusual hours (possible intrusion attempts).

### 4. Success vs Failure Rate
Provides overview of authentication reliability and potential risk level.

## Security Insight
This project demonstrates how raw authentication logs can be transformed into actionable security insights, similar to what is done in SOC environments for early threat detection.

## Outcome
This project builds foundational skills in:
- Cybersecurity analytics
- SQL querying for security data
- Log-based threat detection
- Security mindset for SOC environments

---

## Author
Transitioning professional from Marketing Strategy & Data Analysis into Cybersecurity, focused on Security Analytics, Data Intelligence, and Risk Detection.
