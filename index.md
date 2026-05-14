---
layout: home
---

# Nathan Herrmann

**Software Engineer II**

📍 South Bend, Indiana | 📞 801-368-7037 | ✉️ NathanJHerrmann@gmail.com | 🔗 [\[LinkedIn\]](https://www.linkedin.com/in/nathor/)

---

## Summary

Software Engineer with 5+ years of experience building and maintaining enterprise-grade financial software on the NetSuite platform. Specialized in SuiteScript 2.x development, payment processing systems (ACH/NACHA, cross-border, AvidPay), and cloud-based middleware solutions using C# and Azure. Proven track record of leading feature development, migrating legacy systems, and delivering reliable releases across multiple product lines.

---

## Skills

**Languages & Frameworks**
- JavaScript / SuiteScript 2.x
- C# / .NET 6
- Entity Framework Core

**NetSuite Development**
- SuiteScript 2.x
- SuiteApp Development Framework (SDF)
- Custom Record Types, Saved Searches, Portlets, Dashboards
- Bundle Deployment & Release Management

**Cloud & Infrastructure**
- Microsoft Azure (Blob Storage, Service Bus, Azure Functions)
- Azure DevOps

**Practices & Patterns**
- Test-Driven Development (TDD)
- SOLID Principles, Clean Code, Domain-Driven Design
- Agile / Scrum
- CI/CD

---

## Experience

### AvidXchange — Charlotte, NC (Remote)
**Software Engineer II** | 2020 – Present

AvidXchange is a B2B payments and accounts payable automation company. As a member of the NetSuite product team, I design, develop, and maintain SuiteApps that integrate NetSuite with AvidXchange's payment platform.

#### Payment Processing (AvidPay, FastPay, NACHA/ACH)
- Rebuilt the AvidPay and FastPay process payments search to support more than 4,000 records and improve page load performance, resolving critical production slowness issues
- Converted AvidPay and FastPay payment submission to a **Map/Reduce** architecture, enabling parallel processing of large payment batches (50+ payments)
- Designed and implemented the **NACHA/Standard ACH payment flow** end-to-end, including new custom record types, process payments page, ACH account setup, and required field validation
- Added support for **Customer Refunds and Expense Reports** in AvidPay XML payloads
- Resolved multiple production defects including duplicate batch creation on page refresh, incorrect payment dates, and malformed vendor address data in XML submissions
- Implemented a cleared check image suitelet for retrieving check images from AvidXchange's API
- Added descriptive inline error messaging for failed payments on the process payments page

#### Cross-Border Payments (CBP)
- Developed the full **OAuth 2.0 authentication flow** for CBP, including token request, token management, and credential storage in a custom NetSuite record
- Built the **CBP Vendor Account setup feature**, covering country/currency selection, form parsing, funding account enablement, and API interactions
- Implemented `Initiate Authentication` and `Receive and Record Authentication Response` user stories as part of the CBP API integration
- Resolved defects in funding account creation error handling and CBP account record field persistence

#### Approvals & Invoice Workflows
- Converted the Approvals pages from SuiteScript 1.0 to **SuiteScript 2.0**, including resolving the 1,000-vendor limit
- Developed a **Dashboard Portlet** for daily approvals reminders using saved searches
- Implemented **Approval Plugins** architecture, allowing modular approval routing logic
- Added invoice image links to the payments approval page for improved reviewer context
- Built the `Set Initial Approval Status` and `Retry Assigning Approval Status` features for newly created payments

#### AFN Middleware (Azure)
- Built and tested **Azure Blob Storage access** via a C# class library, including permissions research and proof-of-concept work
- Developed the **Notifications Processor Function App** using Azure Functions
- Implemented the `NetSuite Account Record` middleware data model (Debtor Info, Creditor Info, Payment Info Merge) across multiple user stories
- Contributed to Azure Service Bus and Entity Framework proofs of concept for the AFN middleware platform

#### SuiteApp–to–SDF Migration
- Researched and led the plan to migrate the team's development workflow from classic bundle development to **SuiteApp Development Framework (SDF)**
- Performed test bundle conversion, assessed customer impact, and documented findings
- Executed multiple SuiteApp release submissions to the NetSuite Marketplace

#### ACH & Positive Pay File Generation
- Converted ACH File Generation and Positive Pay File Generation pages to **SuiteScript 2.0**
- Implemented fix for ACH file gen issues related to iframe/cookie handling in various browsers
- Added ACH File Gen fields and Company ID requirements to the process payments page

#### Bundle & Release Management
- Executed 10+ versioned release cycles across PAY, BS, CBP, and AFN product lines (2021–2025), including bundle versioning, script locking, changelog updates, and QA deployments
- Managed release readiness for product versions including Jelly Bean, Helium, Lithium, Beryllium, Boron, and Begonia

#### Other Contributions
- Developed an **auto-create Bills feature** for syncing invoices from AvidInvoice into NetSuite as Bill records
- Built the `Copy Customer Script Permissions on Bundle Install` feature to automate permission propagation
- Added field-level character validation for AvidPay payment submissions
- Implemented in-app sunset messaging for the classic bundle
- Designed configurable test environment targets to support QA flexibility across dev accounts

---

## Education

**University of Utah** — Salt Lake City, UT
Bachelor of Science in Computer Science | Graduated 2020

---

## Certifications

- NetSuite SuiteScript 2.0 Developer II *(in progress)*
- Microsoft AI Fundamentals *(in progress)*

---

*References available upon request.*
