# Software requirements and recommendations for EBIO 4420/5420 - Computational Biology

## DISCLAIMER:
I haven't tried every single link or installation method mentioned below this year.  Please let me know if links are broken or methods no longer work!

## For ALL, no matter what kind of computer and OS you have:
* Everyone will need a "text editor" for editing "plain text".  Chances are you already have at least a basic one on your computer, even if you have never used it.  You can edit plain text with a wide variety of software offerings (that's part of the beauty of plain text!).  On a Mac, you can use something like TextEdit.app (included with Mac OS),  TextWrangler (free download), or XCode (see below).  On a Windows machine, you can use something like Notepad, Notepad++, or any of many other offerings.  I recommend Notepad++.  For Linux users, there is gedit.  I welcome suggestions about what you like!  If you want to feel like true "programmer", you can try out various command-line editors, such as vim, atom, or emacs.  If things like that are intimidating, don't worry; you won't have to use them unless you want to (at least, not yet...).
* You will need a way to edit "markdown" files.  Since markdown is plain text, you can technically write and edit it in any plain text editor.  However, a markdown-friendly editor is very nice to have.  On Mac, Xcode works well for this, as does BBEdit [https://www.barebones.com/products/bbedit/download.html](https://www.barebones.com/products/bbedit/download.html).  I'm not sure about current offerings for Windows or Linux, but some Google searching on your part will likely lead to some suggestions.  You can also use a web-based platform such as StackEdit, [https://stackedit.io/app#](https://stackedit.io/app#), regardless of your OS.   
* Obviously, if you already have any/all of the required software installed on your computer, there is no need to re-install, though I do suggest updating if you haven't in a while.
* If you need me to provide you with a laptop computer for use in this class, please let me know.
* Everyone needs R and RStudio for this course, but the install procedures are slightly different for different operating systems (detailed below).

## For Mac Users only:
* Download and install XCode from the App Store.  Open XCode after it is installed and "agree" to the terms of use.  Once XCode is installed, it is a good idea to install "command line tools."  A decent guide for doing so is available at [http://railsapps.github.io/xcode-command-line-tools.html](http://railsapps.github.io/xcode-command-line-tools.html)
* Download and install Git. A decent guide can be found here: [https://www.atlassian.com/git/tutorials/install-git](https://www.atlassian.com/git/tutorials/install-git).  The installer itself can be found here: [https://sourceforge.net/projects/git-osx-installer/files/](https://sourceforge.net/projects/git-osx-installer/files/).  **NOTE:** In order to get the installer to open, you will likely have to `control-click` on the installer, and then choose `Open` when prompted.  (Otherwise, your Mac may refuse to open it because it is from an "unidentified developer".)
* Download and install R (*not* RStudio yet) by following instructions at [https://cran.rstudio.com/](https://cran.rstudio.com/)
* Download and install RStudio by following instructions at [https://www.rstudio.com/](https://www.rstudio.com/)
* **NOTE about using TextEdit**: If you plan to use TextEdit to create plain-text files, you will likely need to adjust the preferences in that application.  Open it, then choose "Preferences..." from the "TextEdit" drop-down menu near the upper left of the screen.  In preferences, choose the radio button for "Plain Text" (NOT rich text), and under "Options" I suggest UN-selecting all the check-boxes.

## For Windows Users only: 
* Windows users will need to emulate a UNIX-style terminal.  There are several ways to do this.  If you have a preferred method, please use it.  If not, for this class I suggest using git-bash as provided by "Git for Windows" at [https://git-scm.com/downloads](https://git-scm.com/downloads).  You can download it from that link and install with all defaults unless you have a good reason to using something besides the default settings. A screencast of how to download, install, and navigate in GitBash is available at [https://youtu.be/93c9Td5iHHY](https://youtu.be/93c9Td5iHHY)
* Download and install Base R:  [https://cran.r-project.org/bin/windows/base/](https://cran.r-project.org/bin/windows/base/)
* Download and install RStudio: [https://www.rstudio.com/](https://www.rstudio.com/)
* NOTE: git bash is a stripped down, minimalist UNIX-like experience for Windows users.  If you want a fully featured UNIX-terminal-like experience, you may want to download and install [cygwin](https://www.cygwin.com/), or you could go even one step further and create a virtual Linux machine using VirtualBox.  A YouTube video showing how to download, install, and navigate in cygwin is available [here](https://youtu.be/Yig-AL6bedc).

## For Linux Users only:
* Open a Terminal window and install Git by typing `sudo apt install git` at the command prompt
* Also using the Terminal, install R and RStudio.  Here are a couple sets of directions that should hopefully work.  Do NOT do both.  I'm just providing two here in case one of them doesn't work for you  . 
    1. [https://www.r-bloggers.com/how-to-install-r-on-linux-ubuntu-16-04-xenial-xerus/](https://www.r-bloggers.com/how-to-install-r-on-linux-ubuntu-16-04-xenial-xerus/)
    2. [https://linuxconfig.org/rstudio-on-ubuntu-18-04-bionic-beaver-linux](https://linuxconfig.org/rstudio-on-ubuntu-18-04-bionic-beaver-linux)
