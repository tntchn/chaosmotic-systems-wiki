　　　.   　　˚　✭　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　　✭　.　　. 　 ˚　.　c h a o s m o t i c 　　　.   　　˚　✭　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　　✭　.　　. 　 ˚　.　s y s t e m s 　　　.   　　˚　✭　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　　✭　.　　. 　 ˚　.　

Chaosmotic Systems: Culture, Cosmology, Computation is an MFA-level seminar taught by Garrett Laroy Johnson. It was taught for the first time at the School of the Art Institute of Chicago in the Art Technology / Sound Practices department during Fall 2024 semester. The course materials are public and can be accessed here.

This repository serves as an entry point for the course's collaborative wiki project. Students will contribute (5) 500-word articles about concepts, authors,

## Installation
### GitHub
GitHub Desktop is how you will grab changes ("fetch" and "pull", in Git terminology) made by classmates and then contribute your own material ("commit" and "push" in Git terminology. This workflow is setup so that your changes will automatically be reflected on the live and public wiki website after about a 15-minute delay.

1. Students should first make a GitHub account and download the GitHub desktop client. You can do both at www.github.com.
2. Open GitHub Desktop, Go to settings and sign in.
3. Copy the URL to this page. Go to file > clone repository. Note the location of the cloned repository, you will use it below.

### Obsidian
Obsidian is where you will add to the Wiki on your own machine. Changes made on your own machine in Obsidian will not be automatically sync'd to the website (more on that soon).

1. Download Obsidian.
2. Open the program and click "open folder as vault". This is where you need the location of your cloned repository .../chaosmotic-systems/content.
3. Edit away! You may want to consult some tutorials on Obsidian if you need help getting started, but it is really very straight forward.

### Node.js
You will also need to download and install [node.js]([url](https://nodejs.org/en)). 

## Getting GitHub Privleges
You will not be allowed to make changes to the GitHub by default. You need to send your username to the course TA, who will manually add you as a collaborator. Do this sooner rather than later!

## Making Edits and Uploading Content
After you've completed installation successfully, you can start here every time you sit down to make changes in the future.

### Editing Workflow
Here is a workflow that will allow you to preview how the changes will appear on the public website before you commit them.

1. As a matter of habit, everytime you open Obsidian and Github, you should click fetch origin or pull changes. This will synchonize the materials on your local machine with the version on GitHub which is shared by the class.
2. Open your favorite application: Terminal on Mac OS or Command Prompt or Powershell on Windows. You can do this by going to Github Desktop, navigating to the 'repository' tab and selecting 'Open in Command Prompt' or 'Open in Terminal'.
3. Run the command (that means type and hit enter): npm i. This will install all the requisate files to build out the site from our Obsidian files. Wait until that is complete.
4. When complete, run npx quartz build --serve.
5. Open your browser and navigate to http://localhost:8080 to see a preview of the site that reflects your local changes.

### Uploading
Note: Do not wait too long to commit and push your changes. If someone else is working on that article, you won't lose your changes, but you will need to work through the differences between them and that can be a pain. Focus on pushing commits that are complete thoughts, though not necessarily totally completed.

1. Now that we've made some changes we want to make public, it's time to go back to the GitHub Desktop client.
2. You'll notice a list of files which have been added or changed. Below that list you will need to enter some information. Give a quick summary (e.g. "added pages on Glissant's concept of opacity and abstraction in the films of Carlos Reygadas"). You can add a longer description if you like.
3. Now you'll notice a button below that field asking you to Commit to ___. Press that when you're ready.
4. Now you're ready to sent those up to the Server. Click Push origin.
5. Return to your terminal window. Type `ctrl + c` to stop the local webserver.
6. Run `npx quartz sync`. Your changes should soon be live.
