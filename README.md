# Penetration-Testing-Project-Using-Burp-Suite
Project Overview
This project involved utilizing Burp Suite, a widely recognized web application security testing tool, to demonstrate how HTTP requests can be intercepted and manipulated to gain unauthorized access to a website. 

Business Understanding
In the realm of cybersecurity, understanding how attackers exploit vulnerabilities is essential for developing robust security measures. This project aimed to highlight the importance of secure web application development by demonstrating the potential risks associated with improper handling of HTTP requests. By gaining hands-on experience with Burp Suite, the project emphasized the need for organizations to regularly test their web applications for vulnerabilities and adopt proactive security measures to safeguard against unauthorized access.

Tools and Frameworks

    Burp Suite: A comprehensive web application security testing suite used for intercepting, modifying, and analyzing HTTP/S traffic between a client and  server.
    Web Browser: Used for navigating the educational site and interacting with its features.
    Hack Yourself First: An intentionally vulnerable website allowing users to practice penetration testing techniques safely.


Project Description
I navigated to the Hack Yourself First website (http://hack-yourself-first.com/) and created an account using my first name and randomly generated details. This step was crucial as the site is designed to be purposely vulnerable for educational purposes.

Steps Taken:

    Account Creation:

    Successfully created a user account and navigated to my account profile.
    Captured a screenshot of the website in "Normal Operation," showing the header and navigation menu, which included links like "Leaderboard" and "My Account."

Screenshots 1a & 1b

    Burp Suite Setup:

    Launched Burp Suite and ensured that the HTTP Intercept mode was activated.
    Captured  a screenshot displaying Burp Suite in intercept mode.

Screenshot 2

    Browser Configuration:

    Configured my web browser’s proxy settings to direct traffic through Burp Suite’s proxy listener.
    Documented  the browser settings with a screenshot confirming that the proxy was enabled and correctly configured.

Screenshot 3

    Profile Modification:

    Made a modification to my profile by changing my name and submitting the changes.
    Captured the intercepted HTTP request in Burp Suite, showing the modification  before it was sent to the server.

Screenshot 4

    Request Manipulation:

    Altered the intercepted request to escalate my privileges to an administrator level.
    Captured a screenshot of the modified request within Burp Suite.

Screenshot 5

    Demonstrating Abnormal Operation:

    Finally, I navigated back to the Hack Yourself First website and refreshed the page, revealing the previously unavailable Admin menu.
    A screenshot was taken, illustrating the "Abnormal Operation," displaying the new administrative options accessible due to the manipulated request.

Screenshot 6a-6c

Conclusion
This project effectively demonstrated the power and utility of Burp Suite in intercepting and modifying HTTP requests. Through practical engagement with the tool, I gained insights into the mechanics of web application vulnerabilities and the importance of secure coding practices. The exercise highlighted how easily an attacker could exploit improper validation and authorization measures if security is not diligently maintained. The knowledge and skills acquired during this project will inform future security assessments and vulnerability management practices, underscoring the necessity of continuous security training and proactive testing in web application development.
