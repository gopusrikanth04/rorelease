# Improvements

1. Dashboard
   1.  Added Pipeline Stage and Pipeline Status details to the Release Pipeline Cycles table on the dashboard.\


       <figure><img src="../.gitbook/assets/image (2) (1) (1).png" alt=""><figcaption></figcaption></figure>
2. Change Management > User Stories
   1. Added a column-level filter (select from menu) for User Story Type in the User Stories table.
   2.  Added Modified By and Modified On columns in the User Stories table.\


       <figure><img src="../.gitbook/assets/image (1) (2).png" alt=""><figcaption></figcaption></figure>
   3.  Added ALM Integration and Sprint columns to the Sync History table.\


       <figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>
3. Build > Transport Management
   1. Added a column-level filter (selectable from the menu) for Transport Type, Status, and Last Imported System in the Transport Management.
   2.  Added Excel download functionality in Transport Management to export all transport details.\


       <figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>
   3.  In gCTS Transport Management, the file list is now displayed when clicking on a Commit ID in Commits for transport request.\


       <figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>
   4. Added TOC request details in the Transport Management Import History.
4. Build > API Management
   1. The values in Encrypted Key Value Maps (KVMs) are now displayed based on the type of Key Value Map. If the KVM is encrypted,      \
      the values will be securely stored and displayed in an encrypted format. For plain text KVMs, the values will be shown in readable text.
5. Build > Build Pipeline
   1. Enhanced the build pipeline by integrating **Version Control Platform input** at the time of creation.      \
      This enables seamless navigation to commits and facilitates other version control-related operations.
6. Release > Release Pipeline
   1.  Added a Notify option to notify users in the wait for Promotion Task.\


       <figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>
   2.  Added a Description field to all tasks in the Release Pipeline to provide detailed information about each task.\


       <figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>
   3.  Enhanced validation for task names in the release pipeline to allow only alphanumeric characters, hyphens (-), underscores (\_), and periods (.),       &#x20;while restricting all other special characters.\


       <figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>
7. Pipeline Activity
   1. Hiding the rollback button after the rollback is completed for CPI deployment in the pipeline activity.
   2. Added ToC ID details in the On-Premise deployment log.
   3.  Enhanced the Deployment Task in Pipeline Activity to display retry details, like Last Retry By and Last Retry On for better tracking and visibility.\


       <figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>
   4. Added transport type details to On-Premise deployment logs for improved clarity and understanding.
   5.  Enhanced Integration Advisor Deploy Logs to display Consistency Check Logs and Import Logs, ensuring better visibility and traceability during deployments.\


       <figure><img src="../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

       <figure><img src="../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>
8. CPI Test Generator
   1.  Added the "Last Test Results" and "Test Runs" to the action button of Test Suite.\


       <figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>
   2.  Added the "Last Test Results" and "Test Runs" to the action button of Test Case.\


       <figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>
   3. Added new columns to the message table in test case creation: messageType, multicastIndex, splitIndex, branchId, and childCount.
   4.  Added Excel download functionality for CPI test results.\


       <figure><img src="../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>
   5. Added "Commit ID" and "Branch" columns to the Update History.
   6. Added Artifact Version and Test Suite columns to the Test Run Results.
   7. Added support to display the Mock Endpoints field in the CPI Test Case View.
   8. Added Artifact Version and Mock Run in Test Run Details
   9. Display of headerProps for CPI messages in test run details. The test run details now include headerProps for CPI messages,      &#x20;providing better visibility into message headers and improving debugging capabilities.
9. ALM Integration
   1. The integration does not allow updates after creation in project settings. Currently, updates are only enabled for "Jira JQL" and "Disable writing comments/notes".
   2. "Disable writing comments/notes" : Added a checkbox option to enable or disable automatic comment writing on Jira user stories
   3. Added the Web Request URL field for automation rules. After creating a new ALM integration, this field is automatically populated.
10. Administration > Environments
    1.  Label changed from "IFlow API URL" to "IFLOW URL" in CPI environment creation.\


        <figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>
11. Administration > Static Code Analysis > CPI Rules
    1.  Enhanced CPI lint functionality to consider allowed user role values, improving test case execution efficiency.\


        <figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>
