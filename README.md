# Setting UP ubuntu machine after the installation

## 1 . Install git 
sudo apt-install git-all
configure default branch strategy : git config --global init.defaultBranch master


## 2 . Setting up Intellij Community Edition
Download IntelliJ IDEA Community Edition:
    Go to the IntelliJ IDEA download page.(https://www.jetbrains.com/idea/download/?section=linux)
    Choose the "Community" version and download the .tar.gz file for Linux.
Extract : 
tar -xvzf ideaIC-*.tar.gz
Run : 
cd idea-IC-*/bin
./idea.sh
To make IntelliJ IDEA easier to launch, you can create a desktop shortcut by running the setup wizard in IntelliJ after the first launch.
