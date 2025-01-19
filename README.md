# Web_Application_Vulnerability_Scanner
Name: ROHITH ALLADA

Company: CODTECH IT SOLUTIONS

ID: CT08JPM

Domain: Cyber Security & Ethical Hacking

Duration: January 05 to February 05 2025

Mentor:

Overview of the Project :-
Project:- WEB APPLICATION VULNERABILITY SCANNER
Objective:
The objective of this project is to develop a Python-based web application vulnerability scanner that identifies common vulnerabilities such as SQL Injection and Cross-Site Scripting (XSS) in web applications. The tool automates the process of scanning web pages for potential security flaws in forms and inputs, providing a basic security check for developers and penetration testers.

Key Features:
1.Web Form Identification:

The tool identifies all form elements present on a given web page, making it easier to focus testing efforts on relevant sections of the site.

2.Form Parsing:

Extracts critical details such as action URLs, form methods (GET/POST), and input field names from web forms to understand the structure of the target application.

3.SQL Injection Testing:

Tests web forms for SQL Injection vulnerabilities by submitting a known malicious SQL payload (' OR '1'='1), which is a common vector for bypassing authentication and manipulating databases.

4.Cross-Site Scripting (XSS) Testing:

Tests for XSS vulnerabilities by submitting a script payload (<script>alert('XSS')</script>) and checking for its execution in the response, which could lead to malicious script execution in a user's browser.

5.Automated Form Submission:

Automatically submits forms with test payloads and analyzes the server's response to detect vulnerabilities.

6.Simple Reporting:

Provides real-time feedback on whether vulnerabilities like SQL Injection or XSS are detected, along with details of the affected form.

7.Support for Multiple Forms:

The tool can handle multiple forms on a single page, making it versatile for web applications with complex structures.

Technologies Used:
1.Requests Library:

Used for sending HTTP requests to web applications and interacting with web forms to test vulnerabilities.

2.BeautifulSoup (bs4):

Parses the HTML content of web pages and extracts forms and other elements for testing.

3.URL Parsing (urllib):

Used to construct full URLs from relative form action attributes, ensuring accurate form submission.

4.Python:

The primary programming language for developing the tool, utilizing various libraries for web scraping, form handling, and vulnerability testing.

Programming Language:
Python (Version 3.x)

Libraries:
1.requests:

For making HTTP requests and handling responses from the target web application.

2.BeautifulSoup (from bs4):

For parsing and extracting HTML elements, especially form tags, from the web page.

3.urllib.parse:

To join base URLs and relative paths from form actions for proper form submission.

How It Works
1.Forms Detection:

Extracts all forms from the target URL using BeautifulSoup.

2.SQL Injection Testing:

Tests each form by injecting an SQL payload (' OR '1'='1) into input fields.

Checks for SQL-related errors or unusual responses.

3.XSS Testing:

Injects an XSS payload (<script>alert('XSS')</script>) into input fields.

Checks for the payload in the server response.

4.Form Submission:

Automatically fills out form fields with the payloads and submits them via GET or POST methods.

Install beautifulsoup4 using pip:
pip install beautifulsoup4

Vulnerablity_Scanner_CodTech
![WhatsApp Image 2025-01-19 at 20 28 37_2f40778d](https://github.com/user-attachments/assets/398b51bf-0c72-49f5-ad12-049a6e84c162)
