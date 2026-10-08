# Various Useful Security Resources

This page contains various resources for learning, or practicing security issues, as well as useful documentation on securing and tooling for performing security.

## Guides

- How to Design a Secure System
   - https://bytebytego.com/guides/how-do-we-design-a-secure-system/
- OWASP Security Testing guide
    - https://owasp.org/www-project-web-security-testing-guide/stable/
    - Top 10
        - https://top10.owasp.org/2025/
- SANS
    - https://www.sans.org/top25-software-errors
        - Top 25 weaknesses
- Threat modelling cheat sheet
    - https://cheatsheetseries.owasp.org/cheatsheets/Threat_Modeling_Cheat_Sheet.html
    - https://owasp.org/www-community/Threat_Modeling_Process 
- NIST
    - https://www.nist.gov/
- Securing applications with Helmet
    - https://www.geeksforgeeks.org/node-js-securing-apps-with-helmet-js/
- HTTP Headers
    - https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers
- HTTP Methods
    - https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Methods

## Checking for issues

- https://cwe.mitre.org/
    - Weakness database
- https://www.cve.org
    - Vulnerability database
- https://www.spinnakersupport.com/blog/2023/12/22/cve-vs-cwe/
    - Difference between CWE and CVE
- https://www.first.org/cvss/calculator/3.1
    - Common Vulnerability Scoring System Version 3.1 Calculator
    - https://www.first.org/cvss/calculator
        - Will take you to the latest version

## Threat analysis

- DREAD
    - https://medium.com/@Readsec/risk-assessment-using-the-dread-framework-a-case-study-on-cve-2025-21298-2dc8c852b473
- STRIDE
    - https://imgs.search.brave.com/W-VZ2mrNs-WUhP3tb-zXYmtpmFBKxvsaO3I76Yb-sYU/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9jZG4u/cHJvZC53ZWJzaXRl/LWZpbGVzLmNvbS82/M2JjODg1ZGQ2MGE4/ZTA3NjJlZWRiM2Iv/Njk4NjUxMThmYzUz/NzFlM2M2OWFlNjg5/XzY5ODY0NDk3Njc2/Y2QyODkxY2IxYzcy/YS0xNzcwNDA5MDY5/NTUwLmpwZw

## Tools

- GitHub Dependabot
    - https://docs.github.com/en/code-security/getting-started/dependabot-quickstart-guide
- Snyk
    - https://snyk.io/
    - https://securitysenses.com/videos/snyk-demo-20-minutes-2022
    - https://www.youtube.com/watch?v=m1gKcr4RCF4 (10 minutes)
- Miro Threat Modelling Template
    - https://miro.com/templates/threat-modeling-stride/
- Threat modeling AI tool
    - https://stridegpt.streamlit.app/
     - **Caution:** it requires your codebase, so you'll need to obsfucate or remove sections.
- Open Source Vulnerability scanners
    - https://owasp.org/www-community/Vulnerability_Scanning_Tools
    - https://owasp.org/www-project-defectdojo/


## Practice issue spotting/Hacking

The following have all been written to be deliberately flawwed.

- https://vwad.owasp.org/
    - OWASPs directory of legal broken and vulnerable applications for security testing and training
- https://owasp.org/www-project-juice-shop/
    - The most modern and sophisticated insecure web application for security trainings, awareness demos and CTFs.
    - https://juice-shop.github.io/
        - Documentation for it
- https://owasp.org/www-project-webgoat/
    - WebGoat is a deliberately insecure application that allows interested developers just like you to test vulnerabilities commonly found in Java-based applications that use common and popular open source components.
- https://github.com/rewanthtammana/Damn-Vulnerable-Bank
    - Damn Vulnerable Bank is designed to be an intentionally vulnerable android application.
- https://github.com/snyk-labs/nodejs-goof
    - A vulnerable Node.js demo application, based on the [Dreamers Lab tutorial](http://dreamerslab.com/blog/en/write-a-todo-list-with-express-and-mongodb/).
- https://github.com/stamparm/DSVW
    - Deliberately vulnerable web application written in under 100 lines of code, created for educational purposes. It supports majority of (most popular) web application vulnerabilities together with appropriate attacks.
- https://github.com/edu-secmachine/reactvulna
    - Deliberately vulnerable react application.
- https://github.com/OWASP/NodeGoat
    - Node.js project provides an environment to learn how OWASP Top 10 security risks apply to web applications developed using Node.js and how to effectively address them.
- https://owasp.org/projects/pygoat
    - PyGoat is an intentionally vulnerable web Application Security in Django. Our roadmap builds an intentionally vulnerable web Application in Django. Each vulnerability can be based on the OWASP Top Ten.