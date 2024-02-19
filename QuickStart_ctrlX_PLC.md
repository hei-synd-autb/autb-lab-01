<h1 align="left">
  <br>
  <img src="./img/hei-en.png" alt="HEI-Vs Logo" width="350">
  <br>
  HEI-Vs Engineering School - Industrial Automation Base
  <br>
</h1>

Cours AutB

# This is a quick start for ctrlX PLC

How to check if systems are connected, [at the end of this document](#check-if-system-is-connected).

## Get Lab from Git

Create a folder AutB in Documents.
Pin it to Quick Access.

<figure>
    <img src="./img/QuickAccessToAutB.png"
         alt="Lost image quick start to AutB">
    <figcaption>Quick start to AutB</figcaption>
</figure>

> By default, folder Automation is reserved for Siemens S7.


<figure>
    <img src="./img/CloneWithTortoiseGit.png"
         alt="Lost image CloneWithTortoiseGit.png">
    <figcaption>Clone With Tortoise Git</figcaption>
</figure>

<figure>
    <img src="./img/SelectSourceAndSetinationForProject.png"
         alt="Lost image SelectSourceAndSetinationForProject.png">
    <figcaption>Select Source And Destination For Project (Select lab number)</figcaption>
</figure>


## Load archive from folder and upload program on target

Launch program ctrlX PLC Engineering

<figure>
    <img src="./img/ctrlX PLC Engineering.png"
         alt="Lost image ctrlX PLC Engineering.png">
    <figcaption>ctrlX PLC Engineering.png</figcaption>
</figure>

<figure>
    <img src="./img/StartSystemLoadFromArchive.png"
         alt="Lost image StartSystemLoadFromArchive.png">
    <figcaption>AutB Extract From Archive</figcaption>
</figure>

<figure>
    <img src="./img/StartSystemSelectVersionStudent.png"
         alt="Lost image StartSystemSelectVersionStudent.png">
    <figcaption>Select Student version with .projectarchive extension</figcaption>
</figure>

**.projectarchive** is to be seen as a *.zip* of all files you need for your project

Many possibilies, you can try this:
<figure>
    <img src="./img/StartSystemExtractInSameFolder.png"
         alt="Lost image StartSystemExtractInSameFolder.png">
    <figcaption>Select where you want your project</figcaption>
</figure>

Scan network to connect IDE with ctrlX Core.
Double click on (1)

A the end of the process the ctrlX (3) should be green too.

<figure>
    <img src="./img/ScanNetworkForCtrlX.png"
         alt="Lost image ScanNetworkForCtrlX">
    <figcaption>Scan Network For CtrlX</figcaption>
</figure>

<figure>
    <img src="./img/SelectDevice_ctrlx-CORE.png"
         alt="Lost image SelectDevice_ctrlx-CORE">
    <figcaption>Select Device ctrlx-CORE</figcaption>
</figure>

Enter password to log to ctrlX Core
<figure>
    <img src="./img/Device User Logon.png"
         alt="Lost image Device User Logon.png">
    <figcaption>Device User Logon</figcaption>
</figure>

Enter password to log to ctrlX Core
<figure>
    <img src="./img/Generate Code Login Start Program.png"
         alt="Lost image Generate Code Login Start Program.png">
    <figcaption>Generate Code Login Start Program</figcaption>
</figure>

Ready !

# Check if system is connected

## Check if ctrlX Core is connected or ready.

<figure>
    <img src="./img/ctrlX WORKS Engineering.png"
         alt="Lost image ctrlX WORKS Engineering.png">
    <figcaption>Open program ctrlX Works</figcaption>
</figure>

<figure>
    <img src="./img/OpenCtrlX_Works_To_CheckConnectionWithCore.png"
         alt="Lost image OpenCtrlX_Works_To_CheckConnectionWithCore">
    <figcaption>CtrlX Works show you list of ctrlX Cores connected to your PC</figcaption>
</figure>

Click on ctrlX Core, it opens it in a Browser.
You will need login: **boschrexroth** and password: **boschrexroth** to connect.
*Maybe you need to select advanced and access unsage to connect.*

When you are connected you have access to the core.

<figure>
    <img src="./img/StartSystemResetAlarms.png"
         alt="Lost image StartSystemResetAlarms.png">
    <figcaption>You can see and reset alarms here</figcaption>
</figure>

## Check is Siemens S7 is connected and running