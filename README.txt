README.txt

PieOptions

From 'Swift Swift View Controllers' by Steven Lipton

With Git information paragraphs

App info: go down to NOTES: section

Author: Frank Cipolla


After looking at a few online tutorials for command line and GUI based (SourceTree) GIT when using distributed collaboration and came to the conclusion that is is far easier to use command line if utilizing branching to track changes.  SourceTree released a new update and it is somewhat easier to use now.

The best learning aid for the command line I found is: https://git-scm.com/.

the GitHub UI is also good for managing the remote repository.


The Pro Git book is available to read online off this site:

The URL for the book is: https://git-scm.com/book/en/v2

===============================  IMPORTANT READ THIS ===========================
Your Identity
The first thing you should do when you install Git is to set your user name and email address. This is important because every Git commit uses this information, and it’s immutably baked into the commits you start creating:
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
Again, you need to do this only once if you pass the --global option, because then Git will always use that information for anything you do on that system. If you want to override this with a different name or email address for specific projects, you can run the command without the --global option when you’re in that project.
Many of the GUI tools will help you do this when you first run them.

Your Editor
Now that your identity is set up, you can configure the default text editor that will be used when Git needs you to type in a message. If not configured, Git uses your system’s default editor.
If you want to use a different text editor, such as Emacs, you can do the following:
$ git config --global core.editor emacs ( or whatever editor you like )



Using Git to access and contribute to this project:

1. Clone (fork) the project.  This will make a complete copy of the repository to your computer.  You will now have a local repository and a reference to the remote repository.

2. Create a Branch and locate yourself in the branch.  This will isolate your changes / additions in the repositories while you work on them.

Reference these to help you:

https://guides.github.com/introduction/flow/

https://git-scm.com/book/en/v2/Git-Branching-Branch-Management

https://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project



NOTES:

In section 7 the book is out of date and I referenced his web article:
https://makeapppie.com/2016/09/05/an-introduction-to-size-classes-for-xcode-8/

Then I bought his Kindle Book: 'Practical Autolayout for xcode 8'

This works with varying traits (regular and compressed) in orientations

He recommends reading the View Controller Programming Guide and particularly the Traits Section.  I concur.

An important note from Programming Guide:

IMPORTANT
Never assume that your app will be displayed with a specific size class on a device. Always check the size class found in an object’s trait collection when making decisions about how to configure that object.

Reference this in the Programming Guide :
Adapting Presented View Controllers to a New Style which tells you how to use delegates to programmatically over-ride default behaviors. 


 
