# CloudWatch-SNS
# ☁️ AWS CloudWatch + SNS Monitoring & Alerts

A hands-on AWS project demonstrating how to use **Amazon CloudWatch** and **Amazon SNS (Simple Notification Service)** to monitor AWS resources and receive automated alerts when specific conditions or thresholds are triggered.

## 🚀 Project Overview

This project implements a simple AWS monitoring and notification system:

**AWS Resource → CloudWatch → CloudWatch Alarm → SNS → Email Notification**

When a monitored metric crosses a defined threshold, CloudWatch triggers an alarm and sends a notification through SNS.

## 🛠️ AWS Services Used

* ☁️ **Amazon CloudWatch** — Monitoring and metrics
* 🔔 **Amazon SNS** — Notifications and alerts
* 🖥️ **AWS Management Console** — Configuration and monitoring

## ⚙️ How It Works

1. Create or select an AWS resource to monitor.
2. Open **Amazon CloudWatch**.
3. Configure a metric and define a threshold.
4. Create a **CloudWatch Alarm**.
5. Create an **SNS Topic**.
6. Subscribe an email endpoint to the SNS topic.
7. Connect the SNS topic to the CloudWatch alarm.
8. Trigger the condition and receive an email notification.

## 📊 Architecture

```text
        AWS Resource
             │
             ▼
      Amazon CloudWatch
             │
             ▼
     CloudWatch Alarm
             │
             ▼
         Amazon SNS
             │
             ▼
      📧 Email Alert
```

## 🎯 Key Learning

* Understanding AWS monitoring with CloudWatch
* Creating and configuring CloudWatch alarms
* Working with CloudWatch metrics
* Creating SNS topics and subscriptions
* Automating alert notifications
* Building a basic AWS monitoring architecture

## 🔮 Future Improvements

* Add **SMS notifications**
* Integrate with **AWS Lambda**
* Create a CloudWatch dashboard
* Monitor multiple AWS resources
* Automate infrastructure using **Terraform**
* Implement automated incident-response workflows

## ⭐ Conclusion

This project provides a practical introduction to **AWS monitoring and automated alerting**, showing how CloudWatch and SNS can work together to improve infrastructure visibility, reliability, and response time.
