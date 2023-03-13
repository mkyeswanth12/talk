# Talk
The Talk Chat Application is a command-line interface (CLI) tool for sending and receiving encrypted messages between two or more users on a local server.

![Screenshot_2023-02-22_06-51-20](https://user-images.githubusercontent.com/47426782/221023387-53e04ca0-955b-4295-b029-cbedf8397e87.png)

# Installation
To install and set up the Talk app on your Ubuntu system, follow these steps:

Clone this repository to your local machine.

Navigate to the cloned repository

Run the installation script with superuser privileges.

The first time you run the installation script, you will be prompted to enter the names of two users. Enter the names of the users and hit enter.

Wait for the script to complete the installation process. This may take a few minutes depending on your system's performance.

Once the script has finished, 
Move the talk sctipt to executibal location.

You can access the Talk app by executing the talk command in your terminal

`git clone https://github.com/mkyeswanth12/talk.git` \
`cd talk` \
`sudo chmod +x talk.install talk` \
`sudo ./talk.install` \
`sudo mv -f talk /usr/local/bin/` \
`talk`

# Requirements
Git \
Ubuntu Operating System \
MySQL Server 

Please make sure your system meets these requirements before running the installation script.

# Usage
When the application starts, you will be prompted to enter your name.
To send a message, type the message in the command prompt and press Enter.
To clear the chat history, type /clear and press Enter.
To view the available commands, type /help and press Enter.
To exit the application, type /exit and press Enter.
# Support
If you have any questions or issues with the Talk Chat Application, please contact the author@ mkyes.mkyc1@gmail.com

# Authors
[MK Yeswanth](https://github.com/mkyeswanth12) - Github Profile

# License
This project is licensed under the Apache License - see the LICENSE.md file for details.

