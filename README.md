# git-setup
What is Version Control?
Version control is a sytem that manages and tracks the changes to code or a documents.

What is version control used for??
In computing version control is use bassically to track and manage changes to a file, Mostly in collaborative projects like software development and Documentations that may need an update.

What is git?
Git is a distributed version control system(its free and open-source). It helps Developers to track changes to their code over time.

What is Git-Hub?

GitHub is a web-base platform that uses Git for version control, it is use for collaborative software development. It enables developers to store, manage and track changes to their code and also allows them to collaborate on projects.


What are the differences between Git and Github?
Git is a distributed version control system  built to help developers track and manage changes in their code. While, If Git is the engine of version control, GitHub is the garage where teams gather to build together. It builds on Git's local capabilities by offering a cloud-based platform for hosting Git repositories—turning individual efforts into collective progress.

Setting Git for the first time on linux

Installing git on Ubuntu

The first command to run on your terminal to intall git is;
$ sudo apt install git-all
after you have intall it you can check its version by typing : 
git --version on your terminal

The next thing is to create a Gidhub account, You can visit https://github.com/signup  to sign up.

Then next you need to configure your git to your GitHub information using :
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"


You can now proceed to generate a SSH key to connect to your GitHub.
You should run the following commands on the terminal(replace the email with your GitHub email):

ssh-keygen -t ed25519 -C "your.email@example.com"
Press Enter to accept the default file location.

You'll see:
Enter a file in which to save the key (/home/youruser/.ssh/id_ed25519):
Just press Enter.

When prompted for a passphrase, you can enter one or leave it blank and press Enter.

To add the SSH Key to GitHub
Display the key:

cat ~/.ssh/id_ed25519.pub
Copy the output (starting with ssh-ed25519).

Go to GitHub:

Click your profile then Settings then to SSH and GPG keys

Click New SSH key

Title: Something like Ubuntu SSH key or the name of your device.

Paste the key in the Key field and click Add SSH key.

From here your Git/GitHub is ready for use









