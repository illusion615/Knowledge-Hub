# AI Business Solution - Knowledge Hub
The knowledge hub solution based on Power Platform to leverage low code to implement a knowledge library solution to provide accurate and tunable knowledge management and query solution.

## Prerequisites

## License/Products Required

| Name | Purpose | Must Have | Suggest Quantity |
|--------------|---------|-----------|-----------------|
| Power Apps Premium | For IT admin, developer and knowledge manager | Yes | 3+ |
| Power Pages | Web portal interface | Optional | 1 |
| Power Automate Process | For backend automation flow instances | Yes | 5 |
| AI Builder Credits | For knowledge building process | Yes | 1+ |
| Copilot Studio Messages | For orchestration and knowledge Q&A | Yes | 2+ |
| Azure Function | To host the file processing code | Yes | by consumption |
| Azure Blob Storage | To store the file and images | Yes | by consumption |
| Microsoft SharePoint site | For multiple file type convention support | Yes | 1 |

### Permissions Required
- Power Platform admin or D365 admin
- Azure Application Admin

### Environment Requirements
- **Development Environment**
   - Region: US or Europe (based on developer location)
   - Language: English
   - Type: Sandbox

- **Testing/QA Environment**
   - Region: Same as target production region
   - Language: English
   - Type: Sandbox

- **Production Environment**
   - Region: US or region closest to most users
   - Language: English
   - Type: Production

## Deployment Steps
The compelted deployment video guidance could be found here:
![Deployment Video](Video/Deployment.mp4)
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
![Operation Manual](Video/User%20Manual.mp4)