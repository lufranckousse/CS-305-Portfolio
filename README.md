# CS-305-Portfolio Reflection


## Artemis Financial Client and Software Requirements

Artemis Financial is a consulting company that develops individualized financial plans for its customers. The company wanted to modernize its software application while improving the security of customer financial data being transmitted over the internet. My task was to identify security vulnerabilities within the application and implement security enhancements to protect sensitive information. Specifically, I added a SHA-256 checksum verification process, implemented HTTPS communication using SSL certificates, generated a self-signed certificate with Java Keytool, and performed testing to verify that the application remained secure and functional.

## Finding Vulnerabilities and the Importance of Secure Coding

One area where I performed well was identifying vulnerabilities related to data transmission and authentication. The original application lacked secure communication protocols and did not verify the integrity of transmitted data. By implementing HTTPS and adding SHA-256 checksum verification, I improved the application's ability to protect sensitive financial information from tampering and interception.

Secure coding is important because it helps protect confidential data, prevents unauthorized access, and reduces the risk of cyberattacks. Organizations that implement secure coding practices can avoid costly data breaches, maintain customer trust, and comply with security standards and regulations.

## Challenging and Helpful Aspects of the Vulnerability Assessment

The most challenging aspect of the vulnerability assessment was understanding how multiple security layers work together to protect an application. Learning how encryption, certificates, hashing algorithms, and secure communication protocols interact required careful research and testing. However, this was also one of the most valuable parts of the project because it demonstrated how software security extends beyond writing functional code.

## Increasing Layers of Security

I increased the application's security by implementing several layers of protection. First, I used the SHA-256 cryptographic hashing algorithm to create checksum values that verify data integrity. Second, I generated and configured a self-signed SSL certificate to enable HTTPS communication. Third, I updated the application's configuration files to enforce secure communication over port 8443. Finally, I reviewed the code and conducted testing to verify that the application functioned properly after the security enhancements were implemented.

In future projects, I would continue using static analysis tools, dependency checking tools, code reviews, penetration testing techniques, and vulnerability assessment frameworks to identify security risks and determine the most appropriate mitigation strategies.

## Ensuring Functionality and Security

To ensure that the application remained functional after refactoring, I compiled and executed the project within Eclipse and verified that it launched successfully. I tested the HTTPS endpoint through a web browser and confirmed that the checksum verification page displayed correctly. I also reviewed the application code for logical and syntactical errors and used dependency analysis tools to identify potential vulnerabilities in project dependencies.

## Resources, Tools, and Practices Used

Throughout this project, I used Eclipse IDE, Java Keytool, Spring Boot, Maven, OWASP Dependency Check, SHA-256 cryptographic hashing, SSL/TLS certificates, and static code review practices. These tools helped me understand industry-standard security practices and gave me hands-on experience implementing real-world security solutions.

## Demonstrating Skills to Future Employers

This project demonstrates my ability to analyze software vulnerabilities, implement secure coding practices, configure SSL certificates, work with cryptographic hashing algorithms, and validate software functionality through testing. It also shows my understanding of software security principles, risk mitigation, secure communications, and application deployment. These are important skills for software engineering, cybersecurity, cloud computing, and DevSecOps roles.
