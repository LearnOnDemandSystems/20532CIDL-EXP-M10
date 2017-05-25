
<!---
Version: 1.0 
-->
# Exercise 1: Creating an Azure AD
## INTRODUCTION MESSAGE
In this exercise, you will:  
  
Create an Azure AD by using the Classic Portal.  
Create a Global Administrator role in the new directory.  
Create a standard User role in the new directory.  
  
The main tasks for this exercise are as follows:  
Sign in to the Azure Classic Portal.  
Create a directory by using the Classic Portal.  
Create a Global Administrator role in the directory.  
Create a User role in the directory.
## COMPLETION MESSAGE
Results: After completing this exercise, you will have created an Azure AD and populated the directory with users.
### Login as Student
Login as Student with a password of Pa$$w0rd.

#### :bulb: KNOWLEDGE
You can use the Commands menu and choose Ctrl\+Alt\+Delete then click Student and enter Pa$$w0rd and press Enter. You can also use the Command menu and choose Paste/Paste Password instead of typing the password manually.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666871.jpg
>* ShowAutomatically = No





### On the Start screen, click Internet Explorer
On the Start screen, click the Internet Explorer tile

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666872.jpg
>* ShowAutomatically = No





### Go to the new Azure Portal
Go to https://portal.azure.com. Enter the email address of your Microsoft account associated with your Azure subscription. Then enter the password for your Microsoft account. Check Keep me signed in. Click Sign In.

#### :bulb: KNOWLEDGE


Before starting this lab, you must have completed the lab in Module 2. All work in this lab is done within vm20532 created in the lab in Module 2. Start and Connect via Azure Portal.



If you see a pop-up for Skype for Business click Don't Enable.  
  
Ignore any updates to OneDrive



#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666873.jpg
>* ShowAutomatically = No



#### :calling: COMMAND
```TypeText
https://portal.azure.com
```


### Browse Virtual Machines
In the navigation pane on the left side of the Azure Portal, click Virtual Machines.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666874.jpg
>* ShowAutomatically = No





### Start the VM
Click the vm20532 VM that was created in the lab in Module 2 for development. In the Overview blade, if the VM is stopped, click Start and wait for the VM to start up. This may take a few minutes.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666875.jpg
>* ShowAutomatically = No





### Connect to the VM via RDP
When the vm20532 VM has started, click Connect.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666876.jpg
>* ShowAutomatically = No





### Allow pop-ups
If presented with a message box that shows a pop-up has been blocked, select Options for this site and choose Always Allow. Then click Connect again.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/673107.jpg





### Click Open
When presented with the RDP download pop-up at the bottom of the screen, click Open.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/673108.jpg





### In the Remote Desktop Connection dialog box:
In the Remote Desktop Connection dialog box, perform the following steps:  
a. Click Don’t ask me again for connections to this computer to prevent this dialog box from displaying again.  
b. Click Connect.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666877.jpg
>* ShowAutomatically = No





### In the Windows Security dialog box:
In the Windows Security dialog box, perform the following steps:  
a. For the User name dialog box, provide the value, Student.  
b. For the Password dialog box, provide the value, AzurePa$$w0rd.  
c. Click OK.

#### :bulb: KNOWLEDGE
Note: If you computer is on a domain, you may need to add a backslash before the username to "escape" the domain.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666878.jpg
>* ShowAutomatically = No





### In the Remote Desktop Connection dialog box:
In the Remote Desktop Connection dialog box, perform the following steps:  
a. Verify if the Remote certificate name matches the name of your virtual machine.  
b. Click Don’t ask me again for connections to this computer to prevent this dialog box from displaying again.  
c. Click Yes.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666879.jpg
>* ShowAutomatically = No





### Close Server Manager
If you just started the VM, Server Manager will start automatically after 30 seconds. When it starts, you can close it.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666880.jpg
>* ShowAutomatically = No





### On the Start screen, open Internet Explorer
On the Start screen, click the Internet Explorer tile.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666881.jpg
>* ShowAutomatically = No





### Sign in to the Azure Portal
Sign in to the Azure Portal at https://portal.azure.com.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666882.jpg
>* ShowAutomatically = No



#### :calling: COMMAND
```TypeText
https://portal.azure.com
```


### Start Classic Portal
In Internet Explorer start a new tab. Go to https://manage.windowsazure.com. Enter the email address and password for your Microsoft account, and then click Sign In.

#### :bulb: KNOWLEDGE
Note: For this lab, you will use the Classic Portal because the functionality to create new Azure Active Directory domains is not fully available in the Portal. \)It is in Preview)  
  
If prompted with a Get Started window, click Not Now.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666883.jpg



#### :calling: COMMAND
```TypeText
https://manage.windowsazure.com
```


### Open Active Directory page
In the navigation pane on the left side of the screen, scroll down, and then click Active Directory. Click the Directory tab at the top of the page

#### :bulb: KNOWLEDGE
Note: The scroll bar does not appear until you hover over it.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666884.jpg





### At the bottom of the screen, click +New.
At the bottom of the screen, click \+New.  
a. Select APP SERVICES, ACTIVE DIRECTORY, DIRECTORY, and then click CUSTOM CREATE.

#### :bulb: KNOWLEDGE
Note: Under App Services you need to scroll down to see Active Directory

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666886.jpg





### Create new directory
b. In the Add Directory dialog box, perform the following steps:  
c. In the Directory list, select Create new directory.  
d. In the Name box, type 20532.  
e. In the Domain Name box, type ad20532\[Your Name\].  
f. In the Country or Region list, select your current location.  
g. Click the check mark button to add the directory

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666885.jpg





### Open the new directory
In the list of directories, click the name of the directory 20532.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666887.jpg





### Close features pop-up
You may be prompted with a popup dialog talking about Azure AD features. You can safely ignore this dialog by clicking the checkmark button to close it.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/673109.jpg





### View the directory home page
View the directory home page

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/673110.jpg





### Click the Users tab at the top of the page
Click the Users tab at the top of the page.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666888.jpg





### At the bottom of the screen, click Add User.
At the bottom of the screen, click Add User.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666889.jpg





### In the Add user dialog box, perform the following:
In the Add user dialog box, perform the following steps:  
a. In the Type of User list, select New user in your organization.  
b. In the User Name box, type admin.  
c. In the Domain list, ensure that only your domain \)ad20532\[Your Name\]) is selected.  
d. Click the right arrow to move to the next step in the wizard.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666890.jpg





### Continue to enter User information:
e. In the First Name box, type Admin.  
f. In the Last Name box, type User.  
g. In the Display Name box, type Admin User.  
h. In the Role list, select Global Admin.  
i. In the Alternate Email Address box, type example@contoso.com.  
j. Ensure the Enable Multi-Factor Authentication check box is cleared.  
Click the right arrow to move to the next step in the wizard

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666891.jpg





### On the Get Temporary Password screen:
On the Get Temporary Password screen, click Create to create the password.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666892.jpg





### Record the temporary password that is generated
b. Record the temporary password that is generated for the user. For instance, using Notepad.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666894.jpg





### Complete the wizard:
Click the check mark button to complete the wizard.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666893.jpg





### Add another user:
At the bottom of the screen, click Add User.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666895.jpg





### In the Add User dialog box, perform the following:
In the Add User dialog box, perform the following steps:  
a. In the Type of User list, select New user in your organization.  
b. In the User Name box, type standard.  
c. In the Domain list, ensure that only your domain \)ad20532\[Your Name\]) is selected.  
d. Click the right arrow to move to the next step in the wizard.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666896.jpg





### Continue entering user information:
e. In the First Name box, type Standard.  
f. In the Last Name box, type User.  
g. In the Display Name box, type Standard User.  
h. In the Role list, select User.  
i. Ensure the Enable Multi-Factor Authentication check box is cleared.  
Click the right arrow to move to the next step in the wizard

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666897.jpg





### On the Get Temporary Password screen:
a. On the Get Temporary Password screen, click Create to create the password.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666898.jpg





### Record the temporary password that is generated
b. Record the temporary password that is generated for the user. For instance, in Notepad.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666899.jpg





### Complete the wizard:
Click the check mark button to complete the wizard.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666900.jpg






# Exercise 2: Securing an Existing ASP.NET Web Application
## INTRODUCTION MESSAGE
In this exercise, you will:  
  
Use the MVC AuthorizeAttribute to secure a web application.  
The main tasks for this exercise are as follows:  
Add the Authorize attribute to the HomeController class.  
Debug the web application.
## COMPLETION MESSAGE
Results: After completing this exercise, you will have used MVC to ensure that a user is signed in before accessing a controller or action.
### Open an existing ASP.NET web application project
On the taskbar, click the File Explorer icon. In the Libraries window, go to Allfiles \)F):\\Mod10\\Labfiles\\Starter\\Contoso.Events, and then double-click Contoso.Events.sln.

#### :bulb: KNOWLEDGE
Note that Known file extensions \)such as .sln) may be hidden. See screenshot. It may also take a while for Visual Studio 2015 to open.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666901.jpg
>* ShowAutomatically = No





### Open the HomeController.cs file
In the Solution Explorer pane, expand the Administration folder.  
a. Expand the Contoso.Events.Management.Old project.  
b. Expand the Controllers folder.  
c. Double-click the HomeController.cs file.

#### :bulb: KNOWLEDGE
Ignore Intellisense errors

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666902.jpg





### Locate the class definition at the top of the file
d. Locate the class definition at the top of the file:  
public class HomeController : Controller

#### :bulb: KNOWLEDGE
Ignore Intellisense errors

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666903.jpg





### Add the Authorize attribute
e. In the line above the class definition, add the Authorize attribute:  
\[Authorize\]  
f. Save the HomeController.cs file.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666904.jpg



#### :calling: COMMAND
```TypeText
[Authorize]
```


### Set Startup Project
In the Solution Explorer pane, right-click the Contoso.Events.Management.Old project, and then click Set as Startup Project.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666905.jpg





### On the Debug menu, click Start Debugging
On the Debug menu, click Start Debugging

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666906.jpg





### The website returns a 401 – Unauthorized error
Wait for Internet Explorer to open.  
Verify that the website returns a 401 – Unauthorized error message.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666907.jpg





### On the Debug menu, click Stop Debugging
Switch to the Contoso.Events – Microsoft Visual Studio window.  
On the Debug menu, click Stop Debugging

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666908.jpg






# Exercise 3: Integrating Azure AD with ASP.NET Identity
## INTRODUCTION MESSAGE
In this exercise, you will:  
  
Create a new ASP.NET MVC application by using ASP.NET Identity for authentication and authorization.  
Integrate the new Website with Azure AD organization accounts.  
The main tasks for this exercise are as follows:  
Create a new management web application by using Azure AD as the identity provider.  
Verify that the Management web application requires a sign-in by using an organizational account
## COMPLETION MESSAGE
Results: After completing this exercise, you will have used an Azure AD domain with the ASP.NET Identity framework.
### In Visual Studio, add a new project
In the Solution Explorer pane, right-click the Administration solution folder, point to Add, and then click New Project.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666909.jpg
>* ShowAutomatically = No





### In the Add New Project dialog box:
In the Add New Project dialog box, perform the following steps:  
a. Expand Installed, expand Visual C\#, and then click Web.  
b. Click the ASP.NET Web Application project type.  
c. In the Name box, type Contoso.Events.Management.  
d. Ensure that the Location box has the value F:\\Mod10\\Labfiles\\Starter\\Contoso.Events.  
e. Click OK.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666917.jpg





### In the New ASP.NET Project dialog box:
In the New ASP.NET Project – Contoso.Events.Management dialog box, perform the following steps:  
a. Click the MVC template.  
b. Ensure that the Microsoft Azure – Host in the Cloud check box is cleared.  
c. Leave the remaining fields to their default values.  
d. Click Change Authentication.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666918.jpg





### In the Change Authentication dialog box:
In the Change Authentication dialog box, select Work And School Accounts.  
a. In the Domain box, type ad20532\[Your Name\].onmicrosoft.com.  
b. Leave the default values in the remaining fields.  
c. Click OK.

#### :bulb: KNOWLEDGE
Note: The screens that display during sign-in process might vary depending on whether you signed in by using that domain lately or set up Internet Explorer to remember a specific sign-in.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666919.jpg





### Sign in by using the Admin User account:
Sign in by entering the Admin User account \)admin@ad20532\[Your Name\].onmicrosoft.com). Click Continue, if prompted. If not, continue to next step anyway to enter temporary password.

#### :bulb: KNOWLEDGE
Note: The screens that display during sign-in process might vary depending on whether you signed in by using that domain lately or set up Internet Explorer to remember a specific sign-in.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666920.jpg





### Enter temporary password
Enter the temporary password that was created earlier in this lab and click Sign In.

#### :bulb: KNOWLEDGE
If you are prompted with an Additional security verification dialog, you can safely close and ignore this dialog.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/673111.jpg





### Update your password to Pa$$w0rd
In the Change Password dialog box, update your password to Pa$$w0rd. Click Update password and Sign In.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666921.jpg





### In the New ASP.NET Project dialog:
In the New ASP.NET Project – Contoso.Events.Management dialog box, click OK.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666922.jpg





### Verify new Project
In the Solution Explorer pane, expand the Administration folder.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666923.jpg





### Set as StartUp Project
Right-click the Contoso.Events.Management project, and then click Set as StartUp Project

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666924.jpg





### Add a Reference
Right-click the Contoso.Events.Management project, point to Add, and then click Reference

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666925.jpg





### In the Reference Manager dialog:
In the Reference Manager – Contoso.Events.Management dialog box, perform the following steps:  
a. On the left side, expand the Projects tab and then click the Solution option.  
b. Double-click the Contoso.Events.Models reference.  
c. Double-click the Contoso.Events.ViewModels reference.  
d. Click OK.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666926.jpg





### Open Package Manager Console
On the View menu, point to Other Windows, and then click Package Manager Console.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666927.jpg





### Install Entity Framework
a. In the Package Manager Console pane, in the Default Project list, select Contoso.Events.Management.  
b. In the Package Manager Console text area, place the cursor after the PM> command prompt, then type the following command:  
Install-Package EntityFramework -Version 6.0.2  
c. Press Enter.

#### :bulb: KNOWLEDGE
If you do not see the Default Project List, you can Auto Hide the Solution Explorer and Properties sheet to expand the window or click the small ellipsis on the right of the Package Manager Console pane title bar.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666928.jpg



#### :calling: COMMAND
```TypeText
Install-Package EntityFramework -Version 6.0.2
```


### Verify results of Install-Package
 Verify the results of the Install-Package command

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/673112.jpg





### Copy folders to new Project:
In the Solution Explorer pane, expand the Administration folder. Expand the Contoso.Events.Management.Old project.  
a. Copy the following folders: App\_Start, Content, Controllers, Fonts, Scripts, Views

#### :bulb: KNOWLEDGE
Note: To copy all the folders at once press the Shift key and then click the App\_Start and Views folders. This will select all six folders at the same time. You can then use the shortcut menu or press Ctrl\+C to copy the folders.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666929.jpg





### Paste all the copied folders into the new project
Paste all the copied folders in the Contoso.Events.Management project.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666930.jpg





### Merge existing folders
c. When prompted to merge the folders, click Apply to all items, and then click Yes.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666931.jpg





### Replace existing files
d. When prompted with Destination File Exists, click Apply to all items, and then click Yes.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666932.jpg





### Open old web.config file
Open the web.config file in the Contoso.Events.Management.Old project

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/673113.jpg





### Copy connectionStrings from old web.config
e. Copy the connectionStrings from the web.config file in the Contoso.Events.Management.Old project

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666933.jpg





### Open new web.config file
Open the web.config file in new Contoso.Events.Management project

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/673114.jpg





### Paste the content into the new web.config file
Paste the content into the web.config file in Contoso.Events.Management project after the </appSettings> tag

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666934.jpg





### Verify new connection strings and Save
Verify new connection strings and click Save

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666935.jpg





### Set as Startup Project
In the Solution Explorer pane, right-click the Contoso.Events.Management project, and then click Set as Startup Project

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666936.jpg





### On the Debug menu, click Start Debugging
On the Debug menu, click Start Debugging

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666937.jpg





### Trust the self-signed certificate.
a. The Microsoft Visual Studio dialog will appear indicating that you can configure IIS Express to trust the self-signed certificate.  
b. Click Yes.  
\)If the dialog above does not appear, see the Knowledge tip on this task).

#### :bulb: KNOWLEDGE
If the Microsoft Visual Studio dialog does not appear, you will need to repair IIS Express and retry. This is a known issue with Visual Studio 2015 Update 3.  
  
If necessary, perform the following steps to repair IIS Express:   
a. Close Internet Explorer \)all instances)  
b. Open Control Panel, click "Programs", then click "Programs and Features"  
c. Select "IIS 10.0 Express", then click "Repair".   
d.  Retry Visual Studio Debug/Start Debugging  
  
If this does not work, try restarting Visual Studio, open the project again and retry Start Debugging.  
  
  


#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666938.jpg





### Accept self-signed certificate
c. The Security Warning dialog will appear indicating that the self-signed certificate cannot be verified but can still be installed.  
d. Click Yes.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666939.jpg





### If prompted, choose to login as another user:
If prompted, choose to "Use another account" to authenticate.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/673179.jpg





### Sign in by using the Standard User account
Sign in by using the Standard User account and temporary password that was created earlier in this lab.  
If you are prompted with an Additional security verification dialog, you can safely close and ignore this dialog.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666940.jpg





### Update your password to Pa$$w0rd
In the Change Password dialog box, update your password to Pa$$w0rd. Click "Update password and sign in".

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666941.jpg





### Accept confirmation
Click Accept on confirmation page

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666942.jpg





### View the home page of Contoso.Events.Management
View the home page of the Contoso.Events.Management web application.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666943.jpg





### Click Go To Events List to view the list of events
Click Go To Events List to view the list of events.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666944.jpg





### Close Internet Explorer
Close Internet Explorer





### Close Visual Studio 2015
Close Visual Studio 2015





### Close File Explorer
Close File Explorer





### Close RDP session
Close RDP session and click OK to disconnect

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666913.jpg
>* ShowAutomatically = No





### Stop VM to save billing charges
If you are stopping labs for the day, on the vm2032 Overview page in the Azure Portal, click Stop to stop billing charges until you start labs again. When prompted, click Yes to stop the VM.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/666914.jpg
>* ShowAutomatically = No





### Close Internet Explorer
Close Internet Explorer to end the lab






