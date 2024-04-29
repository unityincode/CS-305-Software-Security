# CS-305-Software-Security
This repository includes Report for Secure Software Practices for client Artemis Financial.

#README
Artemis Financial is a financial services client that required a secure application capable of handling sensitive financial data. They needed assurance that their software system was not only functionally robust but also secure from potential cyber threats. The primary issues they wanted to address were the security vulnerabilities within their existing ssl-server application, which could potentially compromise client data and trust.

Upon assessing Artemis Financial's software, I meticulously identified and rectified security vulnerabilities. One of my strengths was the effective integration of encryption and hashing techniques to safeguard data integrity and confidentiality. The value of software security to a company like Artemis Financial is immeasurable; it ensures the protection of sensitive financial data, maintains customer trust, ensures compliance with regulatory standards, and safeguards the company’s reputation.

The most challenging aspect of the vulnerability assessment was ensuring that the dependencies were current and free from known vulnerabilities, which required careful review of the OWASP Dependency-Check reports. This was also a helpful exercise as it gave me insight into the importance of keeping dependencies updated as part of an ongoing security strategy.

To increase the layers of security, I enforced HTTPS for secure communications, applied AES encryption for sensitive data, and used SHA-256 for data integrity verification. For future assessments, I would continue to use tools like OWASP Dependency-Check and incorporate automated security testing into the CI/CD pipeline to identify vulnerabilities early.

To ensure the code and application's functionality and security, I conducted both automated and manual testing. After refactoring, I reran the OWASP dependency check to ensure no new vulnerabilities were introduced. It's crucial to have a combination of both static and dynamic testing methods to cover the range of potential vulnerabilities.

Throughout this assignment, I relied on the Eclipse IDE for development, the Maven build system for dependency management, and OWASP tools for security testing. Secure coding practices, like input validation, proper error handling, and the principle of least privilege, were pivotal in this process. These tools and practices are invaluable for future assignments and any professional software development task.

For future employers, I can present a detailed report of the vulnerability assessment and the steps taken to secure the application for Artemis Financial, showcasing my methodical approach to software security and my ability to address complex security challenges. This includes documentation of the refactoring process, the use of encryption and secure communication protocols, and the application of industry-standard security practices, demonstrating a clear understanding of secure software development lifecycle.

-Thanks for reading!
