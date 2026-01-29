# Sharepoint-permission-management
A SharePoint site demonstrating role-based permissions and secure file access for HR and Finance teams.

## Purpose
- Practice core SharePoint Admin tasks.
- Demonstrate understanding of security and access management.
- Show recruiters I can protect company data and manage user access.

## Site Structure
- **HR Department Portal**
  - Policies & Procedures (Sensitive)
  - Forms & Templates (General)
  - Employee Records (Highly Sensitive)
  
    
## Roles & Permissions

| Library                  | HR Manager | HR Staff | Finance Team | All Employees |
|---------------------------|------------|---------|--------------|---------------|
| Policies & Procedures     | Full       | Edit    | Read         | None          |
| Forms & Templates         | Full       | Edit    | Read         | Read          |
| Employee Records          | Full       | Edit    | None         | None          |

## Step-by-Step Build

1. **Created SharePoint Site**
   ![Site Home](screenshots/site-home.png)

2. **Created Document Libraries**
   ![Libraries](screenshots/libraries.png)

3. **Configured Unique Permissions**
   ![Permissions](screenshots/permissions.png)

4. **Created SharePoint Groups**
   ![Groups](screenshots/groups.png)

5. **Uploaded Sample Files**
   ![Files](screenshots/files.png)

6. **Tested Access**
   ![Access Test](screenshots/access-test.png)
   
## Outcome
- Role-based permissions work correctly.
- Sensitive HR data is protected.
- Demonstrates core SharePoint admin skills.
