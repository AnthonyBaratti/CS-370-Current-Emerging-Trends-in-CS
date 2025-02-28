Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?

The code that was implemented for this project was a deep neural network built with keras and run through tensor backend. The program
is built to train on a Pirate/Treasure game, where an agent needs to navigate through a grid matrix to find the treasure. The game uses a reward
system for movement and staying in bounds. Negative points are given per movement to prevent aimless wandering. The agent is allowed 4 different actions
per state (up, down, left right). The algorithm uses a deep neural network and stores past observations for exploitation. 

I was given all of the classes that comprise the game, including the methods to store past states and actions. The neural network was also provided.
The code I had to create was the algorithm that applied the epsilon value to the exploration/exploitation ratio. I used an inverse time decay rate
which slowly turned down the exploration factor in favor of the exploitation factor, allowing the agent to explore more in the beginning epochs and exploit
more in the later epochs. The win loss ratio was calculated to determine when the pirate was achieving a 100% win ratio.

Connect your learning from throughout this course to the larger field of computer science:
What do computer scientists do and why does it matter?

Computer scientists solve problems. They create solutions to make real-world problems more efficient and user friendly. Software is generally designed
with the purpose of making things (especially complicated things like matrix manipulation/algebra) not only easier, but faster. This matters because computer science, like many disciplines
is a collection of information and data used to build on and advance the field or science. By discovering new algorithms and creating more resources,
computer science can grow upon itself for the next generation of scientists in all fields.

How do I approach a problem as a computer scientist?

First, analyzing the problem and its goals is a cornerstone for finding a solution. Understanding the scope of the problem is an important part to finding the solution.
Planning on paper is another important step, especially when the problem is complicated. This can be in the form o a check list, diagram, step by step procedure, or other.
There is a lot of trial and error to solving a problem, but being concise and specific in development can help keep the trial and error manageable, especially during debugging.

What are my ethical responsibilities to the end user and the organization?

Transparency is a key component to ethics. Being honest, and programming with integrity can save a lot of time and money, but also reduce risks involved.
Being proactive rather than reactive with proper planning, proper testing, and a society-centered moral compass are all essential to building ethical and responsible code.
