## XML to CSV Converter

Burp HTTP history is a feature in Burp Suite, a web security testing tool, that allows you to view and analyze HTTP traffic. The HTTP history displays a log of all HTTP requests and responses that have been sent or received by your browser, proxy, or other network-enabled applications.

To access the HTTP history in Burp Suite, follow these steps:

1. Open Burp Suite and navigate to the Proxy tab.
2. Ensure that Intercept is turned off by clicking on the button in the top right corner of the Proxy tab.
3. Click on the HTTP history tab to view a list of captured HTTP requests and responses.
The HTTP history provides various details about each request and response, including the URL, method, status code, headers, cookies, parameters, and payload. You can filter and search the HTTP history to find specific requests or responses, and you can modify or replay requests using the built-in tools in Burp Suite.

The HTTP history is a valuable tool for web application testing, as it allows you to examine the behavior of the application and identify potential security vulnerabilities or other issues. By analyzing the HTTP traffic, you can identify and exploit weaknesses such as authentication flaws, input validation errors, injection vulnerabilities, and more.

This is a simple Python script that can convert XML files of burp http history to CSV format. The script reads in an XML file, extracts the data, and writes it to a new CSV file.

Enjoy!
