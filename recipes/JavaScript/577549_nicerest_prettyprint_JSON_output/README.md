###nicerest: pretty-print JSON output

Originally published: 2011-01-18 22:54:41
Last updated: 2011-01-18 22:59:12
Author: Trent Mick

Save this to "nicerest", `chmod +x`-it, and pipe your REST API `curl` calls through this for nicer output. It will notice HTTP headers (curl's `-i` option) and skips those before attempting to pretty-print the following JSON.