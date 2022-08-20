#### Introduction

Prevention is better than cure. Not installing defects in the first place is better than debugging. This can be achieved only through paying attention to quality assurance fundamentals from Day 0 of your project.
![WhatsApp Image 2021-09-20 at 10 25 37 AM](https://user-images.githubusercontent.com/83284294/133961075-1a4358c1-40ad-4221-98c2-7e1cd5bb5e9e.jpeg)

#### Does poor quality hit?

After surveying 4000 projects, it is found that poor quality is one of the most common reasons for schedule overruns. Poor quality is the reason for half of the cancelled projects.

Here is how time and effort are lost due to bad quality.

- The original effort spent designing and implementing the 'bad quality code' or 'cut-the-corners-short code' is wasted, because sooner or later the entire code will be thrown away.
- By writing a bad code, you are postponing the problem to later. Time spent unit-testing and debugging the code is down the drain. At a later time of the project, either the bad module will have to be replaced, or worse- scattered with patchwork
- Additional time will be spent to strip the bad module out of the main code and modify it. Additional testing and debugging time will be spent to ensure that the modified code still works.
- Time will be spent in the design and implementation of the entire code due to changes in the bad module. the new code, which should have been designed as an integral part of the system has to be designed around the system.

All this could have been prevented if necessary steps would have been taken to ensure a good-quality code from the start.

#### A stitch in time saves nine.

If you can prevent defects or detect and remove them early, you can realize significant schedule benefits.
Studies have found out that reworking defective requirements, design and code typically consumes 40-50% of the total cost of software development.
Requirements defect that is left undetected until construction or maintenance will cost 50 to 200 times more than at requirements time.
If a defect is not detected in the early stages, it becomes a time bomb later, with 10-100 times much more effort to fix.

![WhatsApp Image 2021-09-20 at 10 49 01 AM](https://user-images.githubusercontent.com/83284294/133961079-746840f3-bdaf-449c-9cc3-55d1bf82da90.jpeg)

**The longer defects remain undetected, the longer they take to fix. Correct defects while they are young and easy to control**

#### Prevention is better than cure.

Every hour you spend on defect prevention will reduce your repair time by 4-5 hours. So the key to success is to implement practices that prevent the errors rather than fix them.
An error-prone module is the one that is responsible for a majority of the bugs. **20% modules are responsible for 80% of bugs.** Prevent the existence of such modules by using the practises given below.

#### Practises to prevent errors

- **Testing** Testing is the black sheep of QA. It is the messenger of disaster to the management. But the best way to tackle it is to plan ahead for the bad news. Deliver it as early as possible. Unit testing, where the developer checks their own code to verify if it works correctly has effectiveness in the range 10-60. System testing, in which an independent tester checks the system operation has an effectiveness of 20-60%
- **Technical walkthrough** Walkthrough is a method by which two or more reviewers review technical work to improve quality. Walkthroughs can find between 30-70 per cent of errors in a program. Such inspections are very effective when performed in the early stages and each hour spent in inspection saves 20 hours of maintenance overhead.
- **Code reading** In code reading, two or more reviewers (except for the author) review the code. This method is very effective and finds twice the number of defects per hour than testing.
- **Code review** Code reviews are the most cost-effective on a per0defect basis. This is because they detect both the symptom of the defect and the underlying cause at the same time. Testing detects only the symptom of the defect and not the cause, and the developer still has to find the root cause of the defect. They not only tend to find a higher percentage of defects but also provide a forum for developers to share their knowledge of best practices with each other, which increases their rapid development over time. Thus, technical reviews are a critical component of any development effort that is trying to achieve the shortest possible schedule.

_Notes from [Rapid Development: Taming Wild Software Schedules by Steve McConnell](https://www.amazon.com/Rapid-Development-Taming-Software-Schedules/dp/1556159005)_
