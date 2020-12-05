# CSCI 362 Blog

## HW0: Introduction

My name is Ethan Graham.
I am now a senior at Cofc. If campus opens and we can move into dorms I will be living in a historic house on Meeting St. 

## HW1: Chapter 1

**1.3 What are the four important attributes that all professional software should possess? Suggest four other attributes that may sometimes be significant.**
  - Acceptability 
  - Dependability & Security
  - Efficiency
  - Maintainability
  
**1.8 Discuss whether professional software engineers should be liscensed in the same way as doctors or lawyers.**
  - I believe that professional software engineers should be liscenesed the same way doctors are liscenced. I believe this because Software engineers are responsible for the software in devices that can impact a person health such as insulin pumps to ai. They should be liscened so only people who aren't ignorant to ethics can   
    create the software with minimal accidents that could happen. 
    
**1.9 For each of the clauses in the ACM/IEEE Code of Ethics shown in Figure 1.4, propose an appropriate example that illustrates that clause.**
  -Public: Software engineers shouldn't create software that could negatively impact the general public or clients such as viruses. 
  
  -Client and Employer: Duty to fulfil your job of creating software that only has one purpose without being used for secondary purposes that goes against public
   interest such as obtaining and then selling personal information.
   
  -Product: Software engineers should test the integrity and functionality of ther programs before submitting there final product.
  
  -Judgement: Software engineer should be able to refuse to work on something that is against their ethics.
  
  -Management: Software engineering managers should be enforcing ethical software development and hold members accountable for violating ethics or legal rules.
  
  -Profession: Software engineers shouldn't be postponing maintaining the integretiyof their software for personal gain.
  
  -Colleagues: Software engineers should be respectful of other Software engineers and be able to have intellectual conversations without consequences.
  
  -Self: Software engineers should be continuously testing themselves and pushing themselves to learn more.
  
**1.10 To help counter terrorism, many countries are planning or have developed computer systems that track large numbers of their citizens and their actions. Clearly, this has privacy implications. Discuss the ethics of working on the development of this type of system.**
  - There are many ethical issues to having software that tracks large numbers of citizens and their actions because the information could be stolen or used for a secondary purpose by others such as the government will not willing close it.

## HW2: Reflections on software engineering practices

Brook’s [“No Silver Bullet”](http://bowringj.people.cofc.edu/classes/csci%20362/docs/NoSilverBulletOriginal.pdf), Neville-Neil’s [“Kode Vicious”](http://bowringj.people.cofc.edu/classes/csci%20362/docs/p32-neville-neil.pdf), and Potvin & Levenberg’s [“Why Google Stores Billions of Lines of Code in a Single Repository”](http://bowringj.people.cofc.edu/classes/csci%20362/docs/GoogleCodeRepo-78-potvin.pdf?id=0B2El51RQ1MQnTTVWYVNiOWhuX0U) have a common theme and argument that starting small and over time growing incrementally is extremely beneficial to software and its development. Brooks, Neville-Neil, and Potvin & Levenberg all also argue the importance and benefits to having a history of previous instances and versions of the software. They argue that making small commits consistently and frequently is important as by having this history of commits and versions of the software the integrity of the software is maintained. This also makes it significantly easier to go back and restore the code from a previous version or adjust a part of the code to that of a previous version. In Neville-Neil’s “Kode Vicious” he talks about how one way to approach a problem is to apply the scientific method to it and make the problem the hypothesis that is to be proven or disproven through different tests. Doing this lets him have a log of tests that he could potentially use in the future if he comes across a similar issue in the code. Having the log of proven and disproven tests makes it easier so he does not use a test that did not work in the past. Neville-Neil’s claim that all code should be stored and backed up in some form of version control way is supported by Potvin and Levenberg in “Why Google Stores Billions of Lines of Code in a Single Repository” where Potvin and Levenberg describe the many advantages to storing and vigilantly maintaining a monolithic repository, which stores the history of all the code versions as well as making it possible for a worldwide team of developers to work on a single source code. Brook also adds to this concept by also praising the idea of growing software over building software. He recommends that all developers first have a small working base, this makes it easier to add to it without problems such as over-complication happening or even missing the entire point of the software’s purpose. Both Brooks and Neville-Neil believe in the merits and benefits of science and that software engineers should be basing their inspirations on natures complexities. Brook’s also advocates for top down software design as it is a “top-down growing of the software”. This argument lines up with Google’s approach to improving and developing their codebase. Brook’s, Neville-Neil, and Potvin & Levenberg all agree that well-designed, maintainable code that is adaptable to the user or clients changing needs is grown from a single base source, edited in small batched, tested, and merged to the master source. Google’s monolithic repo that has billions of lines of code is not for everyone. It is best suited for organizations that are as large as Google where they have an open and collaborative culture. Having the code in one repo makes code sharing encouraged as well as being able to reuse the code more possible. This makes it possible for developers to share ideas and learn from each other which saves redundancies across the code.


## HW3: Chapter 11 & 12

**11.4 What is the common characteristic of all architectural styles that are geared to supporting software fault tolerance?**
  A system that has redundant and diverse hardware and software
  
**11.7 It has been suggested that the control software for a radiation therapy machine, used to treat patients with cancer should be implemented using N-version programming. Comment whether or not you think this is a good suggestion.**
  I think this is a good suggestion as it would only expose the radiation to the person once but also run the tests multiple times based on the results which makes it safer for the patient.
 
**11.9 Explain why you should explicitly handle all exceptions in a system that is intended to have a high level of availability.**
  If the system has exceptions that aren't handled then the software may fail and end which would cause it to not be highly available.
  
**12.5 A train protection system automatically applies teh brakes of a train if the speed limit for a segment of track is excedded, or if the train enters a track segment that is currently signaled with a red light (i.e the segment should not be entered). There are two critical saftely requirements for this train protection system:** 
  
  * The train shall not enter a segment of track that is signaled with a red light
  * The train shall not exceed the specified speed limit for a section of track

**Assuming that the signal status and the speed limit for the track segment are transmitted to on-board software on the train before it enters the track segment, propose five possible functional system requirements for the onboard software that may be generated from the system safety requirements.**
  
  1. Check the colour of the signal at the upcoming track (z)
  2. Check the speed limit of the upcoming track (y)
  3. If the train speed is greater than (y) gently apply breaks
  4. If the train speed is slower than (y) slowly speed up to (y)
  5. If (z) is red find a segment stop or find another track that is green
  

## Hw4: Reflections on software failures

For all the readings “An investigation of the Therac-25 Accidents” by Nancy Leveson and Clark S. Turner, “After Stroke Scans, Patients Face Serious Health Risks” by Walt Bogdanich, “Motor Vehicles Increasingly Vulnerable to Remote Exploits by FBI Public Service Announcement, “The Role of Software in Spacecraft Accidents” by Nancy G Leveson, “Who Killed the Virtual Case File?” by Harry Goldstein, “FBI Sentinel project is over budget and behind schedule, says IG auditors” by Jeff Stein, “Years Late and Millions Over Budged, FBI’s Sentinel Finally On Line” by Damon Poeter, “FBI’s Sentinel System Still Not In Total Shape to Surveil” by Robert N.Charette, and Chapter 12 & 13 in “Software Engineering” by Ian Sommerville each involve investigations into a variety of software-related accidents. These accidents range from potential threats towards hacking of modern automobiles to spacecraft crashes. Although each article or text vary, they all share a common theme and viewpoint about the importance of proper safety and security techniques needed to implement and design dependable software. Out textbook in Chapter 12 introduces to us the concept of safety-critical systems: “the system should never damage people of the system’s environment, irrespective of whether or not the system conforms to its specifications” (Sommerville 341 global edition). Sommerville also says that a dependable system is secure if it protects the confidentiality of its information, and the information cannot be changed by an unauthorized person, and the system is always available for its intended use. Having flaws in a systems security can have drastic effects in regards to safety. The FBI’s Public Service Announcement on the cyber security threats to modern automobiles is an example of how having system security flaws can affect safety. Each article we had to read go into detail about how software systems were incorrectly implemented and what accidents resulted because of this, and what could have been done differently to avoid the sometimes devastating accidents. 
The common themes between each articles was bad software design management where the developers didn’t keep everything simplified but rather reused old code, another common theme was a lack of communication and understanding of the program during testing and development, and general self-approval and time-integrity trade offs which results in the code functioning in less than optimal ways. The biggest commonality is that the information on these accidents that happen in the articles are very hard to find which leads to people having a false hope and false belief that they are safe and secure.
Leveson wrote a couple articles on software related accidents that resulted in deaths or serious illnesses. Tuner helped Leveson write an article that focused on patients exposed to the Therac-25, a radiation therapy system released in the 1980’s. Leveson and Turner point out that Therac-20 and older model was reused even though Therac-25 was designed to have more responsibility for maintain safety than its older models. Leveson also goes into details on software related accidents in spacecraft where code from the Ariane501 which crashed was reused from and older model Ariane 4 with redundant functions left in. 


## Hw5: Chapter 4 and reflections

**4.5) Using the technique suggested here, where natural language descriptions are presented in a standard format, write plausible user requirements for the following functions: **

**- An unattended gas pump system that includes a credit card reader.  The customer swipesthe card through the reader, then specifies the amount of fuel required.  The fuel is delivered and the customer's account debited.**
  * Function -> Charge the customer for the amount of gas specified and dispense the specified amount of gas.
  * Description -> Computes the required amount of money needed for the specificed amount of gas.
  * Inputs -> The specified fuel amount and the credit card information
  * Source -> User interace system on the pump and the credit card reader
  * Output -> The specified fuel amount and the reciept with the required money amount on it
  * Destination -> The car and the bank
  * Action -> Customer will input the required amount of fuel they need, the program will dispense the amount and calculate the amout of money required, the customer will put their card into the card reader, when processed and accepted the card reader will dispense a recipt.
  * Precondition -> There must be fuel in the pump, the card must be vaild and have funds
  * PostCondition -> The fuel in the pump must be subtracted, the card must be charged, and the specified amount of gas must be dispensed.

**- The cash-dispensing function in a bank ATM.**
  * Function -> Dispense correct amount of cash
  * Description -> verify cardholders pin and dispense the requested amount of cash
  * Inputs -> amount of cash wanted, card number, pin number
  * Source -> User Interface, card reader, pin pad
  * Outputs -> Cash, receipt, card
  * Action -> User inputs card, enters pin, user selects amount of cash they want, Checks to see if requested funds is available to dispense in users account, Atm checks to requested funds is available to dispense from the machine, atm dispenses the cash if previous checks pass, returns card, dispenses receipt.
  * Precondition -> User must have requested funds in account, Atm must have requested funds, user must have a vaild card, and user must enter a valid pin.
  * Postcondition -> Amount of cash in atm and users bank account must be subtracted, transaction must be recorded.

**- In an internet banking system, a facility that allows customers to transfer funds from oneaccount held with the bank to another account with the same bank.**
  * Function -> Transfer money specified from bank account to another that belongs to the same bank.
  * Description -> Transfer funds from one account to another 
  * Inputs -> Username, password, Bank account being transfered, bank account transfering money from, amount to transfer, and a check to make sure they want to do the transfer.
  * Source -> Reading of amount to be transfered, 
  * Outputs -> cash, and receipt
  * Action -> User logs onto the banking system, username and password get verified, user must chose the account they are transferring money from, user selects destination account for the money, user selects amount to be transfered, gets a conformation they want to proceed with transfer, funds get transfered if they agree to transfer, user gets sent a email receipt with the transfer details and if it went through successfully/unsuccessfully.
  * Precondition -> User must log into bank system with valid user information, user must have funds to transfer in their account, recieving account must be valid and part of the same bank.
  * Postcondition -> receiving account add transfered amount, original account subtracts transfered amount. 
  
**4.6 Suggest how an engineer responsible for drawing up a system requirements specifications might keep track of the relationships between functional and non-functional requirements.**

The engineer could use some sort of visual system to differentiate between non-functional and functional requirements. They could also use UML to display a graphical model such as a diagrm, sequence or charts. Having different visuals could help the engineer see the differences between requirements and how they affect the system as a whole which will then lead to being able to clearly define the specifications of the project for other engineers, clients and himself/herself.

**4.7 Using your knowledge of how an ATM is used, develop a set of use cases that could serve as a basis for understanding the requirements for an ATM system.**

  1.  User inserts debit card into the ATM
  2.  ATM reads card; asks for pin number.
  3.  User inputs correct pin number.
  4.  ATM verifies pin number; ATM asks user for what they want to use the ATM for:
      * Withdrawal OR
      * Balance check OR
      * Deposit
  5. User chooses an option.
      * User enters amount to withdraw OR
      * User asks for account balance OR
      * User inputs amount to deposit
  6. ATM
      * Checks if there are enough funds to withdraw that amount from and, if there are releases money to user OR
      * Print receipt for account balance OR
      * Accepts deposit and prints receipt
  7. User receives debit card back. Transaction over. 
  
  
  
## Hw6: Chapter 2

**Suggest the most appropriate generic software process model that might be used as a basis for managing the development of the following systems. Explain your answer according to the type of system being developed:**

  * **A sytem to control antilock braking in a car-** The waterfall process is usually adapted for safety-critical systems because of the higher amount of analysis and documentation require before implementation, because a major part of finalizing the software is testing i think the waterfall model is the most appropriate generic software proccess
  
  * **A virtual reality system to support software maintenance-** Software maintenance is best done through versions and updates over long amounts of time, which would lead to the incremental development process as the most appropriate.
  * **A university account that replaces an existing system-** The integration and configuration process seems like it would be the best choice for a new account system as it takes reusable components and integrates them into a new system setting
  * **An interactive travel planning system that helps users plan journeys with the lowest environmental impact-** I think this would be the incremental development process as a planning system would need to be adaptable and have multiple versions.


## Hw7: Chapter 5 & 6

**5.3  You have been asked to develop a system that will help with planning large-scale events and parties such as weddings, graduation celebrations, and birthday parties. Using an activity diagram, model the process context for such a system that shows the activities involved in planning a party (booking a venue, organizing invitations,,etc. ) and the system elements that might be used at each stage.**

![5.3 image](https://github.com/Grahamet/grahamet.github.io/blob/master/Images/5.3.png)

**Develop a sequence diagram showing the interactions involved when a student registers for a course in a university. Courses may have limited enrollment, so the registration process must include checks that places are available. Assume that the student accesses an electronic course catalog to find out about available courses.**

![5.5 image](https://github.com/Grahamet/grahamet.github.io/blob/master/Images/5.5.png) 

**5.7 Based on your experience with a bank ATM, draw an activity diagram that models the data processing involved when a customer withdraws cash from the machine.**

![5.7 image](https://github.com/Grahamet/grahamet.github.io/blob/master/Images/5.7.png)

**5.8 Draw a sequence diagram for the same system. Explain why you might want to develop both activity and sequence diagrams when modeling the behavior of a system.**

![5.8 image](https://github.com/Grahamet/grahamet.github.io/blob/master/Images/5.8.png)

## Hw9: Chapter 8 and reflections

**Write a scenario that could be used to help design tests for the wilderness weather station system**

Tom works for a wilderness weather station out in Kells, Northern Ireland. He spends a lot of time at work because he often gets snowed in and has to spend the night. This gives him plenty of time to test the weather station software. First, he has to log onto the system using his weatherman username and password. 

Tom usually first checks the status of the satellitle communcations (SatComm) and the regular communications (Commslink) link to ensure that the summary is being collected from up-to-date data. He then will request a weather data summary report from satellite communications and receive an acknowledgement of this request. 

Tom knows the weather station will send him a report if it is unable to collect data via the Commslink and it will also acknowledge that he requested a report. Always alone and drinking coffee, Tom looks forward to receiving the summary report of the weather data to give him something to do on long snowy days at work. 

**A common approach to system testing is to test the more important functionalities of a system first, followed by the less important functionalities until the testing budget is exhausted. Discuss the ethics involved in identifying what “more important” means.**

This is not a very ethical approach. Testing is time-intensive and often leads to changes in software as the tests reveal issues. The testing period should have plenty of time devoted to it to ensure that a customer is getting, if not a totally bug-free product, at least a product that has undergone extensive testing before it was deemed appropriate to receive money for. A testing budget should also be a little bit larger because of its importance to a project. 

If a software company develops and delivers software to an external customer without putting in significant testing time, then how can the software company be sure that they will get that customer back? A company can only ensure returning customers if they have put the time and effort into making their product the best it can be for the requirements asked for and tested it effectively to the best of their abilities.

## Hw10: Chapter 15

**The reuse of software raises a number of copyright and intellectual property issues. If a customer pays a software contractor to develop a system, who has the right to reuse the developed code? Does the software contractor have the right to use that code as a basis for a generic component? What payment mechanisms might be used to reimburse providers of reusable components? Discuss these issues and other ethical issues associated with the reuse of software.**

I think there will forever be a debate between groups who want to share everything and groups who want acknowledgement of their achievements and therefore the rights to their own software. The former group will argue that they have built working software and its reuse is important in order to save time and expenditure on creating more software that works the same way in a future product. The latter group will argue that they have the sole right to reuse software that they developed.

## Hw11: Chapter 9

**Briefly describe the three main types of software maintenance. Why is it sometimes difficult to distinguish between them?**
  
  1. Bug Fixing - this is repairing faults found in the software after it has been launched. The bugs are there possibly because testing was not as thorough as it should have been or clients have exposed bugs by using the software in unexpected ways. Coding errors, design errors, and requirement errors are the least, middle, and most expensive to correct, respectively. 
   2. Modifying software to work in a new environment - when the hardware or platform that the system was built to run on changes, then the software must change as well in order to be compatible and avoid being obsolete.
    Implementing new or changed requirements - software must be updated or changed so that it conforms with any new requirements. 

It is sometimes difficult to distinguish between the different types of maintenance because they are often given different names and also because faults that arise within a system can maybe have overlapping maintenance requirements.

**Do software engineers have a professional responsibility to develop code that can be easily maintained even if their employer does not explicitly request it?**

Yes. Software development and maintenance are not separate activities. It is important to keep in mind how a system will need to be maintained if, for example, it is a system that is meant to last a long time and will have a revolving-door of developers working on it. A software developer who cares about the quality of their work will want to reduce the future cost of maintaining their software. According to the textbook, they can do this by using "Good software engineering techniques such as precise specification, test-first development, the use of object-oriented development, and configuration management" to help reduce the cost of future maintenance (Sommerville 259).  The ACM Software Engineering Code of Ethics says that a software engineer must "promote an ethical approach to the practice of the profession". This can only by done by carefully constructing software that is in the best interests of the employer (even if they do not require it), the client (who will have to pay for future maintenance), and the public (who want to use the software).

## Hw12: Chapter 16

**Design the interfaces of components that might be used in a system for an emergency control room. You should design interfaces for a call-logging component that records calls made, and a vehicle discovery component that, given a post-code (zip code) and an incident type, finds the nearest suitable vehicle to be dispatched to the incident.**

![CallLogger image](https://github.com/Grahamet/grahamet.github.io/blob/master/Images/Call%20Logger.png)

![Vehicle image](https://github.com/Grahamet/grahamet.github.io/blob/master/Images/vehicle.png)

## Hw13: Chapter 17 

**Your company wishes to move from using desktop applications to accessing the same functionality remotely as services. Identify three risks that might arise and suggest how these risks may be reduced.**

  1. **Security** - there is definitely a risk that the information needed for the company will be less secure if it is able to be accessed remotely. This risk may be reduced by implementing extra security precautions as well as decreasing accessibility of information to only certain parties.
  2. **Failure Managment** - if the system is available remotely as a service, it becomes more complicated with many more parts involved in the success of the system. The system will rely on all components (the computer, the server, access to the server) functioning properly in order to work. So there is a higher risk that the system will fail because there are more components that need to work together.
  3. **Transparency** - because of the different components that have to work together, there is a higher risk that users will be aware of flaws in the system and inconsistencies in the software.
  
## Hw14: Chapter 18

**Define an interface specification for the Currency Converter and Check credit rating services services shown in Figure 18.7.**

![currency converter and credit rating image](https://github.com/Grahamet/grahamet.github.io/blob/master/Images/Screenshot%202020-12-04%20191112.png)

## Hw15: Chapter 19

**Why is it impossible to infer the emergent properties of a complex system from the properties of the system components?**

The emergent properties of a system characterize the entire system - all of a system's components' properties are included in this as well as their ability to work together. The emergent properties include properties such as performance, reliability, usability, safety, and security. A component can often be considered reliable, safe, etc. when functioning on its own, but when it is a part of a system, those properties are not enough. Emergent properties encompass component properties as well as defining whether the components work together or not. It is difficult to distinguish emergent properties of a complex system from the system components because the emergent properties depend on the components working as expected.

## Hw16: Chapter 20

**You work for a software company that has developed a system that provides information about consumers and that is used within a SoS by a number of other retail businesses. They pay you for services used. Discuss the ethics of changing the system interfaces without notice to coerce users into paying higher charges. Consider this question from the point of view of the company's employees, customers, and shareholders.**

I am sure from the shareholder perspective, they would not mind if the users were not informed of the increase in price, but this is completely unethical. A software company has a lot of power when it comes to hiding things from the public and from their customers, but they should not take advantage of this. The employees of the software company might feel uncomfortable with having to make this unethical change to the system, but will probably be unlikely to speak up in case they lose their jobs. Customers, being unaware of the change, will not have an opinion UNTIL (because it is bound to come out eventually) it is found out that the software company increased prices without notifying consumers. Then the shareholders will pretend they had no idea and blame it on the developers. The employees will probably be out of a job anyway once the consumers find out about everything, and then those employees have a stain on their record for the rest of their careers. So, all in all, it is a terrible idea, both for ethical reasons and practical ones.

## Hw17: Team Progress 1

Our team, [“Team-Gr8”](https://github.com/csci-362-01-2020/Team-Gr8) is doing really well. A detailed description of the progress we have done so far can be found on our [“wiki”](https://github.com/csci-362-01-2020/Team-Gr8/wiki) page. We have completed the three deliverables that we have been assigned and even had our automated testing framework done as early as deliverable two as we found that once we had that fully working it was easier to set up our testcases from then onwards.


**Our current Script**
![script inmage](https://github.com/Grahamet/grahamet.github.io/blob/master/Images/Screenshot%202020-12-04%20192732.png)

**Our current test cases**
![testcaseImage](https://github.com/Grahamet/grahamet.github.io/blob/master/Images/Screenshot%202020-12-04%20193853.png)

Our current goal for our next step is to be able to send our outputs to an html file so that we can present our data through the browser in a neat format such as a table.

## Hw18: Chapter 21 and Chapter 22

**22.6 Fixed-price contracts, where the contractor bids a fixed price to complete a system development, may be used to move project risk from client to contractor.  If anything goes wrong, the contractor has to pay. Suggest how the use of such contracts may increase the likelihood that product risks will arise.**

Fixed-price contracts are attractive to potential software development clients because it guarantees them a predetermined budget and also allows for all the risk to be taken up by the contractor. Fixed-price contracts mean that the contractor takes on any extra costs that could incur because of changes in requirements or technology that affect the timeline for the project's completion. While this may be a benefit for the customer, who will have more power to change their mind and project requirements, it is much more likely that product risks will arise because of bad communication, changes in plans, and off-schedule development. And all of these problems will be up to the contractor to take care of, which does not seem like a smart business plan.

## Hw19: Chapter 23

**Figure 23.14 shows the task durations for software product activities. Assume that a serious, unanticipated setback occurs, and instead of taking 10 days, task T5 takes up to 40 days. Draw up new bar chart showing how the project might be reorganized.**

![project reorganization](https://github.com/Grahamet/grahamet.github.io/blob/master/Images/Screenshot%202020-12-04%20193613.png)

## Hw20: Team Progress 2

Our team currently is progressing really well. A detailed report of what our progress is can be found on our wiki in [“Deliverable #4”]https://github.com/csci-362-01-2020/Team-Gr8/wiki/Chapter-4).

Currently we have:

  * 25 working test cases
  * A working script that can run a single test case
  * A working script that calls our other script to run through all our testcases in our TestCase folder
  * Brower viewable results 
  
I believe we have worked well as a team so far with constant communication and fairly distributed work. I believe that we have been fully prepared for each deliverable with working code that either meets or exceeds whats needed to be done. We are currently prepared to move on to our next deliverable where we insert 5 faults into our code and demonstrate where they are and how many testcases they will affect. We will aslo have our final report, poster and presentataion available soon.

## Hw21: Chapter 24

**Explain why program inspections are an effective technique for discovering errors in a program. What types of error are unlikely to be discovered through inspections?**

Program inspections ensure that fresh eyes read over code that could have defects in it. Sometimes it is hard to find errors in your own code if you have spent hours and hours writing it - it really helps to get a second opinion, especially if it is in the context of a program inspection, where the team members know what the code needs to do and there is a moderator who can ensure that criticism is appropriate and unbiased. When programming for a team, it is fair that the team will get to review each others code before the code is put to use - this enables everyone to be a part of the work, and everyone is culpable for any failures. 

I think errors that are unlikely to be discovered through inspections would not be in the functionality of the code itself, but maybe in how that component works with others when the program as a whole is run. This is hard to check until the team's release of the code has been combined with other working parts of the software. But ensuring that the code works as expected in a small capacity will go a long way in getting it to work effectively with the software as a whole.
