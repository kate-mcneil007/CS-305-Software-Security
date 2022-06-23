# CS-305-Software-Security

•	Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial Financial is a financial consulting company, this means they create plans for peoples “savings, retirement, investments, and insurance” (“Project one guidelines and rubric”, n.d.). By nature, the company handles a lot of sensitive information. This includes how much clients make a year, what investments they are making, how much they have in retirement, etc. This is information that should not be known to anyone except the client and those they are working with. Therefore, secure communications are of the utmost importance.

•	What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I felt I did a good job of finding software vulnerabilities such as incorrect variable types, and variables without a length min/max. Both of these could allow users to input code not expected by the program and breaking it. I was also able to find many plugins that were out of date creating security vulnerabilities.  

•	What about the process of working through the vulnerability assessment did you find challenging or helpful?
I found it challenging to determine false positives in the vulnerability assessment. While reading the OWASP documentation they briefly discuss false positives. They say, “if the CPE value is wrong, this is usually obvious” (“How to read the report”, 2022). This was my first-time using CPE’s so this was not very helpful. 

•	How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
The first thing I suggested was better defining variables. By making them the correct type as well as creating a minimum and maximum length the program will be less likely to take in unexpected code. Updating all the plug ins was also an important step as many of them had vulnerabilities that were solved through updates. Another layer of security was encryption. By adding encryption sensitive data would be more secure. In the future I would use OWASP again as it was very helpful in finding vulnerabilities. 

•	How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
I ensured my software application was functional through running the program. This allowed me to see what it output. When the application was not functional I would study what it output to see what errors were occurring so I could then fix them. I ensured my code was secure by using both encryption and a certificate. I checked to see if I introduced new vulnerabilities by running the OWASP dependency check both before refactoring code and after. 

•	What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
I really enjoyed using the OWASP dependency check, I will be using this in the future. As always, I found the documentation of the language I was using immensely helpful. I always enjoy using the official documentation of whatever language I am using as it shows how to properly implement various functionalities included in the language’s libraries. I will continue using resources like this in the future as well. 

•	Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
I would like to show a future employer my ability to encrypt data as well as properly implement functionality. I would also like to show my ability to generate and use certificates, as well as properly refactor code while assessing any potential vulnerabilities that may arise. 
