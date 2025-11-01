# CCRA (Customer Credit Report Automation)
## _Overview_
This UiPath project automates the end-to-end customer credit check process, integrating multiple systems to gather comprehensive credit information and deliver consolidated reports to stakeholders in Singapore's banking sector.

## _Key Features_
- Automated email-based request handling and user information extraction.
- Multi-system integration: AS400 terminal, Credit Bureau, Quest net, and internal banking websites.
- Data consolidation and business rule application for credit check report generation.
- MS Access database for transaction logging and audit trail management.
- Automated email delivery of final consolidated credit reports to requesters.
- Support for chargeable credit inquiries with complex search logic and user-specific business rules.

## _Technology Stack_
- RPA Tool: UiPath
- Systems Integrated: AS400 Terminal, Credit Bureau, Quest Net, Internal Banking Portals
- Data Management: Microsoft Access, Excel, Outlook
- Environment: Singapore Banking

## _Workflow Summary_
1. Bot receives customer credit check requests via email and extracts user-specific parameters.
2. Queries AS400 system to retrieve foundational customer details and stores them in MS Access.
3. Executes additional inquiries on Credit Bureau, Quest Net, and internal banking systems to gather comprehensive credit history.
4. Applies business logic to consolidate all collected data and generate a structured credit report.
5. Sends the finalized report back to the requester via email with logging for compliance and auditing.

## _Use Cases_
- Automated credit assessment and risk evaluation in banking operations.
- Multi-source data aggregation for customer due diligence and compliance.
- Reducing manual effort and turnaround time for credit inquiries while maintaining accuracy.

## _Complexity Highlights_
- Handles chargeable credit inquiries requiring careful orchestration and exception management.
- Supports dynamic business rules per customer profile and search type.
- Robust error handling and retry logic for terminal and web-based interactions.

Author

_Poovarasan Gunasekaran_

