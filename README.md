# Artemis-Financial-Secure-Software-Report

**_Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?_**

Artemis Financial is a financial consulting company that develops individualized plans for savings, retirement, investments, and insurance for their clients. They wanted to modernize their operations through custom software. This custom software requires the most current and effective software security to be implemented since they are handling confidential information. 

**_What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?_**

I think I was able to locate a lot of the vulnerabilities in the software itself. Most of the vulnerabilities stem from outdated plugins that need to be updated to currently released versions. It's important to code securely because it protects both the company and the users from third parties who would try to maliciously attack them to gain information. Software security adds to the company's well-being because it protects the company from attacks that could potentially affect users or the company's systems as a whole. Should either of those happen, it can be very damaging to the company in money or clients lost. It also put off new clients from seeking their services. So, in order to keep the company successful, it's crucial they are always practicing secure coding in all their software.

**_What about the process of working through the vulnerability assessment did you find challenging or helpful?_**

I found the manual review to be rather difficult just because I haven't worked much with Java and wasn't entirely certain what would be considered a vulnerability in the physical code. I also was a little lost on false positives at first and definitely could have limited the list of vulnerabilities that popped up in the dependency report. I did find it helpful to go through the Vulnerability Assessment Process Flow Diagram and identify which areas need to be looked at. It helped give me an idea of what would need to be looked at for what this company wants to do.

**_How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?_**

I approached the need for increased layers of security by first creating a self-signed certificate that allowed the browser to securely connect to the program via HTTPS. Next, I added the hashing function to the code base in order to protect data. Lastly, running static tests to find any known vulnerabilities with plugins or that I didn't introduce new vulnerabilities to the program. I think running dependency reports is something I would do in the future because it helps in identifying holes in the software that someone could abuse. I also think making sure to pay attention to secure coding along the way and keeping security in mind at all times is just as crucial. 

**_How did you ensure the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?_**

I was able to ensure the code and software were functional by testing it through my browser to see if it created a secure connection. I ended up doing a second round of static testing to make sure there weren't any new vulnerabilities introduced in the dependency report.

**_What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?_**

I think the dependency check tool was extremely helpful in finding issues within the program. This was also the first time I worked with certificates which I found to be really helpful in testing the code to make sure it was secure. 

**_Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?_**

I would definitely want to showcase the Practices for Secure Software Report. I think this really showed that I understand and can recommend the best algorithm ciphers to protect data and how I went about doing it in this instance. I can show that I was able to enable a hashing algorithm that successfully connected securely from the browser to the software.
