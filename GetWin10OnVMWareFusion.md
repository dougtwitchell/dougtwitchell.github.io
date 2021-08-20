---
title:  'Get Windows 10 on VMWare Fusion for MacOS'
author: Doug Twitchell
lang: en-us
...

This tutorial will show how to run Windows on MacOS using VMWare fusion.  This is for students in the College of Business and Economics who use MacOS, but need to run software that only runs on Windows.


# Minimum required specifications

To run Windows in VMWare Fusion, your Mac must have the following minimum specifications.  You can find your Mac's specifications by going to  → About this Mac.

- Memory: 4GB (8GB Recommended, 4GB will work, but will be slow)
- Storage: At least 40 GB free

# Steps

The process has three major steps:

- Obtain and install VMWare Fusion  
- Obtain and install Windows 10 on VMWare Fusion  
- Obtain and install the required software
  
# Obtain and install VMWare Fusion

<figure class = "youtube">
    <iframe width="480" height="270" src="https://www.youtube-nocookie.com/embed/X46TMmI5Fos" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <figcaption>Obtaining and installing VMWare Fusion</figcaption>
</figure>

## Register with VMWare and Download VMWare Fusion

1) Go to [The VMWare Fusion Personal License Page](https://my.vmware.com/web/vmware/evalcenter?p=fusion-player-personal)
2) Choose `Create an Account` (unless you already have one)
3) Register by giving the required information
4) Verify your email address by clicking on the appropriate link in the email sent to you
5) Go back to [The VMWare Fusion Personal License Page](https://my.vmware.com/web/vmware/evalcenter?p=fusion-player-personal) and login with your account
6) You should see your License Key in the License Information.  You will need this later.
7) Download VMWare Fusion 12 by clicking on the `Manually Download` button in the Download Packages section

## Install VMWare Fusion

1) Open the .dmg file you downloaded.  You can find it by clicking on `show in finder` on the downloaded file in the browser
2) Double-click on the installation
3) During the installation, it will ask you for a license key.  This is the serial number saved above.
4) Allow notifications from VMWare Fusion when asked
5) When asked to enable access to Accessibility features, Click `OK`.  When presented with the Accessibility settings, click on the lock to unlock, if needed, and check `VMWare Fusion` to allow them.
6) When asked whether to allow VMWare Fusion to control "System Events.app", allow it.
7) During the installation, you may get a prompt to allow VMWare Fusion to load a system extension.  You may have allow this in `System Preferences` → `Security and Privacy`.  On the General tab, it should say, "System software from developer 'VMware, Inc.' was blocked from loading.  Click on the `Allow` button.
8) If prompted, install any updates to VMWare Fusion.
9) If not prompted, once you are finished with the install, open VMWare Fusion and have it check for and install updates: ![check for updates](CheckForUpdates.png)
10) Once finished, when you open a VMWare Fusion, it will present you with a window asking you to "Select the installation method."  Leave that open and go to the next step where you will obtain and install Windows 10.

# Obtain and install Windows 10 on VMWare Fusion

<figure class = "youtube">
    <iframe width="480" height="270" src="https://www.youtube-nocookie.com/embed/JWFHZabXm0A" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <figcaption>Get Windows 10 from Azure Dev Tools for Teaching</figcaption>
</figure>

## Sign up for Azure Dev Tools for Teaching

1) First you need to get a Product Key for Windows 10 by signing into Azure Dev Tools for Teaching.
2) Go to [aka.ms/devtoolsforteaching](https://aka.ms/devtoolsforteaching){target="_blank"}
3) Sign in using your Boise State "Work or School" email.
4) At this point you should be logged in and see something that says, "Welcome to the Azure Education Hub." If there's an error, follow the instructions in the next section.  If not, skip the next section.

### Inability to login to Azure Dev Tools for Teaching (only if there's an error)

<figure class = "youtube">
    <iframe width="480" height="270" src="https://www.youtube-nocookie.com/embed/Eam_x0klsao" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <figcaption>What to do if you get an error when trying to login to Azure Dev Tools for Teaching</figcaption>
</figure>

Some of you may get an error when attempting to login to Azure Dev Tools for Teaching.  If this is the case, follow these insructions.

1) The most common error when login into Azure Dev Tools for Teaching is an Incorrect account type.  To fix this error, you will login with a personal Microsoft Account.
2) Click on "Sign in with a separate Microsoft Account", or, if that's not available, start over by going to [aka.ms/devtoolsforteaching](https://aka.ms/devtoolsforteaching) and clicking on `Sign in` again.
3) This time, choose `Use another account` when prompted to pick an account
4) Use your personal Microsoft account.  You may have one for using Outlook.com email or for playing XBox online.  You may have to create one, if you don't have one already.
5) When prompted, enter your `boisestate.edu` email address to verify that you are a student at Boise State.
6) Go to your email and click on the link in the verification email.
7) You should now be logged in.
   
If you are still having trouble logging in, create a screenshot of your error and send it and the following to [helpdesk@boisestate.edu](mailto:helpdesk@boisestate.edu):

> I am attempting to login in to Azure Dev Tools for Teaching at aka.ms/devtoolsforteaching.  When I login I get the error in the attached screenshot, which says: "[THE TEXT OF THE ERROR]." I have attempted to login using my boisestate.edu account and my personal Microsoft Account, but neither work.

Additionally, send the same thing to [Microsoft Support](https://support.microsoft.com/en-us/supportrequestform/7a3f017a-c951-7e06-1bd7-64bf7fc202ff?SL=en&SC=US).

## Download Windows 10

1) After logging into Azure Dev Tools for Teaching, you should see a page that says "Welcome to the Education Hub."  Click on `Download Software` .
2) Search for "Windows 10" and choose "Windows 10 Education, version 21H1 – DVD" 
3) Click on "View Key" and copy the Product Key.  Copy it and save it somewhere for later.
4) Click on the Download button to download Windows 10 as a DVD image.

## Install Windows 10 in VMWare Fusion

<figure class = "youtube">
    <iframe width="480" height="270" src="https://www.youtube-nocookie.com/embed/1nWBPZMe2Sg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <figcaption>Install Windows 10 in VMWare Fusion</figcaption>
</figure>

1) Open Finder and go to your Downloads folder (or choose `Open in Finder` from the context menu on the file you downloaded).
2) If VMWare Fusion isn't already open, open it.
3) You should see a window that says "Select the Installation Method."  If not, with VMWare Fusion as the program in the foreground, go to the `File` menu on the menu bar and choose `New..."
4) Drag the file from Step 1 (its name will start with `en_windows_10`) to the area that says "Install from disc or image."
5) Choose `Continue`.
6) Leave "Use Easy Install" checked and choose an Account Name and Password for the administrator account for your new Windows 10 install.
7) Copy the Product Key you saved earlier into the "Windows Product Key" box
8) Choose "Windows 10 Education" as your Windows Version.  `Continue`
9) Choose the "More Seamless" option to allow for copying/pasting between MacOS and Windows 10. `Continue`
10) **If you only have 4 GB of RAM, choose `Continue`.  If you have more, choose `Customize Settings`**
    1)  If you have more than 4 GB of RAM do the following.  If not skip to the next step.
    2)  In the Settings, choose `Processor & Memory`.
    3)  Move the memory slider from 2048 to 4096 (or 8192 if you have 16 GB of RAM)
    4)  Close the settings.
11) Click on the large `►` in the black area of the virtual machine window just created.
12) Windows will now install.
13) When you login the first time, it will prompt you to logout and login again so that it can properly install VMWare Tools.  Logout and login again.
14) Windows 10 is not ready to install whatever software you require.

# Obtain and install the required software

At this point, you have a running Windows 10 virtual machine.  Using the virtual machine is almost exactly like using any other Windows 10 machine.  You should install the software specific to your class the same way as instructed for other Windows users.  The remaining sections are available if you need help installing the associated software for your classes.

## Obtain and install Microsoft Office including Microsoft Access

<figure class = "youtube">
    <iframe width="480" height="270" src="https://www.youtube-nocookie.com/embed/hw430PIHsqg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <figcaption>Obtain and install Microsoft Office including Microsoft Access</figcaption>
</figure>

1) Inside your Windows 10 virtual machine in VMWare Fusion use Internet Explorer to go to [https://www.boisestate.edu/oit-software/microsoft-office/student-advantage-microsoft-office-365-proplus/](https://www.boisestate.edu/oit-software/microsoft-office/student-advantage-microsoft-office-365-proplus/)
2) Scroll down and find and press the `Download Software` button
3) Sign in using your boisestate.edu username and password
4) Click on `Install Office` in the upper-right corner of the Office 365 screen
5) Choose to run the file it downloads
6) Choose `Yes` when it asks whether you want to allow it to make changes
7) After the installation is finished, the first time you open an office app, it will ask you to login.  Login using your boisestate.edu credentials

## Obtain and install Microsoft Project

<figure class = "youtube">
    <iframe width="480" height="270" src="https://www.youtube-nocookie.com/embed/mm2zCap34PE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <figcaption>Obtain and install Microsoft Project</figcaption>
</figure>

1) Go to [aka.ms/devtoolsforteaching](https://aka.ms/devtoolsforteaching) and click on `Sign in`.
2) Go to `Software` in the left-hand navigation
3) Search for "Project" in the search bar
4) Choose "Project Professional 2019 (Windows only)"
5) Click on `View Key` to get your license key.  Copy this key into notepad or some other place
6) Click on `Download`
7) Once it is downloaded, copy it from the Downloads folder to the Documents folder
8) Right-click on the file and choose `Mount`
9) Double-click on `Setup`
10) After it is finished, open Project and enter the license key when prompted

## Obtain and install Visual Studio Community

<figure class = "youtube">
    <iframe width="480" height="270" src="https://www.youtube-nocookie.com/embed/Va4grZDTX8c" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <figcaption>Obtain and install Visual Studio Community</figcaption>
</figure>

1) Go to [https://visualstudio.microsoft.com/vs/community/](https://visualstudio.microsoft.com/vs/community/)
2) Click on the `Download Visual Studio` button
3) Choose `Run` when asked what you want to do with the file
4) Choose `Yes` when asked if you want to allow it to make changes
5) Click the `Continue` button when prompted 
6) Choose `.NET desktop development` from the Workloads
7) Click the `Install` button in the lower-right corner
8) After it is done installing, it will launch and ask you to sign in.  Sign in using your boisestate.edu credentials

## Obtain and install Microsoft Visio

<figure class = "youtube">
    <iframe width="480" height="270" src="https://www.youtube-nocookie.com/embed/6saoRW-Mwho" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <figcaption>Obtain and install Visio</figcaption>
</figure>

1) Go to [aka.ms/devtoolsforteaching](https://aka.ms/devtoolsforteaching) and click on `Sign in`.
2) Go to `Software` in the left-hand navigation
3) Search for "Visio" in the search bar
4) Choose "Visio Professional 2019 (Windows only)"
5) Click on `View Key` to get your license key.  Copy this key into notepad or some other place
6) Click on `Download`
7) Once it is downloaded, copy it from the Downloads folder to the Documents folder
8) Right-click on the file and choose `Mount`
9) Double-click on `Setup`
10) After it is finished, open Project and enter the license key when prompted
