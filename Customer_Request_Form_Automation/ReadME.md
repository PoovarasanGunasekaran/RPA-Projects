# CRF (Customer Request Form) Automation
## _Overview_
This UiPath project automates the full lifecycle of Customer Request Form management, including email intake, validation, assignment, daily transaction handling, and record maintenance in Microsoft Access for Hong Leong Bank Berhad.

## _Key Features_
- Automated email extraction and attachment validation for incoming customer requests.
- Dynamic request form checking: prompts user workflow if attachments are missing or invalid.
- Extraction of key transaction details and assignment to relevant teams, with logic to check team availability and workload limits.
- Daily transaction recording in MS Access database to maintain complete audit trails and facilitate business reporting.
- Staff leave handling and request reassignment to ensure timely processing.
- Automated updating and reversal of request status with daily notifications to users.
- Robust error management and logging for compliance.

## _Technology Stack_

- RPA Tool: UiPath
- Data Handling: Microsoft Access
- Integration: Outllook Email, File system, Database operations

## _Workflow Summary_
1. Bot receives form submissions by email, checks attachment validity, and interacts with users for missing/invalid files.
2. Parses valid forms for transaction data, assigns to teams within allowed daily limits, and checks staff leave status.
3. Records every transaction and form handling step in MS Access for complete record-keeping and future reference.
4. At daily intervals, reverts pending or completed statuses and notifies users automatically.

## _Use Cases_
- Automated customer support request tracking in regulated environments.
- End-to-end digital record maintenance for transaction audits and compliance.
- Team workload balancing and staff availability management.

Author

_Poovarasan Gunasekaran_

