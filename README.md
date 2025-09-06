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

### Navigate to Users
## Step 2: User List After Creating DevUser and ViewUser

![User List](./screenshots/Screenshot%202025-09-04%20120524.png)





### Step 3: DevUser User Administrator Role for Group

![User List](./screenshots/Screenshot%202025-09-04%20121033.png)
### Step 4: ViewUser assigning the Directory Reader Role for Group
![User List](./screenshots/Screenshot%202025-09-04%20121233.png)




---
###Step 5: Permissions and Limits logged in as ViewUser 

## Could not edit any user information
![All Users After](./screenshots/Screenshot%202025-09-04%20122403.png)

## Could not be able to reset my own or any other user password

![All Users After](./screenshots/Screenshot%202025-09-04%20122654.png)


##Step 6: Permissions and Limits logged in as DevUser(developer)

## Logged in as DevUser created a user named TestUser1
![All Users After](./screenshots/Screenshot%202025-09-04%20130735.png)

## Reset the password for TestUser1 as DevUser
![All Users After](./screenshots/Screenshot%202025-09-04%20130921.png)


## Key Takeaways
- Learned user & group management in Entra ID.  
- Practiced RBAC and least-privilege.  
- Documented login tests for role validation.
