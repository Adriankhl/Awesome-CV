## Please, describe the project you are most proud of. What was the technical problem and how did you solve it? What was your contribution to the project?

I am very proud of my project - Relativitization, which is an agent-based simulation framework and also a turn-based strategy game in 4D, relativistic spacetime. Social scientists can use the framework to build models to study interstellar society, and others can just have fun with the game. The software is written in Kotlin. I am the creator and the sole developer of the project. You can find it at https://github.com/Adriankhl/relativitization

The framework is required to be performant, physically correct, and easy to use. Special relativity tells us that there is time delay and time dilation, which affects what an agent can see and how they can interact with each other. Therefore, I have to craft the data structure, algorithm, and API carefully to fulfill the need. I have also parallelized the computation using coroutine. It is handy to have immutable data to ensure the correctness of the parallelized computation, so I have created a small code-generation library KSergen (https://github.com/Adriankhl/ksergen) to generate immutable data classes from mutable data classes.

The game must have a GUI, and I would like it to have multiplayer functionality. Since I was not a professional game developer, I had to figure them out myself. I implemented the server-client architecture with the Ktor library, where messages are transferred through the HTTP protocol. I built the GUI based on libGDX, which works on both PC and Android devices.

In general, it is quite challenging to turn a cool idea into a software with more than 60k lines of code, while keeping everything to function well together. I surely have become a more mature developer after the project.

## Why are you interested in joining Adyen?

Adyen is a top player in the payment industry, where it offers an opportunity to work with data on a global scale. Besides, the Dutch directness is a valuable perk in a workplace.

## What is your experience with Data Engineering or Big Data technology?

I have over 6 years of experience in data-oriented research for both natural science and social science, with “biggish” (order or TB) data. Having created and contributed to several open projects, I am capable of doing proper software engineering.

## Ubisoft: Let the company know about your interest working there

Apart from my game development experience in Kotlin, I am also an enthusiastic open source game contributor, mostly in C++. Therefore, I am confident to be capable of working on C++ or C# projects.

I have a Hong Kong passport, which means I can apply for the open work permit Hong Kong recent graduates, no sponsorship is needed.
