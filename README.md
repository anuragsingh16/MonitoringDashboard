# MonitoringDashboard

AWS CloudWatch & Grafana Integration – A Mini-Project on EC2 & Load Balancer Monitoring 
🔹 Project: Real-time Monitoring of EC2 Instances & Load Balancer using AWS CloudWatch & Grafana
🔹 Tech Stack: AWS (EC2, ALB, CloudWatch, IAM, S3, RDS, Glue) | Grafana | Python | Bash

📌 Overview:
Monitoring is crucial for cloud-based applications to ensure optimal performance, detect anomalies, and troubleshoot issues efficiently. In this project, I integrated AWS CloudWatch with Grafana to visualize real-time metrics for both EC2 instances and Application Load Balancer (ALB).

🔹 Steps Followed:
✅ 1. Set Up AWS CloudWatch Metrics for EC2 & ALB

Collected CPUUtilization, NetworkIn, NetworkOut for EC2
Monitored Request Count, 2XX requests, and Latency for ALB
Configured IAM roles with CloudWatchReadOnlyAccess
✅ 2. Created Grafana Data Source for CloudWatch

Integrated Grafana with AWS CloudWatch for real-time monitoring
Defined EC2 Instance ID & Target Groups as Dynamic Variables
✅ 3. Configured Dynamic Queries in Grafana

EC2 Graph: Used $server_ip to track instance performance
ALB Graph: Used $target_group to track request distribution
✅ 4. Visualized Key Metrics in Grafana Dashboard

CPU Utilization, Network Traffic for EC2
Request Count & Error Rates for ALB
✅ 5. Load Testing & Debugging

Simulated requests using curl to validate data flow
Verified logs in CloudWatch & Grafana Query Inspector
📊 Key Learnings:
🔸 How to configure AWS CloudWatch & IAM roles for metric collection
🔸 Building dynamic Grafana dashboards with CloudWatch as a data source
🔸 Using Grafana variables to make monitoring scalable & flexible
🔸 Debugging data flow using AWS CloudWatch Logs & Query Inspector

This project helped me gain hands-on experience in cloud monitoring, AWS observability, and real-time dashboarding! 🎯
