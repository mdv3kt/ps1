Title: Problem Set 1 Answers
Author: Mark Valeiras

1.	User-Agent: Mozilla/5.0 (X11; Linux i686) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/32.0.1700.77 Safari/537.36
	The first part, Mozilla/5.0 indicates that the user agent is Mozilla based or compatible with Mozilla. 5.0 indicates the version of Mozilla. The next segment is representative of the operating system used. X11 reffers the the windowing system employed byut the OS which is Linux run on an i686 processor. The AppleWebKit/537.36 refers to the display manager type and version. "KHTML" refers to the HTML formatting that will be employed by the web kit. Finally, Chrome/32.0.1700.77 refers to the browser name and version followed by Safari/537.36 which is the name and version of the browser that chrome is built from.

2.	The error reported when using a mutable static global variable as a counter is a result of a concurrency issue. Since a web server is a multithread program, multiple requests made simultaneously to the server could result in multiple attempts to accesse the counter variable at the same time leading to potentially inconsistent and inaccurate values. 