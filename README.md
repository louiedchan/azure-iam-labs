# azure-iam-labs
Hands-on labs in Microsoft Azure Entra ID (IAM, RBAC, users, groups, least privilege
# Lab 1: Tenant-Only IAM Setup

## Objective
Simulate an IAM environment in Azure Entra ID:
- Create users and groups
- Assign directory roles
- Test least-privilege access

---

## Steps I Completed
1. Created a new Entra tenant.  
2. Created `DevUser` and `ViewUser`.  
3. Built a security group (`DevelopersGroup`).  
4. Assigned roles:
   - `User Administrator` → DevUser
   - `Directory Readers` → ViewUser  
5. Logged in with test accounts to validate permissions.

---

## Screenshots
## Step 2: Create Users

### Navigate to Users
## User List After Creating DevUser and ViewUser

![User List](./screenshots/Screenshot%202025-09-04%20120524.png)


### Creating DevUser


### DevUser User Administrator Role for Group

![User List](./screenshots/Screenshot%202025-09-04%20121033.png)
### ViewUser assigning the Directory Reader Role for Group
![User List](./screenshots/Screenshot%202025-09-04%20121233.png)

### All Users List
![All Users After](./screenshots/all-users-after.png)


---

## Key Takeaways
- Learned user & group management in Entra ID.  
- Practiced RBAC and least-privilege.  
- Documented login tests for role validation.
