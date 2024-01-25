# Testing-Web-Applications-for-Vulnerabilities

In the Challenge assignment, I assumed the role of an application security engineer at Replicants, tasked with testing their new web applications for vulnerabilities. I successfully completed the assignment and provided mitigations for the identified vulnerabilities (in the accompanying PDF file).

**Web Application 1: Your Wish is My Command Injection**

I accessed the web lab and navigated to the Replicants website to test a web application for command injection vulnerabilities. After successfully exploiting the application using the dot-dot-slash method, I designed payloads to display the contents of /etc/passwd and /etc/hosts. I provided a screenshot confirming the successful exploit and outlined two to three recommended mitigation strategies in the M15 Challenge Submission File.

**Web Application 2: A Brute Force to Be Reckoned With**

I set up the activity by installing bWapp and accessing the Broken Auth - Insecure Login Forms page. Using Burp Suite Intruder, I performed a brute force attack on the administrator accounts with a list of breached passwords. A screenshot in the M15 Challenge Submission File confirmed the successful execution of the exploit. I also provided two to three sentences suggesting mitigation strategies for this vulnerability.

**Web Application 3: Where's the BeEF?**

I successfully set up the BeEF tool by accessing the control panel and navigating to the advanced version of the infected Butcher website. Using BeEF, I executed a social engineering phishing exploit to create a fake Google login pop-up, capturing user credentials. Additionally, I tested a stored XSS attack on the Replicants web application, injecting a BeEF hook. A screenshot in the M15 Challenge Submission File confirmed the successful exploit, and I detailed two to three mitigation strategies for this vulnerability.
