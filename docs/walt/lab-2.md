---
id: a-lab-2
---

## Create a Codespace

### A. Navigate to the repository

1. In your browser, open the fork of the animation repository

2. Find and click the green Code button, then click the small + icon.  This will create a new Codespace on the default branch (Master).

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
* The Codespace, the CLI and VS Code editor are configured
  * These are based on settings in the repo configuration files.
  * Finally, all commands specified in the settings file are run. 
  


### C. Note the URL change. 

Checkout the new URL in the browser address bar (it ends with .github.dev). This name is generated from your username, plus a random GitHub generated name.  

https://[username]-improved-robot-pqpjx7p9qvcrw6r.github.dev/

[<a href="walt/lab-3.html">Go to next lab</a>]
