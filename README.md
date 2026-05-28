# Azure Monitoring Dashboard Project

Enterprise-style Azure cloud monitoring and observability project using Azure Monitor, Log Analytics, KQL, Azure Workbooks, Diagnostic Settings, Storage Accounts, and Azure Activity Logs.

This project demonstrates how cloud engineers monitor Azure environments by collecting operational events, routing logs into a centralized Log Analytics Workspace, querying activity with KQL, and visualizing real cloud activity through an Azure Monitoring Dashboard.

---

## Project Overview

The goal of this project was to build a real Azure monitoring and logging environment that tracks administrative activity, resource changes, policy events, and operational updates inside an isolated Azure resource group.

This project simulates how cloud operations teams monitor enterprise environments for visibility, troubleshooting, governance, and security awareness.

The monitoring environment was built using a dedicated resource group so it would remain separate from other Azure projects.

---

## Project Architecture

The project includes the following Azure resources:

- Azure Resource Group
- Azure Log Analytics Workspace
- Azure Activity Logs
- Azure Diagnostic Settings
- Azure Monitor Logs
- Azure Workbook Dashboard
- Azure Storage Account
- Resource Tags
- KQL Queries

---

## Technologies Used

- Microsoft Azure
- Azure Monitor
- Log Analytics Workspace
- Kusto Query Language
- Azure Workbooks
- Azure Activity Logs
- Diagnostic Settings
- Azure Storage Account
- Azure Resource Manager
- Cloud Governance Tags

---

## What I Built

In this project, I created an Azure monitoring environment that can:

- Collect Azure administrative activity
- Track resource creation and updates
- Monitor tag changes
- Capture policy audit events
- Query cloud activity logs with KQL
- Visualize activity in a dashboard
- Organize resources inside a dedicated resource group
- Demonstrate cost-conscious cloud resource management

---

## Resource Group Design

A dedicated resource group was created for this project:

```text
rg-monitoring-lab
