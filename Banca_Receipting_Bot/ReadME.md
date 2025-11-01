# Banca Receipting Bot
## _Overview_
The Banca Receipting Bot automates the end-to-end process of receipting for insurance policies using UiPath. It continuously monitors output files from the BPMS Policy Processing Bot, posts receipt numbers into both terminal and web-based systems, and updates reporting files and stakeholders accordingly.

## _Key Features_
- Automated monitoring of batch outputs from upstream bots/systems.
- Receipt number creation and posting to terminal and web insurance platforms.
- Updates receipt numbers and success counts in Excel reports.
- Automated email notifications to clients on successful batch runs.
- Robust error handling and logging for audit and compliance.

## _Technology Used_

- RPA Tool: UiPath
- Integration: File system monitoring, Terminal & Web automation, Excel, Outlook Email

## Workflow Summary
1. Bot continuously monitors for processed files from the BPMS Policy Bot.
2. On file receipt, creates insurance receipts and posts receipt numbers to client systems.
3. Updates receipt data and transaction counts in an Excel report.
4. Sends notification email to the client with summary and success metrics.
5. Supports both terminal interface and modern web UI applications.

## _Use Cases_
- Insurance policy receipt generation and reconciliation.
- Automated reporting for business and compliance teams.
- Batch handling for both legacy (terminal) and modern (web) platforms.



Author

_Poovarasan Gunasekaran_

