## Reflection – Artemis Financial Secure Software Project

Artemis Financial is a consulting company that needed to strengthen the security of its software systems. Their main requirement was to ensure secure communications, protect sensitive financial data, and follow industry best practices for encryption and code security. The issue I addressed was refactoring their application to use modern encryption, certificates, and secure communication protocols.  

I did well in identifying vulnerabilities and applying secure coding practices such as AES‑256 encryption, SHA‑256 hashing, and enforcing HTTPS with TLS. Coding securely is critical because it protects client data, prevents breaches, and builds trust in the company’s services. Security adds long‑term value by reducing risk and supporting compliance with industry standards.  

One of the more challenging but helpful parts of the project was certificate generation and configuring the Spring Boot application for HTTPS. This gave me hands‑on experience with keystores, certificates, and secure endpoints. To increase layers of security, I also ran OWASP Dependency‑Check to confirm no new vulnerabilities were introduced. In the future, I would continue using static analysis tools, penetration testing, and dependency checkers to assess risks and choose mitigation strategies.  

To ensure the application was both functional and secure, I tested the checksum endpoint with valid and invalid inputs, verified HTTPS redirection, and confirmed the application executed without errors. After refactoring, I re‑ran vulnerability scans to make sure no new issues were introduced.  

The tools and practices I used—such as Java’s built‑in cryptographic libraries, OWASP Dependency‑Check, and secure coding principles—will be valuable in future projects. For employers, this project demonstrates my ability to conduct a vulnerability assessment, apply secure coding practices, and deliver a professional report that balances functionality with security.
