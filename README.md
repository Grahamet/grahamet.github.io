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
