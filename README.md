# oic-process-audit

Run the following java command to run the export utility.

Mac/Unix:
./run.sh -status completed -offset 0 -url oic-production.integration.ocp.oraclecloud.com -user user@oracle.com -password password

Windows:
.\run.bat -status completed -offset 0 -url oic-production.integration.ocp.oraclecloud.com -user user@oracle.com -password password

Options
-status: [completed|open]. Default: open
	completed: will generate a report with all completed process instances and related information.
	open: will generate a report with all open process instances and related information.

-offset: integer value. Default: 0 (beginning)
	This could be useful in the event you do not want to re-run the whole export from the beginning (useful for completed process instances).
