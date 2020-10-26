# CodePathHw_Unit9

Exploit 1 - I performed session hijacking to verify this vulnerability. In one browser (firefox), I logged in normally but then copied the current PHPSESSIONID using a tool provided by Codepath. We then went to another browser (Chrome) which was NOT logged in and changed the PHPSESSIONID in this browser (using the same tool) to match the one we retrieved from the normally logged in browser. The result is that we were automatically logged into the system in the second browser without the need for a username or password.
