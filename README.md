# Run Client Side of the Project

This Project has two parts, the client side and smart_contracts. To run the client side we need to do the following:

1. Download [VScode](https://code.visualstudio.com/download)
2. Next, we need to install [Node.js and NPM](https://nodejs.org/en/download/)
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
3. Now that all of the basics are downloaded Let Get It! 



Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
