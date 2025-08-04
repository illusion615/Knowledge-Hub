# AI Business Solution - Knowledge Hub
The knowledge hub solution based on Power Platform to leverage low code to implement a knowledge library solution to provide accurate and tunable knowledge management and query solution.





## Deployment Steps
The compelted deployment video guidance could be found here:
![Deployment Video](Video/Deployment.mp4)
1. **Deploy Azure Blob**

2. **Deploy Azure Function**
   - Extract the AzureFunction.zip code

3. **Create Environment and Configuration**

4. **Create Power Pages Site**

5. **Create SharePoint Site and List**

6. **Import 3rd Party Solution Components**
   - Creator Kit(The latest version can be download here: https://learn.microsoft.com/en-us/power-platform/guidance/creator-kit/overview)
   - Import solutions numbered 1, 2, and 3 in sequence. Ensure each solution is fully completed before importing the next one.

7. **Import Solution #4**
   - This step includes many environment variables. Please follow the instructions shown in the video.

8. **Import Solution #5**
   - In the environment variables, make sure to enter the Instant URL for this environment.

9.  **Import Solution #6**
   - Similarly, in the environment variables, make sure to enter the Instant URL for this environment.

### Post-Import Steps

10. **Publish All Customizations**

11. **Publish Copilot Studio**

12. **Upload Documents and Complete Testing**

13. **Feature Walkthrough**
![Operation Manual](Video/User%20Manual.mp4)

# Knowledge Hub Solution
The enhanced knowledge hub solution based upon Power Platform to provide a business user participant knowledge lifecycle management application.

# Objectives
Knowledge Hub solution is aims to resolve below challenges during enterprise building their LLM knowledge solutions.
1. **Turn black box into white box**: There is just few way even no way to do when the out-of-the-box knowledge features of Copilot Studio can't provide an acceptable knowledge query accuracy.
2. **Business user friendly knowledge lifcycle management**: Business user not able to participants into the knowledge lifecycle management as it's usually too technically and hard to udnerstand.
3. **Flexible architecture to integrate with wider source of knowledge**: The knowledge usually narrow down to documents rather than wider data sources(internal, and external)
# Solution Features
![alt text](Docs/Architecture/Solution%20Highlights.png)
# Architecture
![alt text](Docs/Architecture//Architecture%20Diagram.png)

RAG method and Power Platform implementation
![alt text](Docs/Architecture/RAG%20implementation.png)

# Agenda
## [License Required](Docs/License%20Required.md)
## [Change Log](Docs/Change%20Log.md)
## [Deployment Guide](Docs/Deployment%20guide.md)
## License
This project is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
