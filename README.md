# Creating Your First Azure Virtual Machine: A Beginner’s Guide

This README provides a quick reference for the commands used in the full article, which guides you through creating an Azure Virtual Machine and hosting a simple React web application.

**For the complete step-by-step tutorial, please visit the Medium article:** [Creating Your First Azure Virtual Machine: A Beginner’s Guide](https://theek.medium.com/creating-your-first-azure-virtual-machine-a-beginners-guide-3777540baeaa)

## Command Cheat Sheet

Here's a list of the commands used in the article for easy reference:

```bash
# Update package lists
sudo apt update

# Install Node.js and npm
sudo apt install nodejs npm

# Check Node.js version
node -v

# Install curl (if not already installed)
sudo apt install curl

# Install nvm (Node Version Manager)
curl [https://raw.githubusercontent.com/creationix/nvm/master/install.sh](https://raw.githubusercontent.com/creationix/nvm/master/install.sh) | bash

# Source bashrc to use nvm
source ~/.bashrc

# Install the latest LTS version of Node.js using nvm
nvm install --lts

# Fix npm audit issues
npm audit fix --force

# Check if Git is installed
git --version

# Install Git (if not already installed)
sudo apt install git

# Clone your React repository from GitHub (replace <> with your repo URL)
git clone <>

# Navigate to your project folder (replace <your-project-folder-name>)
cd <your-project-folder-name>

# Install project dependencies
npm install

# Start the React development server
npm run dev
