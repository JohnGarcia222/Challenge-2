# Challenge 2
--------------
Throughtout the course of the project I have had to work my way through some issues within my code that did not allow me to execute everything properly on my first go around. The first thing I had to install/re-install were the pips for my code. In order to do so I had to find out what python version I was running. I went towards the bottom of the screen inside the blue bar and started to run python 3.7.13 in dev mode which then allowed me to go into my terminal and install pip fire and questionary. Outside of this was checking to see if anything special was required and it seems as though all forms of operating systems work fine as long as you have the correct packages and libraries installed.
---------  
# Technologies  
----------
Libraries: fire, sys, pathlib  
Framework: VS Code  
Operating Systems: Mac OS, Microsoft Windows   
Programming Language: Python   
--------
# Installation
--------
The first and foremost thing to do is to get anaconda running which can be installed from an outside source (https://anaconda.cloud/register) and the you link that into vs code.  
The next thing that needs to be installed is python which can be grabbed from the extensions area -> 
![image](https://user-images.githubusercontent.com/127170402/229506847-268f3c51-4351-4e26-b2d2-0ebe8cfec6bb.png)


and once that is all installed you will have to direct to the blue bar on the bottom and change the version of python to 3.7.13 dev. Can be seen here -> ![image](https://user-images.githubusercontent.com/127170402/229506720-53093ff1-713a-4a4f-ae5e-74f53cef4718.png)

Upon the dev activation you will need to install you pips(fire and questionary). To do this you will need to direct to your terminal and the use the (pip install questonary) and the (pip install fire) lines of code.

Last but not least you will need your imports with are fire and questionary. In you command terminal in either GIT bash or vs terminal you will have to make sure that first you input (conda activate dev). Then you need to run the command (pip install fire and pip install questionary). All of this put together should allow the code to run smoothly on your device.

--------
# Changes made within the code
--------

Initial change made was adding a csv_save spot by coding csv_save into fileio.pv. I then imported the csv_save into my app.py through the (from qualifier.utils.fileio import save_csv) line of code. All of this will allow the user to save and see their data upon using the code.

The next change was to add confirmation in regards to whether or not the user would like to save their qualifying loan, that is if they had any at all. The code would check for qualifying loans and if none are located the system will then exit. If qualifying loans are found the system will then ask the user if they would like their data saved and where. You would then specify your location and move forward.

I then had to reinstall my pips in conda dev mode through GIT bash, normally you dont have to use git bash to install the pips but it seems as though my computer was a special case. I had to route into the dev pips folder on git bash to then grant access to my computer so it could use fire and questionary.

I then had to grab the terminal history which proved a tad bit annoying purely because I use multiple consoles and not just vs code

--------------
# As the code runs
-------------
One of the earliest code lines ran should appear as the following
![image](https://user-images.githubusercontent.com/127170402/229514020-779b8b89-b0af-4ef8-b16d-eaa13c89f8cd.png)

![image](https://user-images.githubusercontent.com/127170402/229513816-689b3b76-beec-4686-b8ee-5b5af1f3c500.png)

Moving a tad bit further down the questionaries should ask for all of your information
![image](https://user-images.githubusercontent.com/127170402/229514760-9d255bc3-6885-40ad-8baa-38c270d9fc5a.png)
![image](https://user-images.githubusercontent.com/127170402/229514810-708ebe64-ec01-483a-8bc0-49e10ed9bb16.png)
![image](https://user-images.githubusercontent.com/127170402/229514845-42967087-e6ca-499a-aca7-e7ed17cf2bb3.png)
![ql2](https://user-images.githubusercontent.com/127170402/229604896-66452159-ef5c-418f-8468-f8200b8dc88b.png)

------------------------
# Contributors
--------------------
John Garcia  
email: Jdganna222@gmail.com

----------
# Contributors/Editors
----------
John Garcia
