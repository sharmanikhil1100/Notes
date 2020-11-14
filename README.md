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
    4. Setting up AWS cli - <br/>
        * Download aws cli for ubuntu using 3 commands given in the course video. <br/>
        * You are ready to go. <br/>
        * Start using aws cli after doing this - [Screenshot here](https://ibb.co/XDFK3tQ) <br/>
    5. Assign roles to Services - <br/>
        * Some aws service needs to be performed on your behalf. <br/>
        * To do so we will assign permissions to aws services using IAM roles. <br/>
    6. Security Tools - <br/>
        * 'Access Advisor' shows the services that this user can access and when those services were last accessed. >br/> Review this data to remove unused permissions. <br/>
    7. IAM best practices - <br/>
        * Check out the slides (pg 49) <br/>
    9. Shared Access Responsibility Mode - <br/>
        * Check out the slides (pg 50) <br/>
    * Don't miss the summary video to get idea of IAM !!
          
2. EC2 Elasctic Cloud Compute - <br/>
    1. AWS budget Setup - <br/>
        * Setup up cost alerts from IAM user accounts. <br/>
        * Grant access first to the IAM users. <br/>
        * Check the bills, costs, budgets, etc. from navbar.
    2. EC2 Instance Examples - <br/>
        * You have different options to choose for EC2 Instances.
        * Different Storage, Network, Processing, RAM, etc configurations to choose for you EC2 instance.
