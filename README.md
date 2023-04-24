# CS-305
## Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Our client was Artemis Financial, a consulting company that developes individualized financial plans for their customers which include savings, retirement, investments, and insurance. Artemis Financial has a public web interface and we were tasked with helping them add a file verification step to that web application.
## What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
In this project we found Artemis Financial's security vulnerabilities through manual review and static testing and then documented potential vulnerabilities from dependencies. It is important to code securely to avoid allowing private information from being able to be taken by intruders. For Artemis Financial this is important as they deal with personal customer information and money. If they were to not protect this information an intruder would probably be happy to relieve them of their money and information which would be bad for the company as a whole.
## What part of the vulnerability assessment was challenging or helpful to you?
I think the most challenging part of the vulnerability assessment for me was the manual review because I am not entirely sure where problems could arise. I found the Maven dependency check very helpful as there is no way I would be able to find potential problems in the dependencies if I couldn't figure out the ones in the small amount of code given.
## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
In this project we just assessed the potential issues but we did find multiple vulnerabilities in the dependencies used. Some of the vulnerabilities in dependencies could be avoided by updating them to newer versions where those problems are fixed so that does help increase the layers of security. I would use maven again to decide mitigation techniques as I think it was very helpful.
## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I tried to run the code and also ran Maven dependency checks often to try to avoid introducing new vulnerabilities.
## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I can see the dependency check being useful in the future.
## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
The ability to run a dependency check and identify which vulnerabilities are relevant.
