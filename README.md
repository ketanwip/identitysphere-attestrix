# IdentiSphere Feature Guide

**Comprehensive overview of all features and capabilities offered by IdentiSphere Access Management Platform**

---

## Table of Contents

- [Access Management & Governance](#access-management--governance)
- [Cost Optimization & Analytics](#cost-optimization--analytics)
- [Security & Authentication](#security--authentication)
- [Self-Service & User Experience](#self-service--user-experience)
- [Integration & Automation](#integration--automation)
- [AI-Powered Features](#ai-powered-features)
- [Compliance & Audit](#compliance--audit)
- [Administration & Management](#administration--management)
- [Key Benefits Summary](#key-benefits-summary)

---

## Access Management & Governance

Comprehensive access control, provisioning, and governance features to ensure the right people have the right access at the right time.

### Application Management

Centralized management of all applications and systems integrated with the platform. Create, configure, and manage application connections with full provisioning capabilities.

**Key Benefits:**
- Unified view of all integrated applications
- Support for disconnected, connected, and trusted applications
- Extended attribute management per application
- Application-specific provisioning configurations
- Bulk import and export capabilities

### Entitlement Management

Granular control over user permissions, roles, groups, and access levels across all applications. Manage entitlements with cost tracking and usage analytics.

**Key Benefits:**
- Fine-grained access control
- Entitlement discovery and mapping
- Cost tracking per entitlement
- Usage analytics and optimization
- Bulk entitlement operations

### Access Bundles

Pre-configured bundles of applications and entitlements that can be assigned to users or groups. Streamline onboarding and role-based access provisioning.

**Key Benefits:**
- Rapid user onboarding
- Consistent access provisioning
- Role-based bundle templates
- One-click bundle assignment
- Bundle provisioning automation

### User & Group Management

Complete user lifecycle management with support for organizational groups, hierarchies, and extended attributes. Bulk operations and CSV import/export.

**Key Benefits:**
- User creation with extended attributes
- CSV bulk user upload
- Organizational group management
- Manager hierarchy support
- User search and filtering

### Access Request Workflow

Comprehensive request and approval workflow system with multi-level approvals, delegation, and automated provisioning upon approval.

**Key Benefits:**
- Self-service access requests
- Multi-level approval chains
- Approval delegation
- Email-based approvals
- Automated provisioning

### Approval Configuration

Flexible approval rules engine allowing administrators to configure approval workflows based on applications, entitlements, user attributes, and risk levels.

**Key Benefits:**
- Customizable approval rules
- Condition-based routing
- Risk-based approvals
- Time-based approvals
- Approval analytics

---

## Cost Optimization & Analytics

Advanced analytics and cost optimization features to identify unused licenses, optimize spending, and maximize ROI on software investments.

### Entitlement Cost Tracking

Track and manage costs associated with each entitlement across different currencies and billing frequencies. Comprehensive cost analytics and reporting.

**Key Benefits:**
- Per-entitlement cost tracking
- Multi-currency support
- Flexible billing frequencies
- Cost history and trends
- Bulk cost import/export

### Usage Analytics

Deep insights into application and entitlement usage patterns. Identify unused licenses, underutilized resources, and optimization opportunities.

**Key Benefits:**
- User-level usage tracking
- Application usage analytics
- Unused license identification
- Usage trend analysis
- Customizable timeframes

### Cost Optimization Recommendations

AI-powered recommendations for cost savings through license reallocation, unused license identification, and usage pattern optimization.

**Key Benefits:**
- Unused license detection
- Reallocation suggestions
- Cost savings calculations
- Priority-based recommendations
- Automated optimization plans

### Advanced Access Analytics

Peer-based analytics comparing user access patterns with similar users (same department, role, or custom attributes) to identify access anomalies and optimization opportunities.

**Key Benefits:**
- Peer comparison analytics
- Department-based analysis
- Role-based access patterns
- Configurable attribute grouping
- Access percentage calculations

### User Cost Analytics

Individual user cost analysis showing total monthly costs, cost per application, and cost optimization opportunities per user.

**Key Benefits:**
- Per-user cost breakdown
- Monthly cost calculations
- Application cost distribution
- Cost trend analysis
- Optimization suggestions

---

## Security & Authentication

Enterprise-grade security features including multi-factor authentication, SSO integration, and advanced authentication rules.

### Multi-Factor Authentication (MFA)

Comprehensive MFA support with multiple authentication methods including TOTP, Email OTP, Keystroke Dynamics, and Manager Verification.

**Key Benefits:**
- TOTP (Google Authenticator, Authy)
- Email-based OTP
- Keystroke Dynamics (biometric)
- Manager Verification
- Backup codes support

### SAML Single Sign-On (SSO)

Enterprise SSO integration supporting SAML 2.0 with external identity providers including Auth0, Okta, Azure AD, and more.

**Key Benefits:**
- SAML 2.0 compliance
- Multiple IdP support
- JIT user provisioning
- Attribute mapping
- SP-initiated and IdP-initiated flows

### Group-Based Authentication Rules

Flexible authentication rules based on user groups with configurable MFA requirements, allowed methods, and authentication chains.

**Key Benefits:**
- Group-specific MFA rules
- Priority-based rule evaluation
- Authentication chain support
- Location/time-based bypass
- Rule testing and validation

### Location & Time-Based Bypass

Intelligent authentication bypass based on trusted locations, IP addresses, time of day, and day of week for improved user experience.

**Key Benefits:**
- IP-based location bypass
- Geolocation support
- Time-based bypass rules
- Timezone-aware verification
- Combined location + time rules

### Manager Verification

Manager-based MFA verification where managers can approve login attempts for their direct reports with risk analytics and time-bound codes.

**Key Benefits:**
- Manager approval workflow
- Risk indicator analytics
- Time-bound verification codes
- Email notifications
- Verification dashboard

### Password Policy Management

Configurable password policies with complexity requirements, expiration rules, and account lockout policies.

**Key Benefits:**
- Password complexity rules
- Expiration policies
- Account lockout management
- Password history
- Policy enforcement

---

## Self-Service & User Experience

Intuitive self-service features that empower users to manage their own access while reducing IT workload.

### Access Catalog

Self-service catalog where users can browse available applications and entitlements, request access, and manage their access portfolio.

**Key Benefits:**
- Browse applications and entitlements
- Search and filter capabilities
- Shopping cart functionality
- Request for self or others
- Personalized recommendations

### AI-Powered Access Recommendations

Intelligent recommendations based on peer access patterns, role-based analysis, and department trends to suggest relevant access.

**Key Benefits:**
- Peer-based recommendations
- Role-based suggestions
- Department popularity analysis
- Access percentage indicators
- One-click request from recommendations

### Request Tracking

Complete visibility into access request status, approval progress, and provisioning status with real-time updates.

**Key Benefits:**
- Request status tracking
- Approval progress visibility
- Email notifications
- Request history
- Search and filter requests

### User Profile Management

Self-service profile management where users can view and update their information, organizational hierarchy, and preferences.

**Key Benefits:**
- Profile information management
- Organizational chart view
- Extended attributes display
- MFA settings management
- Access history view

### My Applications Dashboard

Personalized dashboard showing user's assigned applications, pending approvals, requests, and quick access to key features.

**Key Benefits:**
- Assigned applications view
- Pending items counter
- Quick access tiles
- Activity feed
- Notification badges

### Access History

Complete audit trail of user access changes, request history, and provisioning events with search and filter capabilities.

**Key Benefits:**
- Complete access history
- Search and filter options
- Export capabilities
- Timeline view
- Detailed event information

---

## Integration & Automation

Powerful integration capabilities and automation features to connect with any system and automate provisioning workflows.

### API Connectors

Flexible connector framework supporting REST APIs, SOAP, and custom integrations with authentication, retry logic, and error handling.

**Key Benefits:**
- REST API support
- Multiple authentication methods
- Custom header configuration
- Retry and error handling
- Connection testing

### Provisioning Operations

Comprehensive provisioning operations including user CRUD, entitlement management, group operations, and bidirectional sync.

**Key Benefits:**
- User create/update/delete
- Entitlement management
- Group operations
- Bidirectional synchronization
- Bulk operations

### Scheduled Jobs

Automated scheduled jobs for data synchronization, user provisioning, entitlement discovery, and custom workflows with flexible scheduling.

**Key Benefits:**
- Flexible scheduling (cron, intervals)
- Custom JavaScript scripts
- Database and API operations
- Execution logging
- Error handling and retries

### Import & Export

Bulk import and export capabilities for users, applications, entitlements, and costs with CSV support and validation.

**Key Benefits:**
- CSV import/export
- Bulk user creation
- Application import
- Entitlement discovery
- Import validation and reporting

### Expression Engine

Powerful expression engine for data transformation, field mapping, conditional logic, and dynamic value generation.

**Key Benefits:**
- Data transformation
- Field mapping
- Conditional logic
- Function library
- Expression testing

### Script Builder

Visual script builder for creating custom provisioning scripts with drag-and-drop interface and code generation.

**Key Benefits:**
- Visual script building
- JavaScript code generation
- Script testing
- Template library
- Version control

---

## AI-Powered Features

Cutting-edge AI capabilities powered by configurable AI providers to automate complex tasks and provide intelligent insights.

### AI Application Generation

Generate complete application configurations using natural language descriptions. AI understands your framework and generates production-ready configurations.

**Key Benefits:**
- Natural language input
- Complete configuration generation
- Provisioning operation setup
- Extended attribute creation
- Validation and suggestions

### Multi-Provider AI Support

Support for multiple AI providers including OpenAI, Anthropic, Google, and local models. Choose the best model for each use case.

**Key Benefits:**
- OpenAI (GPT-4, GPT-3.5)
- Anthropic (Claude)
- Google (Gemini)
- Local models (Ollama)
- User-configurable credentials

### AI Database Query

Natural language to SQL conversion allowing administrators to query application data using plain English questions.

**Key Benefits:**
- Natural language queries
- SQL generation
- Schema-aware queries
- Safe query execution
- Result visualization

### AI Access Recommendations

Intelligent access recommendations using AI to analyze user patterns, roles, and peer access to suggest relevant applications and entitlements.

**Key Benefits:**
- Pattern recognition
- Role-based suggestions
- Peer analysis
- Risk assessment
- Approval recommendations

### AI-Powered Analytics

Advanced analytics powered by AI to identify access anomalies, optimization opportunities, and security risks.

**Key Benefits:**
- Anomaly detection
- Pattern analysis
- Predictive insights
- Risk scoring
- Automated recommendations

---

## Compliance & Audit

Comprehensive audit logging, compliance reporting, and security monitoring capabilities for regulatory compliance.

### Enhanced Audit Logging

Comprehensive audit trail of all system events including user actions, access changes, configuration updates, and security events.

**Key Benefits:**
- Complete event logging
- Geolocation tracking
- IP address logging
- User agent tracking
- Searchable audit logs

### SIEM Integration

Vendor-agnostic SIEM integration supporting multiple providers simultaneously including Splunk, New Relic, Sumo Logic, and more.

**Key Benefits:**
- Multiple SIEM provider support
- Parallel log forwarding
- Custom payload formats
- Retry logic
- Fault tolerance

### Compliance Reporting

Pre-built and customizable compliance reports for access reviews, user certifications, and regulatory requirements.

**Key Benefits:**
- Access review reports
- User certification reports
- Custom report builder
- Scheduled report delivery
- Export capabilities

### Access Certification

Automated access certification campaigns where managers review and certify user access on a regular basis.

**Key Benefits:**
- Automated certification campaigns
- Manager-based reviews
- Bulk certification
- Certification history
- Reminder notifications

### Risk Analytics

Advanced risk analysis identifying unusual access patterns, privilege escalations, and security anomalies.

**Key Benefits:**
- Anomaly detection
- Risk scoring
- Privilege escalation alerts
- Geographic anomaly detection
- Risk dashboard

---

## Administration & Management

Comprehensive administrative tools and management features for system configuration, monitoring, and optimization.

### Configurable Analytics

Flexible analytics configuration allowing organizations to define which user attributes to use for access pattern analysis and recommendations.

**Key Benefits:**
- Custom attribute grouping
- Multi-attribute analytics
- Priority-based configurations
- Dynamic analytics
- Organization-specific insights

### Extended Attributes

Dynamic user and application attribute management with support for custom data types, validation rules, and select lists.

**Key Benefits:**
- Custom attribute definitions
- Multiple data types
- Validation rules
- Select list support
- Searchable attributes

### Failed Operations Management

Comprehensive management of failed API operations with retry capabilities, error analysis, and bulk retry functionality.

**Key Benefits:**
- Failed operation tracking
- Error analysis
- Retry functionality
- Bulk retry operations
- Operation history

### Email Configuration

Flexible email service configuration supporting SMTP, custom providers, and email templates for notifications and alerts.

**Key Benefits:**
- SMTP configuration
- Email template management
- Test email functionality
- Encrypted credentials
- Multiple provider support

### Branding & Customization

Customize platform branding including logos, colors, and email templates to match your organization's identity.

**Key Benefits:**
- Logo upload
- Color customization
- Email template branding
- Custom CSS support
- Preview functionality

### System Analytics

System-wide analytics including user activity, application usage, request trends, and performance metrics.

**Key Benefits:**
- User activity metrics
- Application usage statistics
- Request trend analysis
- Performance monitoring
- Custom dashboards

### Session Management

Comprehensive session management with active session tracking, session termination, and security monitoring.

**Key Benefits:**
- Active session tracking
- Session termination
- Session analytics
- Security monitoring
- Bulk session management

### Rate Limiting

Configurable rate limiting to protect APIs and prevent abuse with per-user and per-endpoint limits.

**Key Benefits:**
- Per-user rate limits
- Per-endpoint limits
- Customizable thresholds
- Rate limit monitoring
- Graceful degradation

---

## Key Benefits Summary

### 💰 Cost Savings
Identify and eliminate unused licenses, optimize entitlement allocation, and reduce software spending through data-driven insights.

### 🔒 Security
Multi-layered security with MFA, SSO, risk analytics, and comprehensive audit logging to protect your organization.

### ⚡ Efficiency
Automate provisioning workflows, reduce manual IT tasks, and enable self-service access management.

### 📋 Compliance
Meet regulatory requirements with comprehensive audit trails, access certifications, and compliance reporting.

### 🤖 Intelligence
AI-powered recommendations and analytics help make informed decisions about access management.

### 🔧 Flexibility
Vendor-agnostic architecture supports any integration, SIEM provider, or AI model you choose.

---

## About IdentiSphere

IdentiSphere is a comprehensive access management platform that provides identity and access management (IAM) capabilities including user provisioning, access requests, approvals, multi-factor authentication, and integration with external systems.

**Version:** 2.0  
---

*For detailed implementation guides, please refer to the Administrator Guide and Developer Guide.*



# identitysphere-attestrix
Feature details on IdentitySphere and Attestrix

# Attestrix: Product Overview for Investors & Partners

## Executive Summary
Attestrix is a comprehensive Identity Governance and Administration (IGA) platform designed to streamline access management, ensure compliance, and reduce security risks for modern enterprises. By combining robust Role-Based Access Control (RBAC) with intelligent certification campaigns and automated deviation detection, Attestrix empowers organizations to maintain a "least privilege" security posture without sacrificing operational efficiency.

## Key Value Propositions

*   **Unified Identity Visibility**: Centralize user, role, and application access data into a single pane of glass.
*   **Automated Compliance**: Streamline access reviews and certifications to meet regulatory requirements (SOX, GDPR, HIPAA) with less manual effort.
*   **Risk Reduction**: Proactively identify and remediate access deviations, orphan accounts, and high-risk role assignments.
*   **Operational Efficiency**: Empower application owners and managers to review access quickly through intuitive dashboards, reducing IT burden.

## Detailed Feature Breakdown

### 1. Core Identity & Access Management
Attestrix provides a solid foundation for managing digital identities and their access rights.

*   **User Registry**: comprehensive profiles for all users, tracking status (active/inactive), hierarchy (manager relationships), and role assignments.
*   **Application Registry**: Centralized management of all enterprise applications, including ownership assignment, risk classification (High/Medium/Low), and role definitions.
*   **Role-Based Access Control (RBAC)**:
    *   **Role Engineering**: Define and manage roles based on business functions.
    *   **Role Mapping**: Map business roles to specific application permissions.
    *   **Visual Hierarchy**: Visualize role composition and inheritance to understand complex access structures.

### 2. Intelligent Access Certification
The core engine of Attestrix, driving compliance through automated review campaigns.

*   **Multi-Type Campaigns**: Support for various review strategies:
    *   **User Access Reviews**: Managers review their direct reports' access.
    *   **RBAC Role Reviews**: Role owners certify the composition and assignment of roles.
    *   **Deviation Reviews**: Targeted reviews for access that falls outside of standard patterns.
    *   **Role Owner Reviews**: Verification of role ownership and metadata.
*   **Smart Review Workflow**:
    *   **Bulk Actions**: Approve or revoke access in bulk to save time.
    *   **Delegation**: Delegate reviews to the most appropriate person.
    *   **Progress Tracking**: Real-time dashboards showing campaign completion rates.
    *   **Justification Enforcement**: Require comments for revocations or exceptions.

### 3. Risk & Security Intelligence
Proactive features to detect and mitigate security threats.

*   **Deviation Detection**: Automatically identifies "extra access" (permissions a user has but shouldn't) and "missing access" (permissions a user needs but lacks) based on peer analysis or role definitions.
*   **Orphan Account Management**: Detects and flags accounts that are no longer associated with an active employee, preventing unauthorized access via "ghost" accounts.
*   **Risk Scoring**: Assigns risk levels to applications and roles, allowing organizations to prioritize reviews on high-risk assets.
*   **IAM AI Assistant**: Intelligent assistant to help administrators query data and gain insights into the identity landscape.

### 4. Reporting & Analytics
Data-driven insights to measure the effectiveness of the identity program.

*   **Executive Dashboards**: High-level metrics on active users, role coverage, and campaign health.
*   **Team Review Dashboard**: specialized view for managers to track their team's access status.
*   **Comprehensive Audit Trails**: Immutable logs of all system actions, reviews, and configuration changes for audit readiness.
*   **Export Capabilities**: Flexible data export (CSV, etc.) for external reporting or offline analysis.

### 5. Administration & Integration
Built for scale and ease of management.

*   **API-First Architecture**: Robust RESTful APIs for integration with HR systems, ITSM tools, and target applications.
*   **Data Ingestion**: Support for bulk uploads and history tracking to easily onboard data.
*   **Flexible Configuration**: Granular control over certification rules, email notifications, and system settings.

## Technical Architecture
Attestrix is built on a modern, scalable, and secure technology stack.

*   **Frontend**: React-based Single Page Application (SPA) offering a responsive, dark/light mode compatible user interface.
*   **Backend**: Node.js/TypeScript micro-services architecture ensuring high performance and type safety.
*   **Database**: PostgreSQL for reliable, relational data storage with optimized queries for large datasets.
*   **Security**: Enterprise-grade security with role-based access to the console itself, secure session management, and input validation.
