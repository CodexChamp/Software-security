# Software-security
This is the product of 8 weeks of studying CS 305 software Security
QUESTIONS:
Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
Which part of the vulnerability assessment was challenging or helpful to you?
How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
ANSWERS:
Artemis Financial, a consulting firm specializing in individualized financial plans like savings, retirement, investments, and insurance, was the client. They wanted me to modernize their operations by addressing software security vulnerabilities, ensuring that their sensitive client data was well-protected.

When addressing Artemis Financial’s security vulnerabilities, I focused on refactoring the code to improve server/client security and enhance encryption methods. By applying industry best practices, I introduced layers of security that significantly improved the application's resilience against threats, like using 512-bit encryption and enforcing HTTPS for secure communication. It's crucial to code securely because it safeguards sensitive data, prevents breaches, and fosters trust with clients. The value of secure coding extends to the overall well-being of a company by mitigating risks and ensuring long-term operational stability.

A challenge I faced during the vulnerability assessment was getting the SSL certificate trusted by the server. However, refining the checksum process to improve tamper detection was very helpful and became a key part of my work. I also integrated dependency checks and encryption algorithms to further protect the software.

To increase layers of security, I implemented SSL certificates and reinforced encryption practices. In the future, I would use tools like OWASP Dependency Check to assess vulnerabilities and determine appropriate mitigation techniques based on risk levels and potential impact.

After refactoring the code, I ensured its functionality and security by running comprehensive tests and using tools to detect any new vulnerabilities. Regular testing was key to maintaining the integrity of the code and confirming that no new issues were introduced.

Some of the resources and tools I used, like the OWASP Dependency Check and SHA-512 for encryption, are valuable for future tasks. They provide an effective way to secure applications and mitigate vulnerabilities. I’d also focus on continuous monitoring and regular security audits moving forward.

In future interviews, I could showcase this assignment to demonstrate my experience with refactoring code to meet security standards, improving server/client security, and integrating encryption practices. This project reflects my ability to analyze security vulnerabilities, implement industry-standard solutions, and ensure that sensitive data is protected.
