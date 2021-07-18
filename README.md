![image](https://cdn.discordapp.com/attachments/860905633783480330/866200481540866048/NPCore_Discord_Header.png)
Welcome 👋🏼,
# 🇦 txAdminRecipe Deployer
# STEP: :one:
Download XAMPP: https://www.apachefriends.org/download.html and install the program. Visit https://www.heidisql.com/download.php and install the program. Start Xampp and start the first two boxes so "Apache" and "MySQL" are green. Open HeidiSQL, click the green circle with plus sign and name it something (doesn't matter what). Click open, in an empty space in the left pane, right click and highlight "Create New" and select database, name it something (doesn't matter what) but you will need the name of this later!

#  STEP: :two:
Make a new folder on your desktop and name it whatever you want. Go to https://runtime.fivem.net/artifacts/fivem/build_server_windows/master/ and download the LATEST RECOMMENDED (or your preference) artifacts. Open/Extract those into the folder you made on your desktop.
#  STEP: :three:
Open folder from step 1 and double click FXServer.exe which will then prompt you to open a browser (or will do automatically) and start with the txAdmin Setup. Under Deployment Type, choose REMOTE URL TEMPLATE. For data location, copy the address of your folder and paste it here and add \server-data (for example mine is: C:\Users\john\OneDrive\Desktop\server\server-data). Click save.
![image](https://cdn.discordapp.com/attachments/860905633783480330/860984804840439808/NPCore_Deployment_Type.png)
# YAML URL: ⤵️
https://raw.githubusercontent.com/npcore-framework/txAdminRecipe/main/npcore.yaml
![image](https://cdn.discordapp.com/attachments/860905633783480330/866215425695940608/NPCore_YAML_URL.png)

#  STEP: :four:
On servers first start up, let webpack and yarn run through until complete. Change the name of your database from root to something else and then generate a password and change that information in the server.cfg. Restart server, join, enjoy!
<br>
<br>
All rights are reserved to the original creator of this great framework, we thank you for opening doors and paving ways!
```
Evolve, Network, & Manifest.
The FiveM 🐌 NPCore Collective.
• © 2021 | NPCore Framework •
```

