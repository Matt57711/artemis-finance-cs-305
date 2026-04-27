# artemis-finance-cs-305
​Artemis Financial Security Portfolio
​Project Summary
​Artemis Financial is a financial consulting firm that required a security upgrade for their software to protect sensitive financial data. The company's primary requirement was to ensure their web applications were resilient against modern security threats while maintaining data integrity through robust encryption and secure coding practices. I was tasked with conducting a vulnerability assessment and refactoring their code to implement industry-standard security measures.
​Security Reflections
​Vulnerability Assessment & Secure Coding
​When identifying software security vulnerabilities, I focused on a comprehensive manual code review and dependency analysis. It is vital to code securely because, in the financial sector, a single vulnerability can lead to catastrophic data breaches and loss of client trust. Secure software adds value to a company's overall well-being by protecting its reputation, ensuring regulatory compliance, and minimizing the financial risk associated with cyberattacks.
​Challenges and Insights
​The most challenging part of the vulnerability assessment was identifying subtle logic flaws that automated tools often miss. However, the process was incredibly helpful in teaching me how to think like an attacker to better defend the system. It highlighted the importance of not just fixing bugs, but understanding the underlying architectural weaknesses.
​Layers of Security
​To increase security, I implemented layers of protection such as AES-256 encryption for long-term data archiving, which protects against brute-force and emerging quantum threats. In the future, I plan to use tools like static and dynamic analysis (SAST/DAST) and industry frameworks (such as OWASP) to continuously assess vulnerabilities and decide on the best mitigation techniques.
​Functional & Secure Verification
​I ensured the code was both functional and secure by utilizing JUnit testing for regression and Maven for dependency management. After refactoring the code, I performed a secondary manual review and ran dependency checks to confirm that no new vulnerabilities were introduced and that the core application logic remained intact.
​Tools and Practices
​During this project, I used several key resources and practices:
​AES-256 Encryption: For high-level data protection.
​Dependency Checking: To identify and patch vulnerable libraries.
​Manual Code Review: To find logic flaws and ensure best practices.
​Secure Refactoring: Cleaning up "code smells" that could lead to exploits.
​Future Employer Takeaways
​This assignment demonstrates my ability to bridge the gap between functional software development and cybersecurity. It shows future employers that I am capable of performing formal vulnerability assessments, applying cryptographic standards, and delivering code that is not only operational but resilient against modern threats.