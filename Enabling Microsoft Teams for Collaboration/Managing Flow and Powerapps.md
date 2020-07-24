<center><h1>Managing Flow and PowerApps</h1></center>

<h2>Lab scenario</h2>
<p>You’re the Teamwork Administrator for CodeSizzler. There’s a collaboration solution configured and deployed using apps in Microsoft Office 365. A user Lee Gu has requested help configuring a flow to save email attachments to Microsoft OneDrive for Business. After configuring this, you need to create a data loss prevention policy to ensure that Microsoft Flow and Microsoft PowerApps don’t send Microsoft SharePoint Online and Microsoft Dynamics 365 data outside of the organization.</p>
<p>In this lab, you will manage Flow and PowerApps capabilities.</p>

<h2>Exercise 1: Configuring a flow (10 minutes)</h2>
    <p>•	Task 1: Sign in to Office 365</p>
    <p>•	Task 2: Create a flow from a template</p> 
    <p>•	Task 3: View settings for a flow</p>

<h2>Exercise 2: Testing a flow (10 minutes)</h2>
    <p>•	Task 1: Send an email with an attachment</p>
    <p>•	Task 2: Sign in to Office 365 as Lee</p>
    <p>•	Task 3: Verify the flow results</p>

<h2>Exercise 3: Managing Flow and PowerApps (5 minutes)</h2>
    <p>•	Task 1: Sign in to Microsoft 365 admin center as Admin</p>
    <p>•	Task 2: View Flow quotas and licenses</p>
    <p>•	Task 3: Configure a data loss prevention policy</p>

<h2>Exercise 1: Configuring a flow (10 minutes)</h2>

<h3>Task 1: Sign in to Office 365 with www.portal.office.com </h3>

<h3>Task 2: Create a flow from a template</h3>
<p>1.	In Microsoft Office Home, under Apps, select Explore all your apps. </p>
<p>2.	Scroll down and under All of your apps, select Flow. </p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/1.png"/>
<p>3.	On the Flow page, in the navigation pane, select My flows.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/2.png"/>
<p>4.	In the Welcome to Microsoft Flow window, in the Choose your country/region box, select United States, and then select Get started.</p>
<p>5.	In the Flows area, select New and go for Create from templates.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/3.png"/>
<p>6.	In the search box, type Save Office 365 email attachments to OneDrive and press Enter.</p>
<p>7.	Select Save Office 365 email attachments to OneDrive.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/4.png"/>
<p>8.	Review information about the flow and then select Create Flow.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/5.png"/>

<h3>Task 3: View settings for a flow</h3>
<p>1.	In the navigation pane, select My flows.</p>
<p>2.	In the Flows area, for Save Office 365 email attachments to OneDrive for Business select Edit.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/6.png"/>
<p>3.	Review the steps listed and then close your web browser.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/7.png"/>

<h2>Exercise 2: Testing a flow (10 minutes)</h2>

<h3>Task 1: Send an email with an attachment</h3>
<p>1.	On the Microsoft Office Home page, in the Apps area, select Outlook.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/8.png"/>
<p>2.	In Outlook, select New.</p>
<p>3.	In the To box, type the user email id for whom the mail has to be sent.</p>
<p>4.	In the Subject box, type Flow demo.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/9.png"/>
<p>5.	At the bottom of the message window, select Attach and then select Cloud locations.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/10.png"/>
<p>6.	Select the attachment of which you wish to add and then select Next.</p>
<p>7.	Select the down arrow in the attachment and select Attach as copy.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/11.png"/>
<p>8.	Select Send.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/12.png"/>
<p>9.	Close your web browser.</p>

<h3>Task 2: Sign in to Office 365 with the user account to whom you have sent the email</h3>
<p>1.	Open your web browser.</p>
<p>2.	In your web browser, open the website https://login.microsoftonline.com.</p>

<h3>Task 3: Verify the flow results</h3>
<p>1.	On the Microsoft Office Home page, in the Apps area, select Outlook.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/13.png"/>
<p>2.	In Outlook, verify that there is a new message from your user account with the Subject Flow demo.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/14.png"/>
<p>3.	In the upper-left corner, select app launcher, and select OneDrive.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/15.png"/>
<p>4.	In OneDrive, select Email attachments from Flow.</p>
<p>5.	Verify that the folder contains the attachment which was sent. Notice that the file is listed as modified by the user to whom you have sent the email because those were the credentials used in the flow.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/16.png"/>
<p>6.	In the top menu, select Flow and then select See your flows.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/17.png"/>
<p>7.	In the Flow window, select Save Office 365 email attachments to OneDrive for Business.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/18.png"/>
<p>8.	Read the information in the RUN HISTORY box.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/19.png"/>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/20.png"/>
<p>9.	Close your web browser.</p>

<h2>Exercise 3: Managing Flow and PowerApps (5 minutes)</h2>

<h3>Task 1: Sign in to Microsoft 365 admin center as Admin</h3>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/21.png"/>

<h3>Task 2: View Flow quotas and licenses</h3>
<p>1.	In Microsoft 365 admin center, verify the layout of the screen. If the layout has an Essentials heading in the content pane, then no action is required. If the layout does not have an Essentials heading, then enable the Try the preview toggle in the upper right corner.</p>
<p>2.	In the navigation pane, select Show more and then select All admin centers.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/22.png"/>
<p>3.	From the list of admin centers, select Power Automate.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/23.png"/>
<p>4.	In the Microsoft Flow admin center, select Tenant and select Quotas.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/24.png"/>
<p>5.	On the Quotas page, select Download all the data for the tenant to a .csv file.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/25.png"/>
<p>6.	Wait a few moments for the data to be prepared and then select Download the file.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/26.png"/>
<p>7.	If possible, open the downloaded file in Microsoft Excel or a text editor for review.</p>
<p>8.	Review the file data, it should show that the flow Save Office 365 email attachments to OneDrive for Business was run and the owner should be visible.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/27.png"/>
<p>9.	Close the data file.</p>
<p>10.	In the navigation pane, select User licenses and then select Download a list of active user licenses.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/28.png"/>
<p>11.	Wait a few moments for the data to be prepared and then select Download the file.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/29.png"/>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/30.png"/>
<p>12.	If possible, open the downloaded file in Microsoft Excel or a text editor for review.</p>
<p>13.	Review the file data and note that you should see only users that have used Flow are listed.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/31.png"/>
<p>14.	Close the data file.</p>

<h3>Task 3: Configure a data loss prevention policy</h3>
<p>1.	In Microsoft Flow admin center, in the navigation pane, select Data policies.</p>
<p>2.	In the upper right corner, select New policy.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/32.png"/>
<p>3.	In the Data Policy Name window, in Environments, verify Apply to ALL environments is selected, and then select Continue.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/33.png"/>
<p>4.	In Data groups, in the Business data only area, select Add.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/34.png"/>
<p>5.	In the Add connectors dialog box, select SharePoint, select Dynamics 365, and then select Add connectors.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/35.png"/>
<p>6.	In the upper right corner, select Save Policy.</p>
<img src="https://csgithub.blob.core.windows.net/managingflowandpowerapps/36.png"/>
<p>7.	Close your web browser.</p>
