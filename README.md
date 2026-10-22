# CS-255-Project-1

1. Summary of the project
DriverPass is a driver-training company whose owner, Liam, and IT officer, Ian, were the clients. They found that many students fail the DMV test because they only study old tests. They wanted a cloud-hosted web system that offers online classes and practice tests, lets customers reserve on-the-road lessons, and gives staff tools to manage reservations, users, packages, and reports. The company has 10 cars and three packages, which range from 6 hours of driving up to 12 hours plus an in-person lesson and online class.

2. What I did well

I turned the interview into specific, testable statements, such as “The system shall prevent double-booking of drivers, cars, and customers.”
I was honest about what the client did and didn’t say. Several items are labeled as my own proposals or assumptions: the page-load targets, case-insensitive usernames, and the payment processor.
I covered the security details, including hashed passwords, TLS, encrypted card data, account lockout after failed logins, and PCI DSS.
I included the full user-interface description from Liam’s sketch.
I wrote a realistic limitations section covering the DMV dependency, the tight schedule, and the unknown budget.

3. What I would revise
I would revise the Objectives and Goals section. The measurable targets, such as “customers can complete registration without staff help,” are still vague. I would add numbers, for example a share of customers who finish booking without calling the office, a target uptime, and a limit on how quickly a DMV update notice must reach staff. I would also add a short requirements-to-source table showing which interview statement each requirement came from.

4. Interpreting user needs, and why it matters
Each person in the interview became a user role with its own needs. Liam needs reports he can print and download, so I added activity logging and Excel-compatible exports. Ian needs account control, so I added role-based access, password resets, and blocking former employees. The secretary needs to book by phone, and customers need self-service booking and progress tracking. I also inferred a driver role from the “driver notes” on Liam’s sketch.

Considering user needs matters because a system that works technically but doesn’t fit how people actually work won’t get used. Misunderstood requirements are also the most expensive thing to fix later.

5. My approach to designing software
I start from the stakeholders, turn their words into requirements, and write down assumptions and gaps so they can be confirmed. I then move to models and design. In the future I would add:

Short interviews or surveys with each user role to confirm the requirements.
Prototypes or wireframes that users can react to early.
Prioritization of requirements (for example, must-have versus nice-to-have).
Traceability from each requirement through design to testing.
Iterative delivery in small increments with regular client feedback, to avoid a single big review late in the schedule.
