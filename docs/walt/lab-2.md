---
id: a-lab-2
---

## Create a Codespace

When you want to work on a project, you can choose to create a new codespace or open an existing codespace. For this example you'll create a codespace on the main branch, but they can be created from any branch in the repository. We've found it best to work with a single codespace for training, and restart it when returning to the training session.

If you leave your codespace running without interaction, or if you exit your codespace without explicitly stopping it, the codespace will timeout after a period of inactivity and stop running. By default, a codespace will timeout after 30 minutes of inactivity.  

Any saved changes in your codespace will still be available when you next start it. Don't worry about timeouts; the codespace can be quickly restarted as needed.

💡 **Instructor tip:**

> Have the learner create the codespace on the main branch. From there, if necessary, they can change branches within the active codespace.

### A. Navigate to the repository

1. In your browser, open the fork of the animation repository

2. Find and click the green Code button, then select the Codespaces tab, and click the small + icon.  This will create a **new** codespace on the default branch (Master).

<img src='/assets/img/a-lab-01-01.png' alt="lab image" class="img-lab" >

### B. Wait! 

Creating the codespace takes a minute or so. 
	
<img src='/assets/img/a-lab-01-02.png' alt="lab image" class="img-lab" >
	
That's because there is a lot of actions happening. Here's the details if you are interested.


* A lightweight clone of the repository is created. 
  * This is based on the latest commit.
  * For performance reasons, the full history of the repo is added later.
* A dedicated VM is allocated.
  * This VM is setup with the default storage size (32GB, 64GB etc.)
  * This VM is setup with the default compute resources (2 core 4GB RAM, 4 core 8GB RAM etc.)
   * These defaults are defined in the repository.
* A docker container is created on the VM. 
* The codespace, the CLI and VS Code editor are configured
  * These are based on settings in the repo configuration files.
  * Finally, all commands specified in the settings file are run. 
  


### C. Note the URL change. 

Checkout the new URL in the browser address bar (it ends with .github.dev). This name is generated from your username, plus a random GitHub generated name.  

https://[username]-improved-robot-pqpjx7p9qvcrw6r.github.dev/

[Go to next lab ](/walt/lab-3.html)

