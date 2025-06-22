# data-analyst-bimla
# Descriptive Analysis 
**Project Description:** 🌐Cloud-Based Data Pipeline for Financial Data Management

**Project Title:** 📊 Design and Implementation of a Cloud-Based ETL Workflow at University Canada West

**📌Objective:** The primary goal of this project is to design, evaluate, and implement a cloud-based data pipeline for financial data. The focus is on understanding data ingestion costs, performing cleaning and profiling, and developing a scalable ETL (Extract, Transform, Load) system using AWS services. This project emphasizes practical application of cloud computing concepts to enhance data quality, cost-efficiency, and system reliability.

This project integrates practical cloud computing concepts to enhance data quality, cost-efficiency, and system reliability.

**Dataset:** The dataset originates from a finance group assignment and includes sample business and transactional data. Key features include:

**•	Business Questions:** Contextual queries related to financial analysis

**•	Raw Financial Data:** Used for ingestion, cleaning, and profiling

**•	Metadata:** Structure and relationships within the financial datalake

**•	Profiling Attributes:** Null values, duplicates, data types, and inconsistencies

### 🧭 Methodology

#### 1. Business Analysis and Initial System Design (Week 2)
- **Business Question Analysis:**  
&nbsp;&nbsp;&nbsp;&nbsp;Interpreted Business Problem 3 from the finance domain to identify data and system requirements.
- **Root Cause Identification:**  
&nbsp;&nbsp;&nbsp;&nbsp;Created a Fishbone diagram to explore contributing factors to the data challenge.
- **Datalake Design:**  
&nbsp;&nbsp;&nbsp;&nbsp;Drafted an Excel-based datalake structure.<br>
&nbsp;&nbsp;&nbsp;&nbsp;Visualized the architecture in draw.io for a clear system blueprint.
- **Infrastructure Setup:**  
&nbsp;&nbsp;&nbsp;&nbsp;Deployed an EC2 instance and configured a VPC and security group in AWS to simulate the environment.

#### 2. Cost Evaluation and Data Cleaning Design (Week 3)
- **Cost Analysis of Data Ingestion:**  
&nbsp;&nbsp;&nbsp;&nbsp;Used the AWS Pricing Calculator to evaluate data transfer and storage costs.
- **Data Cleaning Blueprint:**  
&nbsp;&nbsp;&nbsp;&nbsp;Listed common data issues and resolution strategies in Excel.<br>
&nbsp;&nbsp;&nbsp;&nbsp;Visualized the cleaning workflow in draw.io (handling nulls, types, duplicates).
- **Implementation of Cleaning:**  
&nbsp;&nbsp;&nbsp;&nbsp;Conducted profiling and applied cleaning techniques to improve data quality using scripts and tools.

#### 3. Dataset Profiling and ETL Development (Week 4)
- **Profiling Cost Evaluation:**  
&nbsp;&nbsp;&nbsp;&nbsp;Estimated resource costs for profiling and cleaning tasks.
- **ETL Workflow Design:**  
&nbsp;&nbsp;&nbsp;&nbsp;Defined an end-to-end ETL system integrating previously cleaned data.
- **ETL Implementation:**  
&nbsp;&nbsp;&nbsp;&nbsp;Developed and tested ETL scripts to automate data movement, transformation, and loading.

### 🛠️ Tools and Technologies

- **AWS Cloud Platform**: EC2, VPC, Security Groups  
- **Excel**: Data structure planning and issue tracking  
- **Draw.io**: Architecture and process visualization  
- **AWS Pricing Calculator**: Cost estimation  
- **Scripting Tools**: For cleaning and ETL execution

### 📦 Deliverables

- **Detailed weekly progress reports and screenshots** (Weeks 2–4)  
- **Visual models** for Fishbone, Datalake Design, and Cleaning Workflow  
- **Cost estimation documents** for ingestion and profiling stages  
- **Working ETL prototype and documentation**  
- **Summary report** integrating all weekly activities into a cohesive project outcome

## ☁️ AWS Deployment and Service Models

### 📘 Case Study #1: Traditional Computing Model vs Cloud Computing Model
![cs1](https://github.com/user-attachments/assets/14122a4b-9749-4a00-b88e-dc3aebda4a47)
In the traditional computing model, UCW stores data locally in its Vancouver data center, with limited internal access and full control over privacy. In the cloud computing model, data is stored in an AWS data center (Virginia), accessible remotely via the internet, with privacy managed jointly by AWS and UCW under a shared responsibility model. Cloud offers more flexibility and scalability, while traditional systems provide full internal control.

### 📘 Case Study #2: Cloud Deployment Models
![Picture1](https://github.com/user-attachments/assets/fe2915da-f0b2-4933-b9cc-cc9ea08f4ad8)
![Picture2](https://github.com/user-attachments/assets/76512fbb-e360-4a6d-9cc6-99e61906de40)
<br>In a Public Cloud, data is stored in a provider's region (like AWS Virginia), accessed via the internet, and privacy is managed through a shared responsibility model. A Private Cloud keeps data within UCW or a dedicated environment, with restricted access and full privacy control by the organization. Hybrid Cloud combines both public and private setups, with shared access and privacy responsibilities. Multi-Cloud uses multiple cloud providers, requiring coordinated access and strong governance to ensure consistent privacy and compliance.

### 📘 Case Study #3: Cloud Service Models
![Picture3](https://github.com/user-attachments/assets/15412d18-1ede-4886-8766-a58f181e7432)
![Picture4](https://github.com/user-attachments/assets/806a1012-c738-4ce5-8c21-c8023ab4d171)
<br>This table compares IaaS, PaaS, and SaaS based on data location, access, and privacy responsibilities. In IaaS, the Finance Operation Team provisions and controls all infrastructure in the AWS Virginia region, including storage and operating systems, and manages privacy through tools like IAM and encryption. In PaaS, AWS manages the infrastructure, while the Finance Operation Team handles application data and enforces app-level privacy. In SaaS, the AWS Operation Team manages the entire backend and data environment, with the Finance Operation Team only interacting with the application and ensuring compliant use of the data.

## 💰 AWS Cost Analysis

### 📊 Case Study #4: Total Cost of Ownership (TCO) – Delaware North
![Picture5](https://github.com/user-attachments/assets/08127292-8e03-44af-8c8b-8531d6541d64)
<br>This case highlights a global company with over 200 locations and 500 million customers aiming to reduce its total cost of ownership. Facing challenges like rapid solution deployment and aging infrastructure, the company set out to improve efficiency, lower costs, and achieve a positive ROI. By migrating its on-premises data center to AWS, eliminating 205 servers, and leveraging 3-year EC2 Reserved Instances, the company optimized resources, enhanced security and disaster recovery, and improved operational efficiency. As a result, provisioning new services now takes just one day, and ongoing cost savings are being realized.

### 📊 Case Study #5:AWS Pricing Calculator
![Picture6](https://github.com/user-attachments/assets/b8936b9c-77a9-45b9-9f86-d18eecff15e6)
![Picture7](https://github.com/user-attachments/assets/40de4c3b-2480-45c4-b31a-2f3beabeef24)
![Picture8](https://github.com/user-attachments/assets/d43f44e2-f8a2-47a7-b149-a003a4835cbb)

### 📊 Case Study #6:Support Plan
![Picture9](https://github.com/user-attachments/assets/717dae1c-e797-4c9f-a796-e9e0520441d2)

## 📦 AWS Global infrastructure 

### 📊 Case Study #7: AWS Global Infrastruture
![Picture10](https://github.com/user-attachments/assets/ac0712a1-a7a2-489b-a14c-3199f437a1e0)
![Picture11](https://github.com/user-attachments/assets/2b2396fa-5d28-4c8d-9e47-5a17305d42b8)
<br>In the given architecture, dataset location is managed across all three levels—Regional Edge Cache, Edge Location, and Region—since data can be cached or stored at each of these points to optimize availability and performance. Dataset access is available at the Edge Location and Region levels, allowing users to retrieve or interact with the data efficiently depending on proximity and system routing. However, dataset privacy is strictly maintained at the Region level, where AWS data centers enforce comprehensive security controls, compliance standards, and privacy regulations to protect sensitive information.

## 🔐 AWS IAM (Identity and Access Management)

### 🧩 Case Study #8: Who is Responsible?
![Picture12](https://github.com/user-attachments/assets/ed56f24a-83d7-4cb5-b11c-7f44add9ad2a)
<br>In the given architecture, EC2 is a shared responsibility between AWS and UCW. AWS is responsible for providing and maintaining the underlying infrastructure that supports the EC2 service, while UCW is responsible for configuring, managing, and utilizing the EC2 instances according to their operational needs. On the other hand, the platform, software, and dataset are fully managed by UCW, as shown by the active involvement of the finance operation team and their direct control within the UCW-managed environment. This division ensures that while AWS secures and operates the foundational infrastructure, UCW retains control over the application layer and data management.

### 🧩 Case Study #9: IAM practrice: Lab 1
![lab1](https://github.com/user-attachments/assets/c0cc1588-eaae-418a-a9ef-1d8e56910a31)

## 🌐 AWS VPC (Virtual Private Cloud)

### 🧪 Case Study #10: Build Your VPC – Lab 2
![lab2](https://github.com/user-attachments/assets/9e63d576-bb6f-49d2-8be7-668551677bf3)

## ⚙️ AWS Lambda

### 🧪 Case Study #11: Create an AWS Lambda Function
![lab3](https://github.com/user-attachments/assets/6267d6de-632d-4fa4-9239-67e64be6fb51)

## 💾 AWS EBS (Elastic Block Store)

### 🧪 Case Study #12: Working with Amazon EBS – Lab 4
![lab4](https://github.com/user-attachments/assets/cf6a984e-6c3a-4148-b080-e7eac0f90f0e)






