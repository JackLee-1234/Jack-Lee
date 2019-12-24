
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

Type command below in cmd to confirm that npm is correctly installed:

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
  

#### 2. Install some useful software

- Microsoft Visual Studio Code from [here](https://code.visualstudio.com/download)

  

#### 3. Configure the username name and email address in CMD by running the following command:

```

git config --global user.name <username> user.email <email-address>

```
##### Note: Change the value in `<username>` and `<email-address>`.
  

#### 4. Clone project files from Titanfour Git Repository.

```

git clone https://git.titanfour.com:6443/project/DSU-6.git <directory-path>

```

##### `<directory-path>` is the path of the file you will like to save to.  Optional way is to leave blank in `<directory-path>`.

  

#### 5. Install all the neccessary modules by running the following command:

```

cd <your-project-file-path>

npm i

```

#### OR

```

cd <your-project-file-path>

npm install

```

#### 6. Starting DSU-6 project

```

cd <your-project-file-path>

polymer serve --open

```
#### 7. Have Fun! :smiley:

  

## Feature Enhancement Needed

#### 1. User accounts

#### 2. Digital Signature to sign off checklist

#### 3. Store Original AC Image

#### 4. Offline Data Storage & Online Data Syncing

#### 5. Progress update, add in `architect name` field

#### 6.
