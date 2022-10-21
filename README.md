# Software Security CS305

For this project I will be working as a developer for a software engineering company, Global Rain, that specializes in custom software design and development. The software is for entrepreneuurs, buisnesses, and government agencies around the world. At Global Rain, I will be working with a client, Artemis Financial, a consulting company that develops individualzed financial plans for their customers. These plans includes savings, retirement, investments, and insurance. 

My job will be to protect Global Rain's client data and finacial information. I will be adding a file verification step to their web application to ensure secure communications. I will be examining Atemis Financial's software to address any security vulnerabilities. 

I will also recommend an appropriate encryption algorithm cipher to deploy, given the security vulnerabilities, and justify my reasoning behind it.  

The algirthm cipher I reccomended is the SHA-256 since it avoids collisions and keeps everything secure against attackers and it is the most secure cipher. 

Additional layers of security were used on this software application. We started by adding a Certificate of Authentication (CA) and then we deployed a cipher by implementing the cryptographic hash algorithm by refactoring the code. This cipher algorithm that was used is the SHA-256 as mentioned in Step 1 and Step 3. We then secure communications by refactoring the code to convert HTTP to the HTTPS protocol. Then for the second testing, I ran a secondary static testing of the refactored code by using the OWASP Dependency-check Maven to ensure the code compiles with software security enhancements.

Certificate authorities (CA) are very important for security since it is a trusted organization that verifies websites. There are a lot of malicious fake websites created by hackers and these websites try to copy other popular websites to steal information. Hackers can create fake websites that look identical to other ones however the real one will have its own certificate authorization making it trustworthy and safe to use. By looking at the certificate we can see if that website is really who they claimed to be.   Applying industry standard best practices to secure coding to the company’s overall wellbeing is very important and a priority to maintain the data of the users safe and make it a safe place for users to use. 
