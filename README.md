**# The-Gaming-Room**


**# CS 230 Portfolio Artifact: The Gaming Room**

Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
What did you do particularly well in developing this documentation?
What about the process of working through a design document did you find helpful when developing the code?
If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?


**Answers**:


**1. Summarize briefly who The Gaming Room client is and what their software needs are? Who was the client? What kind of software did they try to have you design?**

Creative Technology Solutions (CTS), wanted a cross-platform web release of their game “Draw It or Lose It,” previously released on Android only. The new software had to accommodate multiple teams (of three or more people apiece), run four, one-minute rounds per game, and pull from a repository of stock images for gameplay. Requirements were to support multiple teams with an ability to customize team skins, give unique identifiers and names to each game, team, and player, and to ensure only one game could run at a time. There was no other option than a web app that worked on all devices, with the UI following the Android version or a redesign and respecting image licensing.

**2. What do you feel you did best in writing this documentation?**


Requirements and limitations were clearly described in the documentation, ranging from technical limitations to legal constraints such as image licensing. It included a detailed description of system structure, domain modeling (with references to UML), and platform comparison so that all parties involved knew what was needed, both from a technical and business point of view. They appreciated the clear and organized manner of the document, and the client and development team were able to follow along without issue.

**3. What was it about the sit-down-read-a-design-document that helped you when you were actually writing code?**



The code was instrumental in getting a better feel for the relationships among entities (Game, Team, Player), the flow of information, and tech stuff like unique ids and memory management for a single game. This front-loaded planning approach minimised uncertainty in coding and resulted in smoother implementation, especially for functionality such as team management, cross-platform support, etc.



**4. If you could revise one part of your work on these papers, what would it be? How would you improve it?**

If I could make a change, I would add a bonus system architecture section with more specific diagrams and descriptions of how the client/server part communicates. Sequence diagrams and increased explicitness of the logical topology would keep the architecture more transparent for decision makers and future developers.

**5. How did you understand the user’s needs, and how did you integrate them into your software? Why is it necessary to have the user in focus when designing?**

User requirements were identified by mapping game features (multi-team support, unique ID, anti-cheat, responsive UI) as specific technical features. The concept made the interface intuitive and recognizable to previous users of the application, both on the platform. Taking into account user requirements is important because it determines the acceptance, satisfaction, and success of the software. Disregarding these requirements can cause the product to be incompatible with the class of interested users.

**6. What was your design strategy for software? What methods you may have applied in the future for analyzing and designing similar software application?**

It started with collecting information regarding the requirements and constraints, and then modeling the domain entities and their relationships. I compared the choice of platforms, security, storage, and compatibility for scalability. In such a case, further down the road, I would do the exact same UML for modeling, force early stakeholder feedback, and prototype to confirm the UI/UX approach. Concepts like iterative design and regular code review would undoubtedly be part of the process as well.
