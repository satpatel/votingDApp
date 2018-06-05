# votingDApp
Decentralized voting application on ethereum block chain

This is a basic example of ethereum smart contract deployment and basic interaction via TestRPC.

Installation steps in Windows 10- 


1- Install Visual Studio Community Edition. If you choose a custom installation, the bare minimum items that need to be checked are all pertaining 
to Visual C++ (Current version is VS 2017)
2- Install the Windows SDK for Windows (If you are in Windows 10 install SDK for Windows 10)
3- Install Python 2.7 if not already installed, and make sure to add its install location to your PATH.
4- Install OpenSSL from here. Make sure to choose the right package for your architecture, and only install the full package (not the light version). 
You must install OpenSSL at its recommended location?—?do not change the install path.
5- Download and install node v8.1.2. Version v6.11.0 is not recommended with VS2017
6- Execute the command npm install ethereumjs-testrpc web3

---> Use npm install --global --production windows-build-tools if you get MSBuild error

---> Please modify deployedContract.address in javascript file if you don't see any change after clicking on vote button.

origin tutorial by Mahesh Murthy(https://medium.com/@mvmurthy/full-stack-hello-world-voting-ethereum-dapp-tutorial-part-1-40d2d0d807c2)
