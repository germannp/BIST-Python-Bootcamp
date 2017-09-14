# 0 Preliminary Requirements for BIST Python Bootcamp  
  
Welcome to the BIST Python Bootcamp! So, what do we hope to achieve? Well for those who have used spreadsheet like Microsoft Excel for their data analysis, we hope to convert you to the power of using a programming language. This will hopefully allow you analyse much larger data sets than Excel can handle and allow a lot more different types of analysis and visualisation of the data. Though it might not seem like it, when you are beginning to learn to program, trust us when we say that as you become more proficient in programming you will actual find it easier and quicker to work with data this way. Hopefully by the end of this bootcamp, you will have a firm grasp of programming in Python, with good skills in applying this to data analysis and visualisation. Going forward you should have a strong grounding in programming and might wish to develop skills in data mining or computational modelling - useful skills to have in Science and many other careers.  

Before the bootcamp it will be very helpful if you could install Python 3 on your computer as described in **Section 0.1**, which should set you up nicely for the course and hopefully any data analysis you need to do during your Masters.  

In **Section 0.2** we have included some some resources for those coming to Python from either Matlab or R, or those who are new to programming. These are optional, you do not need to access them, as we will cover this and more during the bootcamp.  

As well as teaching you to program in Python, we also hope to teach you good programming practices like version control. This will include setting up a Github account, as described in **Section 0.3**. We will also cover this during the course, though you are more than welcome to try it out before hand and indeed download the course's contents before the start.  


## Installing Python3 on Your Computer  

You may already have Python3 installed on your computer (especially if you have a Mac or Linux distribution). However we would like you install [Anaconda Python 3.6 version - www.continuum.io/downloads](https://www.continuum.io/downloads), which nicely supports Windows, Mac and Linux machines and will include the right version of Python and all the scientific packages you need for this bootcamp. If you have problems with the installation and Google is no help, we will do our best to help you in the first session of the bootcamp. If you do not have a computer which you can bring to the bootcamp, please contact the administrators of this course.  

Now that you have Python installed on your computer, you may want to try it out. The easiest way is to launch *Anaconda Navigator* from your applications. In the navigator, double click on *qtconsole* to launch a window which you can input some code. Why not try out typing these and hitting enter after each one:

+ `2+2`
+ `print('Hello, world!')`
+ `import numpy`

If you got no errors you are more than ready to start the bootcamp! If not, no worries, we will cover it in the bootcamp. Now to exit *qtconsole* you can type `exit()` and hit enter.  


## Additional Resources  

+ For those new to programming and would like to try out Python before the bootcamp, we can recommend [www.codecademy.com/learn/python](https://www.codecademy.com/learn/python). Though we will cover the relevant content in this online course, and more, in the bootcamp.
+ For those coming from Matlab or R, there is a useful summary of how the commands for each programming language compare at [mathesaurus.sourceforge.net/matlab-python-xref.pdf](http://mathesaurus.sourceforge.net/matlab-python-xref.pdf).
+ Finally, for those already experienced in Python, you will be welcome to hopefully learn some new tricks. Also all students are encouraged to work together and help other students in the bootcamp.


## Git

Git is a version control software that lets you keep track of the history of your code, data, and documents. To download the course materials run `$ git clone https://github.com/germannp/BIST-Python-Bootcamp.git`.

### Versioning
You can view your changes to tracked files using `$ git diff` and get an overview using `$ git status`. You can then stage changes using `$ git add file-name` and create a checkpoint with the staged changes using `$ git commit -m "Commit message"`. This message should be short, if you want to add more information skip the `-m` and your default editor will open, where you can enter an additional commit message. To move or delete tracked files use `$ git mv` and `$ git rm` respectively. To see the history with `$ git log` and go back to any point using `$ git checkout #commit-hash`.

### Remote Repositories
Your local git repository is connected to a remote repository, e.g. the one you cloned (which is the default). Remove repositories are often hosted by providers like [GitHub](https://github.com) or [GitLab](https://gitlab.com), which provide a graphical interface and further functionality for collaboration (e.g. an issue tracker or a wiki). You can download updates using `$ git pull` and upload your changes using `$ git push` if you have the rights.

### Stash and Branch
If you need to quickly interupt your current taks to work on something else you can save and remove your unstaged changes with `$ git stash` and restore them with `$ git stash apply`. If you want to keep track of several versions of your software, e.g. a stable version and one (for each new feature) under development, you can use [branches](https://git-scm.com/docs/git-branch).

### Course Material
In setting up this course, we have stored all the course material on [github - github.com/germannp/BIST-Python-Bootcamp](https://github.com/philipp-germann/BIST-Python-Bootcamp). In the bootcamp we will be using github to help with version control of the code you will produce, if you want to make your own account and experiment with Guthub before the bootcamp, please do.  
  
As said above, the main takeaway is to install Python3 on your computer, everything else is optional. We look forward to seeing you at the bootcamp.