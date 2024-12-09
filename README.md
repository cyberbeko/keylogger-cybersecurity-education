# keylogger-cybersecurity-education
A Python-based keylogger built in a virtual environment for ethical hacking and cybersecurity education.

<h1>Keylogger-Education🧑🏻‍💻</h1>

 ### [YouTube Demonstration](https://youtu.be/4kLb7yub7fU)

<h2>Description</h2>
The main goal of this project is to provide a basic Web Application Firewall (WAF) using Flask to help block common attacks such as SQL Injection and Cross-Site Scripting (XSS). This simple WAF serves as an introductory example for developers who want to understand how WAFs function and how they can be implemented in a web application. The project demonstrates how to inspect HTTP requests for malicious patterns and return a 403 Forbidden response when suspicious activity is detected.

## Programming Language💻
- **Python** (The primary language used for this project.The WAF is built using Flask, which is a web framework for Python.)

## Utilities Used 💼
- **flask**: A lightweight web framework for Python, used to build the web application and the Web Application Firewall (WAF). Used for routing, handling HTTP requests, and building a simple web application.

- **Flask Middleware**: The custom middleware built into the Flask app to intercept and filter incoming HTTP requests (both GET and POST), blocking patterns associated with SQL Injection and XSS attacks.

- **Python Standard Libraries**:
jsonify: A Flask utility to return JSON responses, which is used to send the "Blocked by WAF" message.
request: A Flask object used to access incoming HTTP request data (query strings, body data).

<h2>Environments Used </h2>

- <b>**macOS**</b>

<h2>Program walk-through🦺</h2>

<p align="center">
Created waf_project folder <br/>
<img src="https://i.imgur.com/CMwnZVB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created a Python file named Berkays_WAF.py  <br/>
<img src="https://i.imgur.com/FfuXL2L.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Write the Flask WAF Code <br/>
<img src="https://i.imgur.com/iOHMmwR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Save and Exit
To save the file in nano and exit.
<br />
<br />
Install Flask and Run the Flask App:  <br/>
<img src="https://i.imgur.com/m9kHRQS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now we are ready to check!  <br/>
<img src="https://i.imgur.com/ofz9zdQ.png?1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Let's test the SQL Injection, try visiting this URL in browser:
<br/>
<img src="https://i.imgur.com/JtR0rpO.png?1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> As you see, The WAF should detect the malicious pattern.
<br /> Return a 403 Forbidden response with the following message.
<br /> Also, when I try with Cross-Site Scripting(XSS) it will say blocked by WAF <br/>
<br />
<br />
  
# CyberBeko WAF (Web Application Firewall)

## Summary

1. **Step 1:** Create a new folder and Python file (`Berkays_WAF.py`).
2. **Step 2:** Paste the WAF code to inspect query strings and POST data for SQL Injection and XSS patterns.
3. **Step 3:** Install Flask using `pip3 install flask`.
4. **Step 4:** Run the Flask app using `python3 Berkays_WAF.py`.
5. **Step 5:** Test the WAF by visiting your local server and attempting SQL Injection or XSS.

## Purpose:
To demonstrate the basic concepts of a Web Application Firewall (WAF) using Flask, specifically to prevent SQL Injection and XSS attacks.

## Goal:
1. **Educational Tool:** Teach developers about WAFs and basic web security.  
2. **Security Awareness:** Raise awareness about the importance of web application security.  
3. **Foundation for Growth:** Provide a starting point for more advanced security features.  
4. **Promote Best Practices:** Encourage basic security practices and proper web app protection.

## Disclaimer

### Important Note:

- This project is intended for **educational purposes only** and should not be used in **production environments**. It is a simple example to demonstrate the basic concepts of a Web Application Firewall.
  
- For real-world applications, it is crucial to use a more **robust and production-ready WAF solution**, such as **ModSecurity** or other advanced security tools.
  
- This basic WAF does not cover all possible attack vectors and should not be relied upon for securing sensitive or high-traffic applications.
  
- Always consider **additional layers of security**, such as input validation, content security policies (CSP), HTTPS, and other security best practices when developing web applications.
  
- In **production environments**, be sure to use a proper **WSGI server** like **Gunicorn** or **uWSGI** to run Flask apps securely and efficiently.


</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
