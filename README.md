When I first started working on Artemis Financials' secure software practices, I wanted to better understand how to combine software development with real-world cybersecurity principles. Through this project, I learned how to apply encryption algorithms, certificates, and vulnerability scanning tools to protect data and communication within a Java-based Spring Boot application. The client’s goal was to make sure all transmitted and stored data was secure while maintaining usability and compliance with modern standards. 

  

One of the things I did well was implement layered security—starting with checksum generation using SHA-256, then enabling HTTPS/TLS with a self-signed certificate and finally integrating OWASP Dependency-Check for static analysis. These steps not only reduced vulnerabilities but also demonstrated my ability to plan and test secure configurations end-to-end. Secure coding matters because it prevents common exploits like data leaks, injection attacks, and man-in-the-middle interceptions. I also found that documenting my process clearly helped ensure transparency and traceability, which are key parts of security audits. 

  

The most challenging aspect was analyzing the dependency-check report and determining which vulnerabilities were true risks versus false positives. It was helpful to review CVE entries, understand their severity, and propose mitigation plans such as upgrading libraries or adding justified suppressions. This exercise improved my understanding of how real organizations manage risk and compliance while keeping systems functional. 

  

After refactoring and configuring the secure communication settings, I verified that the application ran cleanly on HTTPS port 8443 without introducing current issues. I re-ran the vulnerability scan to confirm that no additional risks appeared and validated that the checksum endpoint still functioned properly. This step reinforced the importance of retesting after every security-related change. 

  

The tools and practices from this project—keytool for certificate management, OWASP Dependency-Check, TLS configuration, and secure algorithm selection—are all methods I plan to reuse in future work. I would also continue applying least-privilege principles, version management, and regular static code analysis. 

  

If I were to show this work to a potential employer, I would highlight both the Project Two report and my completed code base. Together, they show my ability to analyze, implement, and verify secure development practices while producing professional documentation that aligns with industry standards. This project gave me confidence in applying practical cybersecurity measures within a software engineering context. 
