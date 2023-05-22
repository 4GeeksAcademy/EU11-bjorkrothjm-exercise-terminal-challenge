<!--hide-->
# Command Line Preview
<!--endhide-->
# Command Line Challange Answers

1. Print current directory path
pwd 
2. List all the files from the current directory including the hidden ones
ls -a
3. Now list all the files inside the project, recursively (all files in the hierarchy)
ls -R
4. Clear all the clutter from the command line
clear
5. Go to the last level below the small-name folder and show on the console the content of the trophy.txt file
cat small-name/ + press tab until trophy.txt shows up
6. Move one level up and get to the funcode directory and list all files with javascript typical extension
ls funcode/*.js
OR
find funcode -name '*.js'
7 Create a new directory inside funcode
mkdir funcode/the-most-funny/not-that-funny

8. Create a copy of the-most-boring-text.txt (you can find it within /boringfolder/'s children) and name it lol.txt
// Finding where the file is:
ls -R boringfolder 
// Copying the file 
cp boringfolder/event-more-boring/i-can-believe-how-boring/the-ulrimate-boring-inception/the-mostboring-text.txt boringfolder/event-more-boring/i-can-believe-how-boring/the-ulrimate-boring-inception/my-copy.txt

9. Move funcode/kids.jpg inside funcode/images/hello/
mv funcode/kids.jpg funcode/images/hello/kids.jpg

10. Remove the "small-name" directory
rm -r small-name 
// Note: "rmdir small-name" will not work because the directory contains files

11. Print in the command line the content of the-ultimate-joke.txt
cat funcode/the-most-funny/lol/the-ultimate-joke.txt

12. Remove all the contents from the boringfolder, they are extremely boring...
cd boringfolder + rm -r

13. Open the file kamehameha/dragon-ball-jokes.md using the VI command line text editor
vi kamehameha/dragon-ball-jokes.md

14. Update the file...
vi kamehameha/dragon-ball-jokes.md 
+ : d (on the first line)
+ : w
+ : q


# Command Line Preview
This command line challenge is designed to help you become familiar with the bash/command line. The challenge goes over the most used commands every developer needs to know in order to succeed in real life.

> :exclamation: We strongly recommend reading [The Command Line lesson](https://4geeks.com/lesson/the-command-line-the-terminal) on the 4Geeks.com platform.

💻 The challenge is built for computers using the Linux bash. Use Codespaces or Gitpod if you are running on Windows (instructions below). 

## 🌱  How to start this project

### 👩‍🎓 Students and Teachers must follow this step:

This project comes with the necessary files to start working immediately.

We recommend opening this very same repository using a provisioning tool like [Codespaces](https://4geeks.com/lesson/what-is-github-codespaces) (recommended) or [Gitpod](https://4geeks.com/lesson/how-to-use-gitpod). Alternatively you can clone it on your local computer using the `git clone` command. 

This is the repository you need to open:

```
https://github.com/breatheco-de/excercise-terminal-challenge.git
```

**👉 Please follow these steps on** [how to start a coding project](https://4geeks.com/lesson/how-to-start-a-project).

💡 Important: Remember to save and upload your code to GitHub by creating a new repository, updating the remote (`git remote set-url origin <your new url>`), and uploading the code to your new repository using the `add`, `commit` and `push` commands from the git terminal.

## Only teachers must follow this step:

#### 1) Install the packages.

```sh
$ npm install
```

#### 2) Run the presentation.

```sh
$ npm run start
```

# Start Playing!

Follow the presentation for a better experience.

This and many other projects are built by students as part of the 4Geeks Academy [Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) by [Alejandro Sanchez](https://twitter.com/alesanchezr) and many other contributors. Find out more about our [Full Stack Developer Course](https://4geeksacademy.com/us/coding-bootcamps/part-time-full-stack-developer), and [Data Science Bootcamp](https://4geeksacademy.com/us/coding-bootcamps/datascience-machine-learning)
