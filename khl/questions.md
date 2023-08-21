## Indie game developer description
As a by-product of my PhD research, I have created a turn-based strategy game in 4D, relativistic spacetime

## GPA
Bachelor 3.314, Master 3.367

## Link
https://github.com/Adriankhl
https://www.linkedin.com/in/adrian-k-h-lai


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

## Why do you want to work in IT in the bank? (maximum 200 words)
Growing up in one of the biggest financial centers (Hong Kong), banking industry always has a special place in my heart. However, as a tech-savvy person, I used to have the impression that banks rely on legacy technology. Things have changed lately, I realize that many banks (ING is obviously one of them) have become more tech-driven and have been working on modernizing the tech stacks. Since banks play a crucial role in the economy of modern society, contributing to technology in a bank does benefit the society. It would be interesting to have a chance to tackle the unique tech challenges in the banking industry.


## Which two future IT challenges for ING do you see and which challenge would you like to tackle? Please explain why. (maximum 200 words)*
One of the classic challenges in banking is the tension between security and agile development. Another one is to provide new functionalities to compete with flashy fintech companies. I am more inclined to tackle the security challenge. Compare to digital banks, reliability is one of the core competitiveness for traditional banks like ING, it is reasonable to have a certain level of bureaucracy. On the other hand, it is important to adopt new things. "New" does not just mean more features, it also means better maintainability, which also contributes to security in the long run. I think it is challenging but intellectually rewarding to figure out "the bank way" of secure and agile development.

## Where in the IT domain do you want to bring added value? (maximum 200 words)
Because of my interest in security, I would like to contribute to DevOps with an emphasis on security (in the flashy term, DevSecOps). While I don't have the background in DevOps, I do have some experience in proper engineering practice and CI/CD when I worked on my personal software projects and other open source projects. I believe my software development capability is well-prepared to enter this interesting domain.

Besides that, as someone who has been working on data-oriented research for some years, I always have the special interest in the big data technology. While I have experience in working in "biggish" data (in the order of TB), but they don't require any distributed processing framework, such as Spark. The scale of ING bank should provide me some opportunities to work on "actually big" data. My research experience and my skills in Java/Kotlin make me a natural fit in this domain.

## Describe a time when you have spotted an opportunity to improve process. What did you do? 

## How do you think this role contributes to the success of the airline?

## Indie game developer: Please give details of your responsibilities and what you learnt from this experience (maximum 500 words)
During my PhD journey, my passion for simulations and physics led me to put a lot of effort into creating an advanced simulation framework and a game using Kotlin. The framework simulates agent-based models in a relativistic spacetime, which could create some interesting phenomena.

Expanding on this framework, I came up with creative gameplay ideas that work with relativistic physics. For example, I replaced a global market with local economies to prevent information from traveling faster than light. Also, I set up a way for multiple players to connect through a server-client setup, and I made a user-friendly interface that works on both PCs and Android devices. I was proud to present my work by writing two research papers and showcasing it at important conferences like FOSDEM and KotlinConf.

Building the game from scratch was incredibly rewarding. I had to design the overall structure, optimize algorithms for calculating relativistic spacetime effects, choose the right libraries, create a code-generation plugin to simplify the framework, write documentation and examples to demonstrate how the framework should be used, write tests using JUnit and GitHub Actions to ensure everything is functioning correctly, and finally, release the game. This experience has transformed me into a versatile scientific software developer.

Here is the repository: https://github.com/adriankhl/relativitization

## Research of research institute: Please give details of your responsibilities and what you learnt from this experience (maximum 500 words)

I was a pivotal part of a global team spanning 5 countries that dissected the dynamics of research funding allocation, specifically examining gender biases within the schemes. My role encompassed diverse technical tasks, including data manipulation using SQL and Python, crafting intricate statistical and Bayesian models, and translating these models into Python codes.

Going beyond the standard data analysis, I delved into creating equation-based and agent-based models to decode funding applicant behaviors. I validated these models using varied programming languages like Java, Python, and Julia, enhancing my proficiency in the languages.

A crucial lesson emerged from an unexpected setback. Due to confidentiality, an engineering team managed the data platform, resulting in the inadvertent loss of our data and scripts. This experience highlighted the necessity for our team, as primary users, to be actively engaged in implementation for a robust product.

In essence, my journey enriched my data analysis skills, honed my modeling expertise, and underscored the significance of collaborative implementation for successful project outcomes.

## Ligo Scientific Collaboration: Please give details of your responsibilities and what you learnt from this experience (maximum 500 words)

Within a Nobel Prize-winning collaboration, I focused on a gravitational waves physics sub-direction. Navigating intricate theories like gravitational waves diffraction and black-hole horizon effects, I implemented models in C, conducted simulations on a supercomputer and analyzed data in Python. This led to two published journal papers and conference presentations. This experience bolstered my technical proficiency across C, Python, Linux systems, supercomputing, and simulations.

Amidst these responsibilities, a defining moment emerged when I encountered a considerable computational bottleneck while simulating diffraction equations. To overcome this hurdle, I figured out an optimization technique that leveraged caching, resulting in a significant acceleration of the computation process. This boosted my confidence in addressing intricate technical challenges.

## Programming Languages: Please give further details of your proficiency in this skill
I have developed a simulation framework and a game from scratch using Kotlin.
I use Python extensively for data analysis.
I have experience in multiple programming languages, such as Java, Julia, C++, and I have contributed to open source projects using these languages. Please check my GitHub PR page for all my contributions: https://github.com/pulls?q=is%3Apr+archived%3Afalse+is%3Aclosed+author%3AAdriankhl

## Databases: Please give further details of your proficiency in this skill
I use mainly Microsoft SQL in my current institute to manipulate data.

## Microsoft C++: Please give further details of your proficiency in this skill
I can work with big C++ codebase and debug issues. For example, I fixed a threading problem here: https://github.com/vcmi/vcmi/pull/1868

## Spreadsheet: Please give further details of your proficiency in this skill
I sometimes use spreadsheet to do data analysis, mostly Google Sheets for collaboration. I even had experience to run simulations in a spreadsheet during an undergraduate course.


