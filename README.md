# Testing-with-Jest
We will use Jest to do some unit testing. Few things are needed here:
* Node.js
* npm (node package manager)
* VS Code

# Instructions
* Create a folder with any file name you choose but make sure it ends with '.js' to let VS Code know we are going to use JavaScript. This file is where we will write our program and will be linked to another specific file used for testing that program. So if our file name is ```hello.js``` where we write our program, this file will be linked to another file called ```testing file.test.js```, and this file we will test our ```hello.js``` file.
* Now open a new terminal and check to see if you have Node.js installed. Use this command:  
```node --version```
* If Node.js is not installed then got this website https://nodejs.org/en/download/ and choose the recommended options. I personally chose version 19.
* After installing it, go back to VS code and verify by using the above command.
* Now check for ```npm``` by using this command:  
```npm --version```
* By installing Node.js, npm should be installed.
* Now check to see if Jest is installed by using this command:  
``` jest --version```
* If not installed we will use npm to start installing it since Jest needs node.js to run and npm is a way to install node modules. Use this to add a ```package.json``` file:  
```npm init -y```
  * This ```-y``` command is useful for automatically answering 'yes' to all questions the ```initi``` command will ask during installation.
* A new file will appear in the folder. This file helps keep track of node modules a project depends on.
* Since we are testing we want to install Jest locally in this project, so we will use this code:  
```npm install --save--dev jest```
* This will update the ```package.json``` file with Jest in it.
* Now go into the ```package.json``` file and you will see ```"test": "echo \"Error: no test specified\" && exit 1"```. We need to replace this with:  
```"test": "jest"```.
 * This indicates that we want to use Jest for our testing.
* Now, let's run Jest:  
```npm run test```
* Now set up your testing file. It should end with:  
```File name.test.js```
* Now we can go look at the files I have and explore how testing is done.

