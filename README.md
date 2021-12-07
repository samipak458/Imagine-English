# Imagine English

![webpg](https://images.samimunir2002.repl.co/imagine.png)

## About Imagine English

Imagine English is an attractive and user-friendly website that provides free English learning tutorials and lectures for basic, intermediate, and advanced levels.  It is a useful website with exercises within the website so students do not have to download or print activities. This can reinforce what is being studied during lessons.

The course content is up to date and designed according to the requirements of the user. It is geared for those who want to practice their English vocabulary as well as grammar. Users have to give a small aptitude test to determine their level of proficiency. They are directed towards the tutorial section according to their proficiency level. Hands-on exercises are provided after each tutorial to test the understanding of the user. Sign-up is needed with an email address to start learning. 

Grammar, regardless of the country or the language, is the foundation for communication. Grammar rules can help learners develop the habit of thinking logically and clearly. After studying grammar, learners are able to become more accurate when using a language. Users will learn grammar rules, vocabulary, common English phrases that are used in daily life and how they can avoid mistakes while speaking.



## Guide to Contribute on this repository

### Fork a project

You can make a copy of the project to your account. This process is called forking a project to your Github account. On Upper right side of project page on Github, you can see -

![](https://camo.githubusercontent.com/543094fcf43ed95ec9bc3692f8e5f4e22ea6b795955d0e04e7d27850190cfc28/68747470733a2f2f692e696d6775722e636f6d2f50306e366639372e706e67)

Click on fork to create a copy of project to your account. This creates a separate copy for you to work on.

### Clone the forked project

You have forked the project you want to contribute to your github account. To get this project on your development machine we use clone command of git.

`$ git clone https://github.com/samipak458/Imagine-English.git`
Now you have the project on your local machine.

### Add a remote (upstream) to original project repository

Remote means the remote location of project on Github. By cloning, we have a remote called origin which points to your forked repository. Now we will add a remote to the original repository from where we had forked.

`$ cd <your-forked-project-folder>` `$ git remote add upstream  https://github.com/samipak458/Imagine-English.git`

You will see the benefits of adding remote later.

### Synchronizing your fork

Open Source projects have a number of contributors who can push code anytime. So it is necessary to make your forked copy equal with the original repository. The remote added above called Upstream helps in this.

`$ git checkout main`  `$ git fetch upstream`  `$ git merge upstream/main`  `$ git push origin main`

The last command pushes the latest code to your forked repository on Github. The origin is the remote pointing to your forked repository on github.
