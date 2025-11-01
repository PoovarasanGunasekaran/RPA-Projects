
# Campaign Process Automation
## _Overview_
This UiPath project automates multi-stage campaign management for Hong Leong Bank Berhad. The solution orchestrates mail extraction, data processing, validation, and database operations across Microsoft Access and Teradata, followed by automated uploads to client web portals.

## _Key Features_
- Automated email extraction and content parsing for campaign details.
- Data insertion into permanent tables in Microsoft Access as local bot DB.
- Product validation, campaign state checks, and transaction processing.
- Lead count verification and dynamic reporting over multi-day campaign stages.
- Integration with Teradata for bulk data retrieval, lead extraction, and upload automation.
- Batch file triggering for seamless downstream data processing.

## _Technology Stack_

- RPA Tool: UiPath
- Databases: Microsoft Access, Teradata
- Integration: Email automation, Database management, Batch scripting, Web upload automation

## _Workflow Summary_
1. Bot retrieves campaign emails, parses transaction data, and inserts records into Access tables.
2. Runs validation and campaign checks based on product and table name.
3. Stage 1: Table creation and campaign entry; Stage 2: Lead count validation.
4. Collects and pulls lead information from Teradata, uploading data into web portals.
5. Batch file is triggered with contextual Teradata information for final processing.

## _Use Cases_
- Automated marketing campaign setup and tracking in financial services.
- End-to-end campaign orchestration across multiple platforms, reducing manual errors and processing times.
- Streamlined integration between local and enterprise data stores.

Author

_Poovarasan Gunasekaran_

