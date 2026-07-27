# 02-business — Business Capability Map

**Document ID:** BCM-001  
**Version:** 1.0.0  
**Status:** Draft  
**Owner:** Business Architecture Office  
**Last Updated:** 2026-07-28

## 1. Purpose
This document defines the core business capabilities that ARQA must support across products, services, and operational workflows.

## 2. Core Capabilities

### 2.1 Identity and Access
- user authentication
- authorization
- role management
- organization membership
- session management

### 2.2 User and Organization Management
- user profiles
- company profiles
- team structures
- permissions mapping
- tenant isolation

### 2.3 Workflow and Task Management
- task creation
- assignment
- approvals
- status tracking
- escalation

### 2.4 Document Management
- document storage
- version control
- approval history
- metadata indexing
- search

### 2.5 AI Services
- content understanding
- recommendations
- summarization
- classification
- explainable outputs

### 2.6 Data and Analytics
- operational reporting
- KPI tracking
- audit reporting
- trend analysis
- exports

### 2.7 Integration Services
- API integration
- webhooks
- third-party connectors
- import/export workflows
- event exchange

### 2.8 Notifications
- email notifications
- in-app notifications
- push notifications
- alert routing
- notification preferences

### 2.9 Security and Compliance
- audit logging
- encryption controls
- policy enforcement
- consent tracking
- retention rules

## 3. Capability Design Rules
Each capability must have:
- a clear owner,
- a bounded context if implemented in software,
- a data classification rule,
- and a documented integration strategy.

## 4. Dependency Guidance
Capabilities should not depend on each other through direct database access. Integration must occur through contracts, services, or events.
