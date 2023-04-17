# CS-305-Security

### Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial, a consulting company that develops customized financial plans, has requested us to examine their web-based software application to identify any potential vulnerabilities that could be exploited by external threats. The aim of this report is to present the findings of our vulnerability assessment of the Artemis Financial software application and to make recommendations for mitigating the security vulnerabilities that we have identified.

### What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

When I found the client's vulnerabilities, I identified each perspective of why and how they could be manipulated, to emphasize the necessity of adjusting the code, and to properly and thoroughly inform them of the possibilities present. It is essential to code securely because software vulnerabilities can be exploited by attackers to cause significant harm to individuals, organizations, and even society as a whole. By adopting secure coding practices, developers can help prevent data breaches, cyber attacks, and other security incidents.

Software security adds significant value to a company's overall well-being by protecting its assets, reputation, and customer trust. A company with strong security is  minimizing the risk of financial losses, legal liabilities, and other reputational damages that can arise from a security breach. It can also help establish the trust of the company to its customers, partners, and stakeholders. Investing in software security should be a top priority for any organization that values its assets and reputation.

### What part of the vulnerability assessment was challenging or helpful to you?

The most challenging part of the report was compiling all of the static testing vulnerabilities and going through them, as there are many of them with obscure and complex attack vectors. While the list was painfully exhaustive, it gave a very thorough look into all of the known vulnerabilites that have been collected and identified over the years. This helped a lot with recommending a defense strategy, because after a high-level look, the high-detail examination made for a fuller and more complete picture of the reality.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

The mitigation plan I decided to go with included the general best practices such as updating all packages to the latest version, continuing to keep them up to date, and always implementing their system code in the most secure ways possible. This includes input validation/sanitization, using secure libraries, and separating each component into its own capsule to lower the risk of outside manipulation.

Other techniques recommended included monitoring system logs, using multiple or secure layers of authentication, security testing, and employee education on security best practices. All of these extra layers will heavily mitigate any vulnerabilities, but will not completely erase the possibility of a breach. In the future, I would assess vulnerabilities in a similar way, and adapt mitigation techniques to the industry, business, and situation that is at hand, because every organization has its own needs and circumstances.

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

This was a vulnerability assessment, meaning that if anything I identified areas that the code was not functional and secure. However, I did make recommendations to ensure the intended functionality and security of the code, which included input validation, APIs, cryptography, and encapsulation. These along with others would create a structure that would keep the flow of information between each component as limited as is required, keeping room for new vulnerabilities at a minimum.

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

In this assessment, I used the maven dependency check tool to identify known vulnerabilities in the project dependencies. These were used to guide the mitigation plan by identifying the types of attacks the software is vulnerable to. Static testing tools are a great way to identify vulnerabilities in a project outside of secure coding or program design errors, and will be of great use in the future.

### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

This assignment in particular demonstrates high-level analytical skill of codebases from various angles such as code quality, static testing, and secure coding practices in general. The descriptive manual review process identifies this analysis most accurately, showing a deeper look at each individual Java file.
