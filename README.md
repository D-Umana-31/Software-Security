# CS305 Project One 

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial, a consulting company specializing in individualized financial plans for customers. The company needed to enhance the security of its software application to protect sensitive financial data, maintain customer trust, and comply with regulatory requirements. The identified threats included phishing attacks, ransomware, malware, API security risks, and vulnerabilities in open-source components.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

For this assignment I conducted both manual reviews and statict testing to find weaknesses in the  code. I was able to find vulnerabilites in lack of input validaiton, absence of authentication, weak error handling, and no data encryption. It is important to code securely becuse, secure coding prevents data breaches, protects customer information, and ensures regulatory compliance. Strong security measures improve customer trust and prevent financial losses due to cyber threats.

Which part of the vulnerability assessment was challenging or helpful to you?

The challenge I had to overcome was identifying all dependenceines and understanding how different vulnerabilites can be exploited. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

To improve security, I updated outdate depedencides to eliminate know vulnerabilites, I implemented input validaiotn and sanitization to prevent SQL injecting, I added authentication mechanisms for API endponts, and I enchanced encryption protocols to protect sensitive data. In the future, I could use automated security scanning tools to continuously assess vulnerabilities and select mitigation techniques.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

After refactoring the code, I tested for functinoality to ocnfirm that fixes did not break the system and I tested for security to verify that new vulnerabilites were not introduced. I used both static analyisis tools and manual review to ensure a comprehensive approach. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Some resources and tools that might be helpful in future assignment include dependency check tools for identifying security flaws in third-party libraries, code review and static analysis tools for detecting security weaknesses, and secure coding practices, such as using parameterized queries and enforcing strong authentication..

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I will be able to show future employeres my vulnerability assessment report, showing expertise in identifying and mitigating security risks, before-and-after comparisons of security vulnerabilities and their resolution, and my ability to apply industry security standards.
