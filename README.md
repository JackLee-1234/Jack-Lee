
# Autonomous Architect Certificate into Billing

#### This is a mobile application developed for Quantity Surveyor (QS) as well as the Architect to use for Joint Inspection and Attaching & Updating Architect Certificate (AC) Information.

##### Author: Jack Lee, David Choy

##### Supervised By: Poo Shah Wae

##### Technical Mentor: Foo Lun Leong

  

## Prerequisites Setup

### Steps

#### 1. Install Polymer 3.0

- Install [Git](https://git-scm.com/download/win).
Once installed, type in cmd to confirm that Git is correctly installed:
```

	git --version

```
- Install [Node.js](https://nodejs.org/en/download/) based on your operating system, this will install npm as well.
- To check your operating system, right click on your **This PC** and click **Properties**.
- Sample image:
	![os](/ReadMe%20image/Operating%20System.png)

Press **Window Key** + **R** to start **Run**, and type in:
```

	cmd
	
```

**cmd** (command prompt) output sample: 
	![cmd](/ReadMe%20image/cmdInterface.PNG)

After installation, type in command below in cmd to confirm that npm is correctly installed:

```bash

	npm --version

```

sample:
	![cmdNpm](/ReadMe%20image/cmdNpm.PNG)

To confirm that Node.js is correctly installed:

```

	node --version

```

sample:
	![cmdNode](/ReadMe%20image/cmdNode.PNG)
	
- Install Polymer CLI.

To install Polymer CLI, run the following command:

```bash

	npm install -g polymer-cli

```

To confirm that the Polymer CLI has been correctly installed:

```bash

	polymer --version

```
sample:
 	![cmdPolymer](/ReadMe%20image/cmdPolymer.PNG)

#### 2. Install some useful software

- Microsoft Visual Studio Code from [here](https://code.visualstudio.com/download)




#### 3. Configure the username name and email address in CMD by running the following command:

```

git config --global user.name <username>

git config --global user.email <email-address>

```
##### Note: Change the value in `<username>` and `<email-address>`.
  
Verify your configuration by showing username and email:
```

git config user.name

git config user.email

```

sample:
 	![cmdGitConfig](/ReadMe%20image/cmdGitConfig.PNG)

#### 4. Clone project files from Titanfour Git Repository.

First we will create a folder by type in following commands:

```

cd \

mkdir <directory-name>

cd <directory-name>

```

in this sample, im using **DSU-6** as `<directory-name>`:
 	![cmdMkdir](/ReadMe%20image/cmdMkdir.PNG)


Next, we will clone the Polymer project into this folder:

```

git clone https://git.titanfour.com:6443/project/DSU-6.git

```

sample:
 	![cmdClone](/ReadMe%20image/cmdClone.PNG)

If you are successfully done, a folder name **DSU-6** will be created in your directory path, open it and open **NewMobileApp** folder:
	![directory](/ReadMe%20image/folder.PNG)

Click into the highlight path as in sample, and copy down the path:
	![cd-directory](/ReadMe%20image/cdFolder.png)

Back to your command prompt, and type in following command:

```

cd <the-path-you-copied-down>

```

In my sample, im using `<C:\DSU-6\DSU-6\NewMobileApp>` as my copied path:
	![cmdPath](/ReadMe%20image/cmdPath.PNG)

#### 5. Install all the neccessary modules by running the following command:

```

npm i

npm audit fix

```

#### OR

```

npm install

npm audit fix
```

##### Note: these commands may take up to 10 minutes to complete the process, be patient.

#### 6. Starting DSU-6 project

type in command below to serve the project:
```

polymer serve --port 8081

```
##### Note: Login to your CBD2_VPN before proceed to next step:

then, go to [here](localhost:8081)

press key **F12** to enter Console mode, and press key **Ctrl** + **Shift** + **M** to enter Mobile View.
##### Note: if key F12 do not entering Console mode, try press key Fn + F12.


#### 7. Have Fun! :smiley:

  

## Feature Enhancement Needed

#### 1. User accounts

#### 2. Digital Signature to sign off checklist

#### 3. Store Original AC Image

#### 4. Offline Data Storage & Online Data Syncing

#### 5. Progress update, add in `architect name` field

#### 6.