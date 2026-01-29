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
     Roles / Groups:
  - **HR Manager** – Full control
  - **HR Staff** – Edit, limited access
  - **Finance Team** – Read-only for some libraries
  - **All Employees** – General read access
    
## Roles & Permissions

| Library                  | HR Manager | HR Staff | Finance Team | All Employees |
|---------------------------|------------|---------|--------------|---------------|
| Policies & Procedures     | Full       | Edit    | Read         | None          |
| Forms & Templates         | Full       | Edit    | Read         | Read          |
| Employee Records          | Full       | Edit    | None         | None          |
