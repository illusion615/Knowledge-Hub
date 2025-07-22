# AI-Business-Solution---Knowledge-Hub
The knowledge hub solution based on Power Platform to leverage low code to implement a knowledge library solution to provide accurate and tunable knowledge management and query solution.

## Prerequisites

## License Required
- Power Apps Premium(for IT admin, developer and knowledge manager)
- Power Pages(Optional, if )
- Power Automate Process(5 process license for certain backend automation flow instances)
- AI Builder Credits(Necensarry AI credits for knowledge building process)
- Copilot Studio Messages(Necensarry message capacity for orchestration and knowledge Q&A)
- Azure Function(To host the file processing code)
- Azure Blob Storage(To store the file and images)
- Microsoft SharePoint site(for multiple file type support)

### Permissions Required
- Power Platform admin or D365 admin
- Azure Application Admin

### Environment Requirements
- Region: US
- Language: English
- Type: Sandbox

## Deployment Steps

1. **Deploy Azure Blob**

2. **Deploy Azure Function**
   - Extract the AzureFunction.zip code

3. **Create Environment and Configuration**

4. **Create Power Pages Site**

5. **Create SharePoint Site and List**

6. **Import Solution Packages**
   - Import solutions numbered 1, 2, and 3 in sequence. Ensure each solution is fully completed before importing the next one.

7. **Import Solution #4**
   - This step includes many environment variables. Please follow the instructions shown in the video.

8. **Import Solution #5**
   - In the environment variables, make sure to enter the Instant URL for this environment.

9. **Import Solution #6**
   - Similarly, in the environment variables, make sure to enter the Instant URL for this environment.

### Post-Import Steps

10. **Publish All Customizations**

11. **Publish Copilot Studio**

12. **Upload Documents and Complete Testing**

13. **Feature Walkthrough**
