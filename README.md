# Notes - AWS Cloud Practitioner - Stephane Maarek

After setting up the free-tier AWS account :

1. IAM (Identity and Access Management) 
    1. Create a user - <br/>
        * Give it AdministratorAccess policy<br/>
        * Put him in admin group<br/>
        * Use this account further for any aws work<br/>
    2. Review policy - <br/>
        * Click on policy in side menu. You will get a list of pre exisiting policies<br/>
        * You can choose from them or create your own custom one as well
         [Screenshot here](https://ibb.co/ySK1pN1)<br/>
    3. Passwords and MFA - <br/>
        * Setup password policies for all user from dashboard <br/>
        * Optionaly, setup MFA for high security. (Advisable not to be imposed on Root user, as it may lock the access of acc in worst case)<br/>
        * MFA = Password + Device check
          
