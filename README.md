# userAuthentication
Authentication and authorization are key pieces to securing any web application that works with user data. Verifying who your users are and what they’re allowed to do will help create a safe and secure user experience.  If users lose access to their accounts or find that their data has been altered, this could result in losing users! Or, if a malicious actor gains access to an admin account, this could give them access to data like passwords or email addresses which can be used in clickjacking attacks.

Cyberattacks can results in:
- Website defacement
- Loss of website availability or in the worst case, total DoS.
- Leaking of sensitive customer data 
- An attacker gaining control over the website
- An attacker using the website as a vector for other attacks
- Loss of user trust in the website 
- Reputational damage. 


Vulnerabilities exist in all corners. In order for web applications to function, there are many parts that work with each other: the user’s browser, the HTML/CSS/JavaScript code including any third-party API’s, the HTTP(S) protocol, and so on. This means there are many points of attack.

Penetration testing, or pen testing, is a growing practice where a cyberattack is simulated in order to identify security vulnerabilities so that they can be discovered and remediated.

Security Principles
= 
CIA (Confidentiality, Integrity, Availability)

- Confidentiality refers to protecting private information from eyes that shouldn’t have access to it. It’s the need to enforce access - who can see this, and who shouldn’t? 
-  Integrity refers to data integrity here. We need security controls that protect data from being changed or deleted, and that the damage can be reversed if done accidentally. Some techniques related to integrity are database security, keeping backups and using cryptography to check for changes.
-  Availability refers to data being consistently, reliably available to those authorized. For example, social media websites ensure that even with high traffic or when a server is compromised, information gets to a user’s screen. This is accomplished through constant maintenance of hardware and software, monitoring servers and networks, and having a plan for any disasters.
