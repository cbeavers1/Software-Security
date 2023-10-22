# Software-Security

* Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

  Artemis Financial is a financial consulting company that wanted to modernize their systems. This meant securing the systems to todays standards of security and encryption. 
  
* What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

  Identifying the dependencies that required updating and implementing these updates to remove vulnerabilities was the part I did best. Secure coding ensures that risk of financial loss, or any other kind of loss, is minimized and 
  removes oppurtunities for attackers to exploit the system. 
  
* What part of the vulnerability assessment was challenging or helpful to you?

  Identifying false positive vulnerabilities was probably the most difficult part for me but ultimately helped me understand how dependency checks work. 
  
* How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
  
  Layers of security were increased by adding a 256 bit hashing algorithm to encrypt communications with the server and by ensuring all dependencies were up to date. I would continue to use the Maven dependency check tool to
  assess vulnerabilities which helps in determining whether an update is required or a refactoring of code. 
  
* How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

  To ensure secure functionality I ran a checksum verification test that produced a unique data value from a message put through a hashing algorithm. After refactoring code for encryption purposes, I ran another dependency check to ensure no known vulnerabilities arose
  from my code. 
  
* What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
  
  Using the maven dependency check tool can be extremely useful in future coding projects or assignments for assessing secure functionality.
  
* Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  
  I would use this assignment as an example for understanding security concepts required to create a secure application or program. 
  
