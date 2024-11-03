# Setup an Individual User

## Specify User Details:  
IAM --> Users --> "Create User "
- Specify User Details:
    - User Name: Miray
    *Check the "Provide access to COnsole" choice.*  

 it would appear 2 choices:  
  - Specify a user in identity Center
  - I want to create an IAM USer_  (We ll choose this option)
> Recommended to check that user must change his pasword after first login  

--->>> Next

---- 

## Set Permissioosn

- Choices:
1. Add suer to group
2. Copy Permission
3. Attach policies directly

- Permission Boundry: default  

*We ll leave all settings by default*
--->>> Next

--- 
## Review and Create
--->>> Create User
*At this point we can copy the user name  and password.*  

## Creating a group

***By default no permission assigned to user. For permission we must explicitely assign by attaching polycies.***

IAM--> User Groups --> "Cretae a Group"  

- Name the Group: Admin  
- Add users to group : leave  as default
- Attach Permissions Policies : Adminsitrative Access  

--->>> Create Group   
*Now we can add users ti this group.*   

## Add Users to group  

IAM --> User groups --> "Admin" --->>> Add Users

*Now we ave addes miray to administratroup
