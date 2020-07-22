
<h1>Configure Microsoft Teams</h1>

<h2>Scenario</h2>
<p>You are the Microsoft 365 Teamwork Administrator for the organization CodeSizzler. You are responsible for Microsoft Teams administration. You are tasked with configuring users and groups so your organization can use Microsoft Teams.</p> 
<p>CodeSizzler wants to allow employees to create teams and channels as well as use any first party apps in Microsoft Teams. CodeSizzler does not want anyone using DropBox or Google Drive for cloud storage with Teams. They also want to prevent certain 3rd party apps from being used with Teams. At first CodeSizzler will adopt Microsoft Teams for their senior leadership and Revenue organization.</p>

<h2>Note:</h2>
<p>To solve this scenario you need to be the admin of your O365 Admin Center and Teams Admin Center to work on this lab.</p>

<h2>Exercise 1: Create Groups and Assign Users</h2>
<p>In the Microsoft 365 (portal.office.com) screen click the Admin icon. </p>
<img src="https://csgithub.blob.core.windows.net/configureteams/1.png"/>
<p>In the Microsoft 365 Admin center hover over the Group icon and click Groups.</p>
<p>In Home > Groups screen click + Add a group.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/2.png"/>
<p>Select Microsoft 365 as group type and go for the basics blade where you will be naming the group along with description.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/3.png"/>
<p>4.In the Add a group dialogue box in the Type field select Office 365. In the Name field type Senior Leaders and go for the Owners blade.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/4.png"/>
<p>Add any of your tenant whom you wish to be the owner for “Senior Leaders” group, here in my case am adding Mohammed Imthiyas as owner for this Senior Leaders group.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/5.png"/>
<p>In the Group email address field verify that seniorleaders@<your tenant domain here> appears. In the Privacy drop-down select Private. Click Next.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/6.png"/>
<p>Finally review the details which you have given for the group and click on “Create group” to get it created.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/7.png"/>

<h2>Task 2: Create an Office 365 group for the revenue team</h2>
<p>In the Microsoft 365 Admin center hover over the Group icon and click Groups. </p>
<p>In Home > Groups screen click + Add a group.</p>
<p>Select Microsoft 365 as group type and go for the basics blade where you will be naming the group along with description.</p>
<p>In the Add a group dialogue box in the Type field select Office 365. In the Name field type Revenue and go for the Owners blade.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/8.png"/>
<p>Add any of your tenant whom you wish to be the owner for “Revenue” group, here in my case am adding Mohammed Imthiyas as owner for this Revenue group.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/9.png"/>
<p>In the Group email address field verify that revenue@<your tenant domain here> appears. In the Privacy drop-down select Public. Click Next.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/10.png"/>
<p>Finally review the details which you have given for the group and click on “Create group” to get it created.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/11.png"/>
<p>So now you can find both the blades “Senior Leaders” and “Revenue” on Groups as shown below:</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/11-12.png"/>

<h2>Exercise 3: Get Started with Teams</h2>
<h2>Task 1: Configure Microsoft Teams</h2>
<p>In the Microsoft 365 admin center and go for Teams Admin Center.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/12.png"/>
<p>In the Microsoft Teams admin center screen expand Teams Apps. In the Manage Apps area search for Avochato and Beanstalk, block the app status</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/13.png"/>
<img src="https://csgithub.blob.core.windows.net/configureteams/14.png"/>
<p>Now, turn off Google Drive and Dropbox in Microsoft Teams and Skype for Business Admin Center under Org-Wide Settings --> Teams Settings, goto Files and turn off DropBox and Google Drive. In the Microsoft Teams screen click Save. Click Close. Or close the Microsoft Teams & Skype for Business Admin Center if you have that open.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/15.png"/>

<h2>Task 2: Launch Teams and Create a Team</h2>
<p>While still logged in to Microsoft 365 with yoru admin account, click the 9-dots icon in the upper left corner and then click Teams.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/16.png"/>
<p>Several educational dialogue boxes may appear, read them and click Next several times until it says You’re ready! And then click Let’s go.</p>
<p>In Microsoft Teams click Join or create a team.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/17.png"/>
<p>In the Join or create a team area click Create team.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/18.png"/>
<p>In the Create team dialogue box select Build a team from scratch.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/19.png"/>
<p>Change Privacy to Public – Anyone in your organization can join</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/20.png"/>
<p>In the Create team dialogue box in the Team name field enter IT Support. In the Description field enter: Team for CodeSizzler employees that need IT support. And click Create.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/21.png"/>
<p>In the Add members to “IT Support” dialogue box type the member name whom you want to add and click on Add.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/22.png"/>
<p>Now search for revenue and select that group from the lookup. Click Add. Click Close.</p>
    <p>1.	In the Microsoft Teams screen click on the General channel under IT Support. Click in the Start a new conversation... box and type: Hi everyone, I created this team to be a self-service IT support portal. And then press the Enter button.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/23.png"/>

<h2>Task 3: Enable Guest access for Microsoft Teams</h2>
<p>While still logged in to Microsoft 365 as administrator go to the Microsoft 365 Admin center. If you need to open a browser and enter the following URL to access the Microsoft 365 admin center: portal.office.com and enter your admin credentials.</p>
<p>In the Microsoft 365 admin center hover over settings and click Org settings, select Microsoft Teams and here is where you can allow permissions for adding members who are outside of your organization to the teams channel.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/24.png"/>
<p>In the Home > Services & add-ins screen click Microsoft Teams. Click Microsoft Teams & Skype for Business admin center. In the Microsoft Teams & Skype for Business Admin Center click Org-wide settings and then click Guest access. Set Allow guest access in Microsoft Teams to On. Click Save.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/25.png"/>

<h2>Task 4: Create a Team from a Group and add an owner</h2>
<p>In the browser click Switch to a different account. Sign in with the member which you have added.</p>
<p>You may have to click through some educational prompts. Eventually, you will be able to close that screen.</p>
<p>In the Office 365 portal click the Teams icon. You may have to switch users from Admin the  new account which you have added.</p>
<p>You will be presented with an informational screen, close this screen.</p>
<p>In Microsoft Teams click Join or create a team. Click Create team.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/26.png"/>
<p>In the Create your team dialogue box click Create a team from an existing Office 365 group.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/27.png"/>
<p>In the Choose your team dialogue box select the Senior Leaders group and click Choose team.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/28.png"/>
<img src="https://csgithub.blob.core.windows.net/configureteams/29.png"/>
<p>Imthiyas has decided that he wants Feroz to be the Teams admin to be a co-owner of the Senior Leaders team in Microsoft Teams so you can be a backup administrator of the team. In Microsoft Teams click the Teams tab.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/30.png"/>
<img src="https://csgithub.blob.core.windows.net/configureteams/31.png"/>
<img src="https://csgithub.blob.core.windows.net/configureteams/32.png"/>
<p>Click the ellipses next to the Senior Leaders team and click Add members.</p>
<p>In the Add members to Senior Leaders dialogue type the administrator email in the box and select it and click Add. In the drop-down box for Administrator choose Owner. Click Close.</p>
<img src="https://csgithub.blob.core.windows.net/configureteams/33.png"/>
<img src="https://csgithub.blob.core.windows.net/configureteams/34.png"/>
