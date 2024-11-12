　　　.   　　˚　✭　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　　✭　.　　. 　 ˚　.　c h a o s m o t i c 　　　.   　　˚　✭　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　　✭　.　　. 　 ˚　.　s y s t e m s 　　　.   　　˚　✭　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　　✭　.　　. 　 ˚　.　

Chaosmotic Systems: Culture, Cosmology, Computation is an MFA-level seminar taught by Garrett Laroy Johnson. It was taught for the first time at the School of the Art Institute of Chicago in the Art Technology / Sound Practices department during Fall 2024 semester. The course materials are public and can be accessed here.

This repository serves as an entry point for the course's collaborative wiki project. Students will contribute (5) 500-word articles about concepts, authors,

## Installation
### Obsidian
Obsidian is where you will add to the Wiki on your own machine. Changes made on your own machine in Obsidian will not be automatically sync'd to the website (more on that soon). Download [here](https://obsidian.md/).

### Node.js and Git
You will also need to download and install node.js, npm, and git. Note the steps are different for MacOS or Windows.

#### Windows 
Windows users should be able to just download and run the installers. 

1. Follow instructions here [node.js](https://nodejs.org/en))
2. Follow instructions here [Git For Windows](https://gitforwindows.org/))

#### MacOS Users

You need to follow these steps as well. 

1. Open the application Terminal.
2. Run this command to install Homebrew: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
3. Run these commands to install node and npm `brew install node; brew install npm`. This may take some time.
4. Run this command to install git: `brew install git`. 

### Final Installation Steps

Open your favorite application (if you haven't already): Terminal on Mac OS or Command Prompt or Powershell on Windows.

#### Clone the Repository
1. Clone the repository to your computer with this command: `git clone https://github.com/garrett-laroy-johnson/chaosmotic-systems-wiki`
2. Run the command: `cd chaosmotic-systems-wiki`
3. Run the command (that means type and hit enter): npm i. This will install all the requisate files to build out the site from our Obsidian files.

#### Add the Repository to the Obsidian as a Vault

Open Obsidian and click "open folder as vault". Find your `chaosmotic-systems-wiki` folder (probably `users/yourusername`, click into it, and select `content`.

## Editing Workflow
Here is a workflow that will allow you to preview how the changes will appear on the public website before you commit them.

1. As a matter of habit, everytime you open Obsidian, you should also open terminal. Write 
2. Before editing, run the command `npx quartz sync`.This will synchonize the materials on your local machine with the version on GitHub which is shared by the class.
3. When complete, run `npx quartz build --serve`.
4. Open your browser and navigate to [http://localhost:8080]([url](http://localhost:8080)) to see a preview of the site that reflects your local changes.

 Now you are free to edit away and add your content!

### Uploading
Upload often.

1. Now that we've made some changes we want to make public, return to your terminal window. Type `ctrl + c` to stop the local webserver.
2. Run `npx quartz sync`. Your changes should soon be live. You can double check that this was successful by going to the GitHub page and looking at the `content` directory. Your files should be present there.

Note: If you get an error, it may be because you have not logged into your GitHub account and gotten privleges. You will need to login to your account in the Termainl, and also need to have communicated your GitHub ID to the course TA who will add you as a collaborator on the repository (you will need to confirm this in an email). 
