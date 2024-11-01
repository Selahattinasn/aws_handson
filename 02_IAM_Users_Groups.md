### IAM User and Groups

IAM --> Users -->  ***Here we see the users accounts.*** 

First We make a Group, then assign Permission by attaching ROles or Policies and then add user in this group;  user woud inherit the permission for the group.

#### Creating a Group and Attaching Admisitrative Policies

IAM--> User_Groups--> "Create User Groups:
- Name teh Group: Admins
- Add User to  Group: - 
- Attach permission policies: "Adminsitrator Access" 

-->>> Create Group


---- 

#### Creating User

IAM--> Users--> "Create User"

- User Name:  Mirmiray 
        Check here  the "Provide user access to the AWS Management Console" (Actually its optional) By doing that we can also ccess  via  Console, not just via programmatic access.

***At this point 2  Options for User Type  will appear.*** 
- Specify User in Identity Center
- I want to create an IAM User ;  --> We ll chec this options

***and here it will appera the configs for password for the potential Users***

- Consoel Password:
    - Auto Generate Pasword
    - Custom Password --> Better oprion
    Check the option "User Must Create a new password after next  login"
--->>> Next


---- 
Set Permissions:
- Permission Options : "Add User A Group", [""Copy permisss", "Attach policy directly"]
- User Groups: ***Here we can select groups of the choices" In our case this is "Admins" group the only one. 
- Set Permission Boundry: Def

--->>> Next

----
Review and Vreate:
- User Details 
- Permission Summary
- Tags

--->>> Create User

----
!!! At this point we can copy the "Console sign in details: 
- Sign in user URL
- User name
- Password
-->>>>  REturn to users list
***Now we can login with this new User"***
 ---- 

##  Theme - Troubleshooting about credentials

### Step 1 - What if you forget the password 

- Click User>>>>> Select user---->>Security Credential--->> Console Password---> Click "Manage"--->>Set  password >>>> Custom password

### Step 2-  What if you forgot your secret access keys key 

  Click User>>>>> Select user---->>Security Credential--->> Go Access keys ---> Deactivate---->> Delete --->>>Create new 

    