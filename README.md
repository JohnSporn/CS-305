# CS-305
John Sporn
Journal Quesions

1. Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a financial consultinng company that develops individualized financial plans for savings, retirment, investments, and insurance for its patrons. The client wants to apply the most current and effective software security. Their clients data and financial information needs to be protected. They have asked to add secure commuication mechanism to their current software application. The data will need to be verified in the form of a checksum.

2. What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

When reviewing the software for this application I was able to identify that the software needed a hashing function to be implemented. This is essential to meet the requirments that Artemis Financial is looking for. Most of the vulnerabilities found just required an update to the latest version. It is important to code securely to insure a users informaton is kept safe and out of the wrong hands. Sensitive data always needs to be encrypted in the best way possible. Companies need to make sure they use best practices to maintain a good reputation in their software products.

3. What about the process of working through the vulnerability assessment did you find challenging or helpful?

Them most challenging thing to work through was figuring which vulnerabilities were false positives. I had to do a lot of self research to work through it. A couple of the vulnerabilities that were found were actually fixed elsewhere and just weren't recognized by the test.

4. How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

To increase security I made sure the application worked successfully on a secure server and the browser recognized it as secure. In the properties file I set the port to an https server which is the most secure server. To do this I had to generate a self signed SSL certificate and add it to the browsers trusted certificates. Anytime an application has sensitve data this needs to be implemented.

5. How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

To ensure the application was functional and secure I checked to make sure it ran properly in the browser. The application was proven to be secure by checking to make sure the browser recognized that the page was secure. The page is secure when there is lock next to the domain name and you can see that your certificate is labeled as vaild. After refactoring the code I ran another dependency check to check if any new vulnerabilites were introduced. There were not any new vulnerabilities.

6. What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

The maven dependency check tool was very helpful in this applciation to help find vulnerabilities and seems that it would be useful to use for every Java based web application. The ability to generate certificates are also always useful for an application like this. Learning how to implement the SHA-256 hashing algorithm is a good practice to know since most web applications need this type of protection for its data. Also, knowing how to verify it works by using a checksum is a good practice in this particular kind of case.

7. Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I would want to showcase to a future employer that I have the ability to implement secure functionalities to an application using the best encryption algorithm ciphers. Being able to verify that the cipher works properly is another demonstration of the skills learned in this assignment. Having the ability to run and comprehend a dependency check report as well as supress false positives and fix vulnerabilities that need to be fixed. I feel these are all good practices that future employers would like to see candidates have when being considered for a job as a developer.
