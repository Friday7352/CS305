### README: Artemis Financial Practices for Secure Software Report

#### Who Was the Client and What Did They Need?
Artemis Financial is a consulting company that helps clients with financial planning, like retirement, savings, and investments. They wanted to improve their software to make communication secure and protect client data. This included adding file verification through checksums and enabling HTTPS communication.

#### What Was Done Well?
I found and fixed security issues in their software effectively. By using the SHA-256 algorithm, I created secure checksums to ensure data wasn’t altered. I also set up HTTPS communication with SSL certificates to protect data during transfers. Secure coding is important because it prevents hacking, protects sensitive information, and builds trust with clients.

#### What Was Challenging or Helpful?
One challenge was handling false positives during dependency testing. Using suppression files helped manage these alerts. This process taught me how to analyze results carefully and use tools effectively to improve security.

#### How Were Security Layers Added?
I added layers of security by implementing checksums to verify data integrity and enabling HTTPS for secure communication. In the future, I’d use tools like OWASP Dependency-Check and dynamic analysis tools to find vulnerabilities and prioritize fixes based on risk.

#### How Was Functionality and Security Tested?
After updating the code, I tested it to make sure everything worked correctly. Functional testing checked features like checksum generation and HTTPS endpoints. I also used the dependency-check tool to confirm no new vulnerabilities were introduced.

#### What Resources and Tools Were Helpful?
The following tools and practices were very helpful:
- **Java Keytool:** To create and manage SSL certificates.
- **SHA-256 Algorithm:** For creating secure checksums.
- **OWASP Dependency-Check:** To analyze and fix dependency issues.
- **Spring Boot Framework:** To simplify adding security features to the application.
These tools will be useful in future projects.

#### What Can Be Shared With Employers?
This project shows my ability to identify security issues, fix them, and ensure the software works securely. I could share the Practices for Secure Software Report or the code for checksum generation and HTTPS communication as examples of my skills in secure software development.

