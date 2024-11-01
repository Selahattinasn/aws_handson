### IAM USer and Groups

IAM --> Users -->  ## Hier we see the users accounts. 
***First We make a Group, then assign Permission by attaching ROles or Policies and then add user in this group,;  user will inherit the permission for the group. *** 

#### Creating Group and Attaching Admisitrative Policies
IAM  --> User_Groups--> "Create User Groups:
    - Name teh Group: Admins
    - Add User to  Group: - 
    - Attach permission policies: "Adminsitrator Access" 
                    -->>> Create Group

*** Now we habe in Group with Adminsitrator Permissions attached to it.***

#### Creating User

IAM --> Users --> "Create User" : 
    - User Name:  Mirmiray 
        Check heer the "Provide user access to the AWS Management Console" (Actually its optional) By doing that we can access also via  Console only programmatic access.
---
        At this point 2  Options for User Type  will appear. 
          + Specify User in Identity Center
          + I want to create an IAM User ;  --> We ll chec this options

          ***The it will appera the configs for password for the potential Users***

          - Consoel Password:
            + Auto Generate Pasword
            + Custom Password --> Better oprion
                Check the oprion "USer Must Create a new password after next  login"
           
                    --->>> Next

    ---- 
    Set Permissions:
    - Permission Options : "Add User A Group", [""Copy permisss", "Attach policy directly"]
    - User Groups: ***Heer we can select groups of the choices" In our case this is "Admins" group the only one. 
    - Set Permission Boundry: - 
                --->>> Next
    ----
    Reeview and Vreate:
    - User Details 
    - Permission Summary
    - Tags
                --->>> Create User


    