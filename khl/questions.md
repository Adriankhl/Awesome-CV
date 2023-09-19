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

## Indie game developer: Brief description of your duties & responsibilities
During my PhD, I showcased my passion for tackling complexity through the creation of an advanced simulation framework and a game using Kotlin. This framework models agent-based interactions in relativistic spacetime, offering a platform for inventive gameplay. I creatively integrated relativistic physics into the game and established multiplayer capabilities across PCs and Android devices via a server-client setup. This effort led to two research papers and presentations at prestigious conferences.

Crafting the game involved optimizing spacetime effect algorithms, selecting libraries, and even creating a code-generation plugin for framework simplification. Rigorous quality control was ensured through comprehensive documentation and test automation with JUnit and GitHub Actions. The release of the game highlighted my adeptness in problem-solving, software development, and Mathematics, while the self-initiated nature of the project emphasized my commitment to continuous learning and independent action.

You can find the repository for this project here: https://github.com/adriankhl/relativitization

## Research of research institute: Brief description of your duties & responsibilities

I was a pivotal part of a global team spanning 5 countries that dissected the dynamics of research funding allocation, specifically examining gender biases within the schemes. My role encompassed diverse technical tasks, including data manipulation using SQL and Python, crafting intricate statistical and Bayesian models, and translating these models into Python codes.

Going beyond the standard data analysis, I delved into creating equation-based and agent-based models to decode funding applicant behaviors. I validated these models using varied programming languages like Java, Python, and Julia, enhancing my proficiency in the languages.

A crucial lesson emerged from an unexpected setback. Due to confidentiality, an engineering team managed the data platform, resulting in the inadvertent loss of our data and scripts. This experience highlighted the necessity for our team, as primary users, to be actively engaged in implementation for a robust product.

In essence, my journey enriched my data analysis skills, honed my modeling expertise, and underscored the significance of collaborative implementation for successful project outcomes.

## Ligo Scientific Collaboration: Brief description of your duties & responsibilities

Within a Nobel Prize-winning collaboration, I focused on a gravitational waves physics sub-direction. Navigating intricate theories like gravitational waves diffraction and black-hole horizon effects, I implemented models in C, conducted simulations on a supercomputer and analyzed data in Python. This led to two published journal papers and conference presentations. This experience bolstered my technical proficiency across C, Python, Linux systems, supercomputing, and simulations.

Amidst these responsibilities, a defining moment emerged when I encountered a considerable computational bottleneck while simulating diffraction equations. To overcome this hurdle, I figured out an optimization technique that leveraged caching, resulting in a significant acceleration of the computation process. This boosted my confidence in addressing intricate technical challenges.


##  Minimum GCSE Maths and English grade A-C or equivalent
##  Bachelor's or Master's degree in Mathematics, Economics, Computer Science, Information Management, Statistics, or a related field
##  Interest in professional development and further training.

I have completed the HKDSE public exam, achieving a grade of 5* in Mathematics, which is equivalent to a GCSE grade A, and a grade of 4 in English, which is equivalent to a GCSE grade C. Additionally, I have taken the TOEFL iBT test and achieved a score of 104 out of 120, underscoring my proficiency in English.

My educational journey includes a bachelor's and research master's degree in physics, and I am currently in the final stages of completing my Ph.D. in quantitative science studies. The rigorous coursework and research in these programs have equipped me with advanced technical skills, including mathematics, statistics, and software development.

My enthusiasm for learning has led me to explore diverse fields. I transitioned from theoretical physics to astrophysics, gaining valuable practical experience in statistical analysis. I then delved into quantitative social science, acquiring expertise in handling various datasets and adopting the analytical approach of social sciences. As a testament to my proactive approach to learning, I even independently acquired proficiency in game development, resulting in the publication of a game. I am now fully prepared to extend my skill set into the realm of healthcare.

## At least 3 years of experience in data mining, data analysis, or a related field

Due to my interdisciplinary background, I have performed statistical analyses in both the field of natural science, such as observing black holes, and social science, like assessing gender biases in funding applications. Considering my journey from the start of my master’s research, I can proudly claim 6 years of invaluable experience. The diverse projects I’ve been involved in have granted me exposure to a wide array of methodologies in data analysis. These encompass techniques ranging from SQL, regressions, Bayesian models, network analysis, and machine learning.

#  Quality assurance and validation of performance data.
#  Trend analysis.
#  Preparation of Performance Reports, both internal and external facing.
#  Presentation of data and analysis to best suit environment / individuals requirements.

My current institution specializes in the field of bibliometric analysis, which involves evaluating the performance of academic scholars. To ensure the accuracy of our data, I possess expertise in data cleaning, employing random sampling followed by manual verification, conducting exploratory analysis, validating findings through comparison across various data models, and utilizing external databases to corroborate specific datasets.

Examining trends within the realm of scientific publications constitutes a regular aspect of our data-related tasks. On occasion, straightforward descriptive analysis suffices. Alternatively, we leverage advanced machine learning models to prognosticate trends. Given the intricate nature of our dataset, we also employ methodologies like network analysis and natural language processing to unearth more profound patterns inherent in these trends.

I have authored several academic publications, which have fostered a deep familiarity with composing technical reports. In order to elucidate intricate concepts for the general public, I have also engaged in crafting documentation and blogs that explain complex technical aspects using accessible language.

Conducting numerous presentations has honed my ability to tailor content for diverse audiences. For instance, I have showcased a software I developed to audiences comprising scientists, social scientists, software engineers, and non-technical individuals. While meeting everyone's needs can prove challenging at times, I consistently garner commendation for my presentation skills.

# Experience of Adastra Clinical Patient Management System

Although I lack prior experience with this particular software, I conducted a brief Google search and stumbled upon a helpful resource - a guide available at the following link:
https://www.oxfordhealth.nhs.uk/training/adastra-quick-guide/

With my technical background, I am confident in my ability to grasp the system's knowledge independently.

# Bloomberg: Please outline in no more than a 100 words the most relevant skills and experience you have for the specific role you are applying for
My background in game development and research has equipped me with strong technical skills in data analysis and software development. During my PhD journey, I collaborated with individuals from diverse backgrounds and nationalities, honing my soft skills in communication, teamwork, and cross-cultural engagement. I have a proven track record of delivering effective presentations and organizing workshops, catering to both technical and non-technical audiences. My interdisciplinary educational and research background reflects my ability to rapidly acquire knowledge in new domains, and I'm eager to bridge any knowledge gaps in finance required for this position.

