# NessusImport

Imports Nessus results from Nessus server, while waiting for scan.
Imported results will be saved in excel file, sorted by severity.

Note, API keys are needed:

YOUR_API_ACCESS_KEY is access key
YOUR_API_SECRET is secret key

Both must be generated on Nessus server.

Also variables must be changed:

NESSUS_SERVER_ADDRESS IP address of Nessus server (remember to add portnumber if not running on port 443)


Files will be created with names:
report_id.csv a CSV file from scan with report_id
report_id.xlsx a excel file from scan with report_id
