## Access Amalyzer

at first time, Access Analyzer needs to be enabled.       

We can see here some findings, 
![IAM7](images/IAM7.png)

if we clich on a findeing we ll see detailed informastion. 

![IAM8](images/IAM8.png)

So this is analyzing access and providing these findings which might warn you about potentially something that's too open, that's allowing more access than you might want it to.  

There's archive rules here about how you archive.

You can see the analyzers here as well.

You can create new analyzers.

And in the settings here you can see the access analyzer administrator and you can optionally add a

delegated administrator as well.

![IAM9](IAM9/IAM9.png)

-----

## Credential Reports

we can dolwnload report  
![IAM10](IAM10/IAM10.png)

it look somthing so 
![IAM11](IAM11/IAM11.png)

Quite a bit Infor tounderstahnd how user is setted for security perspective. 


----


## Policy Simulator

![IAM12](IAM11/IAM12.png)


## Policy Generator

ROles --> "Select a role" --> 

![IAM13](IAM11/IAM13.png)
*at this point we see multiple policiwes appliad to this role*

*at the bottom see the button fo "Generate Poliy"*

This geremates policy based on "cloud trail" evenss. 

Steps: 
1. Choose a time frame: 
![IAM14](images/IAM14.png)
2. Choose trail
![IAM15](images/IAM15.png)
3. Specify Region
![IAM16](images/IAM16.png)
4. we can choose an existing sercive roleto generate policy
![IAM17](images/IAM17.png)
5. Clik on "Generate Ploicy

for exmple tehis is  a generated poliy:
![IAM18](images/IAM18.png)
lets view it 
![IAM19](images/IAM19.png)
in the review  we can see teh applicable actions 
![IAM20](images/IAM20.png)
after two times clicking on next, we can see the policy json  template. We can customize it through editor. 
![IAM21](images/IAM21.png)
