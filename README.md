# TP8 - SQL Server Agent Automation and Monitoring

A SQL Server lab covering scheduled jobs, email notifications and error alerts.

## Implemented

- Database Mail configured with a Google SMTP account and `profile1`.
- `AdminDBA` operator receives notifications.
- `job_insertion` inserts a Journal row every 10 minutes.
- Notifications changed from success to failure only.
- Job failure tested by temporarily renaming the destination table.
- Error 102 alert tested before and after enabling logging.
- Stock validation procedure raises error 50002 for insufficient stock.
- Alerts configured for errors 825, 9002 and severities 19-25.

## Results

Scheduled insertions, failure notifications, stock alerts and the severity-19 test were verified. The table and error-102 logging setting were restored, and the job resumed successfully.

**Tools:** SQL Server, SQL Server Agent, SSMS and Database Mail.
