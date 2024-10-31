# Node JS public repo Hello World subscribe to my channel , thanks you

Simple node.js app that servers  "Welcome to CLOUD ASEEM  & Credit with Thanks to - A Monk in Cloud"

Great for testing simple deployments on Cloud

## Step 1: Install NodeJS and NPM using nvm
Install node version manager (nvm) by typing the following at the command line.

```bash
sudo su -
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
```
Activate nvm by typing the following at the command line.

```bash
. ~/.nvm/nvm.sh
```

Use nvm to install the latest version of Node.js by typing the following at the command line.

```bash
nvm install node
```

Test that node and npm are installed and running correctly by typing the following at the terminal:

```bash
node -v
npm -v
```

## Step 2: Install Git and clone repository from GitHub
To install git, run below commands in the terminal window:

```bash
sudo apt-get update -y
sudo apt-get install git -y
```

Just to verify if system has git installed or not, please run below command in terminal:
```bash
git — version
```

This command will print the git version in the terminal.

Run below command to clone the code repository from Github:

```bash
Git Clone : https://github.com/Aseemakram19/nodejs-on-ec2-youtube.git
Branch Master.
```

Get inside the directory and Install Packages

```bash
cd nodejs-on-ec2
npm install
```

Start the application
To start the application, run the below command in the terminal:

```bash
npm start
```

