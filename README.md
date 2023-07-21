<h1>Chatbot for Reconciliation Process - Version 1.1</h1>


<h2>Description</h2>
The project consists of a Python chatbot that assists in the reconciliation process. Users will be able to easily select between two functions. The main goal of this project is to enable individuals with no knowledge of Python to execute routines.

Option 1 involves the program downloading position archives of all clients for each investment fund from the broker's shelf. There are at least 9 registered investment fund managers, and the program can effectively filter and download the position archives for all funds.

In Option 2, the task is relatively simple: filter the position archive sent by the Administrator, containing only one investment fund but comprising at least 1.5 million rows. This file is too large to be opened in Excel or similar tools. To address this issue, we created a program to filter the archive by selecting the correct broker company and excluding rows that are unnecessary for the task.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b>

<h2>Libraries Used</h2>

- <b>Selenium</b>
- <b>Pandas</b>
- <b>Tkinter</b>

<h2>Environments Used </h2>

- <b>Linux Ubuntu</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch the program: <br/>
<img src="https://i.imgur.com/UPWQMrm.png" height="80%" width="80%" alt="Chatbot Reconciliation Steps"/>
<br />
<br />
Option 1: <br/>
<img src="https://i.imgur.com/RgwrTRZ.png" height="80%" width="80%" alt="Chatbot Reconciliation Steps"/>
<br />
<br />
Option 2:  <br/>
<img src="https://i.imgur.com/1sNkQcZ.png" height="80%" width="80%" alt="Chatbot Reconciliation Steps"/>
</p>

<h2>Updates:</h2>
The project was updated to version 1.1 to align with the changes in the Administrator's archives and the number of Investment managers that the company has in its "shelf". The following updates were implemented:

Option 1: The quantity of Investment managers was reduced to 7.
Option 2: The "00:00:00" timestamp in the archive sent by the Administrator was excluded. 

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
