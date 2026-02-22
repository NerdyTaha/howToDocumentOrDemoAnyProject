# A guide on how to document and demo a project. 
(Disclaimer: This is solely based on my experience and intuition)
---
- While building end-to-end projects, either solo or with a team, good docs help you and your team. Even git commits should be well written.
- So, as a solo dev, wrapping your mind across the entire project can get hard (coz ur context window is small twin..lol)
### DEMO of your project:
- Demo of a project is delivered to clients (technincal/non-technical) or other Engineers (team or seniors) or maybe to just your friends lol.
#### **ATTENTION IS EVERYTHING:** DONT TALK, show. Make flowcharts/Diagrams to visualise your pipeline/system's functioning. 
- Showing your UI and functioning backend is necessary - that is usually sufficient for non-technical folks but not for nerds and geeks. Engineers would dive deep into high and low level system desing, trade-offs, orchestration between different components, etc.
- In order to explain all this, you may have to make diagrams, explain a module/file or a code-block, overall flow of a file and how it's used by other files etc.
- To solve this, I make 4 markdown files -- which is not something new because people have been using it but here is how I design a consitent documentation sytem which helps me as an engineer building stuff end to end:
- readme.md, code_docs.md, changelog.md, dev_logs.md : these are the 4 files to make. 

## readme.md 
1. This includes the description of your project. What is it, what problem it solves, what is needed to use/run this project.
2. Any technical/non-technical person after reading this should get an idea if they need this project or not and how to get it running. 
## code_docs.md 
1. This is the main technical documentation out of all 4 files. 
## changelog.md
1. Traditional changelog.
2. 
## dev_logs.md
1. Simple past tense developer logs of what was done. Include plans. 
##### In this way, all documentation/development-context stays in the root of the repo. There can be external docs, diagrams, task management, etc but the above 4 files can be enough for anyone to pick up the project, learn about it and do whatever they want with it. 

# rough for taha:
- add images ss of these files as examples (alt image ./subdir) -- keep images within the repo. 
