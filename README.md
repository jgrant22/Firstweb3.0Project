# Run Client Side of the Project

This Project has two parts, the client side and smart_contracts. To run the client side we need to do the following:

1. Download [VScode](https://code.visualstudio.com/download)
2. Next, we need to install [Node.js and NPM](https://nodejs.org/en/download/)
3. Install Git [Windows](https://git-scm.com/download/win )
4. Install Git [Mac OS](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) (follow the install on mac section)
   1. install
      1.  Once the installer finishes downloading, launch it. Open the downloads link in your browser and click the file. Or, browse to the location where you have saved the file and double-click it to launch.
      2. The system will ask if you want to run the software – click Run.
      3. You will be welcomed to the Node.js Setup Wizard – click Next.
      4. On the next screen, review the license agreement. Click Next if you agree to the terms and install the software.
      5. The installer will prompt you for the installation location. Leave the default location, unless you have a specific need to install it somewhere else – then click Next.
      6. The wizard will let you select components to include or remove from the installation. Again, unless you have a specific need, accept the defaults by clicking Next.
      7. Finally, click the Install button to run the installer. When it finishes, click Finish.

   2. Verify it installed correctly
      1. Windows
         1. Access to the Windows command line (go to windows search bar > type cmd > right-click > run as administrator)
         2. Copy each command to confirm that an up to date version has been installed 
         ```
         node -v
         ```
         ```
         npm -v
         ```
      2. Mac OS 
         1. Open up your terminal 
         2. Copy each command to confirm that an up to date version has been installed 
         ```
         node -v
         ```
         ```
         npm -v
         ```
5. Now that all of the basics are downloaded Let Get It! 
6. At the top of this page is a GREEN button labeled `code`
   1. we need to click this and copy the script inside 
   2. right above the script we want to copy make sure `HTTPS` is underlined (not ssh)
   3. Let go back to your terminal or cmd line and follow these steps to navigate to our desktop via terminal(mac) or cmd(windows):
   ```
   On Windows the desktop is a folder on the system drive (usually C), C:\Users\user\Desktop and to navigate to it you need to use the cd command (change directory).

   First you need to make sure you're on the root directory, that's C:, so you run cd \

   Second you run cd users\username\desktop

   That's it!

   On Linux the procedure is similar, you run the command cd /home/username/desktop
   ```
   4. now that we are located in our desktop directory lets run ```git clone pasteScriptHere ```
7. Now that all of that is out of the way: 
``` 
Open VS Code
File > Open > find the desktop folder > and select the project folder > then click open
```
8. VS code has a built in terminal we can open by using: ` ^+~ (control + tilde`
9. We need to change into the client directory `cd client` and install the dependencies `npm install`
10. NOW run `npm run dev` when the projects loads it will give a link click that link to open the APP
11. Happy coding !

