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
