# CS255
Portfolio Submission


1. Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?
DriverPass was a system design project for a small driving instruction company (the client) that wanted to improve how students prepare for the DMV driving test. The company asked for an online system that would let students sign up for accounts, schedule in-person driving lessons with instructors, access practice tests/study materials for the written exam, and track their progress. The system also needed admin features so staff could manage packages, view student performance, and update available lesson times.


2. What did you do particularly well?
One thing that went especially well was translating the interview/requirements into structured models. I clearly identified different user types (student, instructor, admin) and mapped what each of them needs to do in the system. I also built UML diagrams (use case, activity, sequence) that showed the flow of key actions like “schedule a lesson” and “take a practice test.”


3. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
I would revise the nonfunctional / technical requirements section.


4. How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?
I started to picture them as real people, with needs I could relate to real life, not just what the system could do in theory.


5. How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?
My approach is basically:

Requirements gathering

Listen to the client in plain language. What hurts right now? What do they wish they could do?

Separate functional requirements (“the system lets students book lessons”) from nonfunctional requirements (“the system should be available 24/7”).

Modeling

Create use case diagrams to show who interacts with the system and why.

Create activity diagrams/sequence diagrams to show how key processes actually happen step by step.

Create class diagrams (or an early data model) to show what data the system needs to store.

Validate with the client

Re-explain the design in simple terms to ensure it still aligns with their expectations.

Plan the build

Identify main components (scheduling module, test module, admin module, etc.).

Note technical constraints like security, performance, and future growth.

Going forward, I would keep using a blended approach: object-oriented modeling for the structure (classes, data, responsibilities) and process modeling for the workflows (how a task moves from start to finish). I’d also add two strategies:

