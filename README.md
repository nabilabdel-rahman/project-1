# UOCIS322 - Project 1 #

Name: Nabil Abdel-Rahman

Contact: nabilabdel-rahman@outlook.com

This project creates a simple webpage server with "file checking" logic.
When ran locally, the server starts by loading a page of a cat figure.
The server can handle requests by loading files and pages that exist in DOCROOT, which is specified to be the folder named "pages" in the repo.
If a file doesn't exist, a 404 Not Found error code is transmitted and appears on the page.
If a request includes illegal characters, the response is a 403 Forbidden error which is transmitted and shown on the page.
The port number to which the socket is bound to is defined in credentials.ini and the DOCROOT is also specified in credentials.ini.
To change either of these, adjust lines 13 and 15 in credentials.ini.
To load the server, run the command make run in whichever Linux environment is used with the repo.
Make sure to use the command make stop to close the server when done using it.