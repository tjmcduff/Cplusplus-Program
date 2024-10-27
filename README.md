# Cplusplus-Program

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
   Client Description: Artemis Financial is a fictional financial services company concerned with the security and integrity of its software systems, particularly as they handle sensitive financial data. Their requirements focused on enhancing software security and ensuring data confidentiality and integrity, especially in long-term data storage.

   Problem Addressed: Artemis Financial required an encryption solution for long-term archived files, a secure way to manage software dependencies, and a mechanism for regular vulnerability assessments. They also needed assurance that potential security issues in their dependencies and codebase were identified and mitigated proactively.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
   Success in Identifying Vulnerabilities: Through the use of tools like the OWASP dependency scanner, we were able to identify vulnerabilities in dependencies and configure a suppression file to handle false positives, ensuring that all findings were relevant and actionable.
   Secure coding is crucial because it helps prevent security breaches that could expose sensitive data, damage client trust, and result in financial and reputational loss. Coding securely aligns with industry standards and mitigates risks proactively, creating a reliable and trustworthy product.
   Strong security practices add value by safeguarding the company’s assets, maintaining regulatory compliance, and enhancing client trust. It allows for smoother operations, as robust security reduces the likelihood of disruptions from security incidents.

Which part of the vulnerability assessment was challenging or helpful to you?
   One of the key challenges was accurately identifying true vulnerabilities versus false positives in dependency scans. Fine-tuning the suppression file required careful judgment and knowledge of which flagged dependencies were genuinely at ris
   The process of configuring the suppression file and managing dependency scans provided valuable insight into balancing comprehensive security checks with efficiency, avoiding unnecessary alerts that could waste time or mask real issues.
   
How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
   Layers of security were added through encryption for long-term file storage, implementing dependency checks, and securing any self-signed certificates generated for test environments. These measures collectively reinforced both data at rest and dependencies, reducing the risk of exploitation.
   In the future, leveraging automated tools like static and dynamic analysis tools, along with manual code review, can provide a more comprehensive vulnerability assessment. Threat modeling and using real-time monitoring tools would also be effective for understanding the application's behavior in production.
   
How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
   After making code modifications, testing protocols were put in place, including running dependency scans and reviewing code coverage to ensure the functionality was intact and no new vulnerabilities were introduced.
   To check for new vulnerabilities, we re-ran dependency scans and conducted regression testing, ensuring that recent changes didn’t negatively impact the application’s security posture.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
  OWASP Dependency-Check: Essential for identifying and managing vulnerabilities in project dependencies.
  Java Keytool: For generating self-signed certificates, which was crucial for testing secure connections.
  Suppression File: To manage false positives effectively, ensuring relevant security issues are the focus.
  Refactoring and Testing Practices: Ensuring high code quality while maintaining security standards was a significant learning outcome.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  The ability to implement secure coding practices, such as using encryption for data protection and managing software dependencies effectively.
  Proficiency in security tools like the OWASP dependency scanner and the process of creating and configuring suppression files to handle false positives.
  Experience in balancing security and functionality by maintaining application functionality while enhancing security layers.
