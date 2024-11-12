# Employee Onboarding flow using power automate
## Overview

This project showcases an automated Employee Onboarding process built with Power Automate. The flow streamlines the onboarding process from capturing new employee details through Microsoft Forms, generating approvals, and automating user creation in Azure Active Directory, to assigning tasks in Planner and notifying the new employee.

## Workflow Details
- Initiated by a new response submission in Microsoft Forms then obtains an access token to interact with Azure Active Directory securely.And sends an approval request to the appropriate team/manager to confirm the new hire.

![image](https://github.com/user-attachments/assets/ee998c37-4e2d-4d22-87de-c813eed1ec2d)

![image](https://github.com/user-attachments/assets/1f77ed5a-15d3-4638-9ba1-af18c31fcc37)

- If approved creates a set of onboarding tasks for the new employee in Microsoft Planner.

![image](https://github.com/user-attachments/assets/c7e789f2-38ea-454f-86cd-f3e23aa4dc21)

-  Creates a new user in Azure Active Directory (Azure AD) using the details from the form.

  ![image](https://github.com/user-attachments/assets/1ad069e9-d0bb-494e-8539-f7e9bee28be5)

- Retrieves available license details and assigns the appropriate licenses to the new user.

  ![image](https://github.com/user-attachments/assets/c953ea16-d269-45c6-8b09-3fbe8b4c1bf9)

- Fetches the organization's calendar and assigns it to the new employee, ensuring their schedule is up to date.

![image](https://github.com/user-attachments/assets/d9ddc9aa-7c47-4ff4-9574-69343da28099)

- Sends a notification to the new employee with their account details and instructions to get started.

  ![image](https://github.com/user-attachments/assets/d0ea32d4-a1e6-4297-9290-42112183b699)

