# Code 301 Pre-work: Intermediate Software Development

To get your laptop and yourself ready for the start of Code 301, there are a series of pre-work tasks to complete. They are all listed in this document.

 Note that these tasks have a corresponding assignment to submit in your Canvas course, but be aware that at the time you receive the link to this pre-work that the Canvas course may not yet be published, depending upon the timing of Admissions processes and when class begins. Typically, Canvas courses are published 5-7 days before class begins.

## Customize Canvas (Canvas assignment)

You will not be able to complete this assignment until the Canvas course is published; the details for fulfilling this assignment are located there.

## Setup of Your Laptop Dev Environment (Canvas assignment)

Completion of the following setup tasks are all to be submitted in a single Canvas assignment. Keep a log of any errors or difficulties you encounter, and include those with your submission.

### Install Atom

If you haven't already, install [Atom](https://atom.io). If you have used an advanced text editor like Sublime Text, then Atom will feel familiar to you. Atom is free, open-source, cross-platform, and has a wide array of useful plug-ins available. Please use Atom during Code 301. (If you are proficient with another text editor that you *love*, you may use that instead)

[Atom's documentation](https://atom.io/docs/latest) is top-notch. Review it now to familiarize yourself with the basics. Make sure you're looking at the docs for the latest version. If you find that you are unable to call atom in the terminal, you may need to enable shell commands through Atom by first opening it through your graphical desktop interface, and selecting `Install Shell Commands` in the drop-down menu.

### Install Node

*Note* If you get an error while installing these packages such as "try again as root/administrator", you may need to use the `sudo` command to get administrator access. For example `sudo apt-get install nodejs`.

#### Linux instructions

  To install Node, open your Terminal, and copy and paste the following line, then hit Enter:

  `sudo apt-get install nodejs`

  If this did not work, try the following:

  `curl -sL https://deb.nodesource.com/setup_5.x | sudo -E bash -`

  It will churn away for a while, and then once it's done you can run the following command:

  `sudo apt-get install nodejs`

  If, once again, you did not achieve success, try [these instructions to build from source](https://gist.github.com/toastynerd/d3e563522977f6750c32).

  Finally, `sudo apt-get install npm`

#### Mac instructions

  If you took Code 201, you should already have Homebrew installed. If you have not, follow the guide on [this page](https://github.com/codefellows/code-201-prework/blob/master/prework/mac/2_homebrew.md#install-homebrew).

  To install Node, open your Terminal, and enter:

  `brew install node`

#### Windows instructions

  To install Node, go [here](https://nodejs.org/en/download/), and then download and run the Windows Installer. Make sure you do not deselect any of the Node components such as NPM during the installation.

#### Verify the Node installation
Now let's verify that it is installed. Enter the following into your terminal:

`node -e 'console.log("works")'`

You should get a response that says "works". If not, try reinstalling Node again

### Install eslint and live-server Node packages

Now that you have Node installed, you can install Node packages using its package manager, **NPM**. Open your Terminal (Git Bash on Windows) and enter:

`npm -g i eslint live-server git-open`

You should see a lot of feedback as it installs.

### Verify the Node packages installation
Now let's verify that it is installed. Enter the following into your terminal:

`npm list -g --depth=0`

You should get a list back that includes `live-server` and `eslint`.

![](http://i.imgur.com/1ITioP1.png)

### What is this linter thing?

Linting is the process of running a program that will analyze code for potential errors. It is an important part of the quality assurance process.

> `lint` was the name originally given to a particular program that flagged some suspicious and non-portable constructs (likely to be bugs) in C language source code. The term is now applied generically to tools that flag suspicious usage in software written in any computer language.

That means the linter is your friend! It will help you write syntactically correct code, so you can catch errors in your text editor, rather than having to hop over the browser, refresh your page, and search for errors. Faster feedback makes for happier developers (that's you!).

### Install linter and linter-eslint Atom packages

For this next part, you will have Atom's package manager **apm** install some packages. Go [here](https://atom.io/docs/v0.194.0/using-atom-atom-packages#command-line) to verify it's enabled. Once you have verified that apm commands will work, enter this on your Terminal:

`apm install linter linter-eslint`

You should get two success messages while it installs the linter and linter-eslint packages.

### Verify the Atom packages installation

Enter the following into your Terminal:

`apm ls`  
You should get back a long list, and at the end you should receive a list of packages you installed for Atom.   
Linter and linter-eslint should be on that list, like in this screen shot:

 ![screen shot 2016-05-28 at 11 33 31 pm](https://cloud.githubusercontent.com/assets/12869788/15631728/a816191c-252c-11e6-8cb4-5c757f240a50.png)

### Make Sure Homebrew Is Up To Date

If... everything goes smoothly...

It's good to regularly check that your installation of Homebrew is current. On your command line, from any directory, enter the command

`brew update`

This is also a good time to make sure that your apps installed with Homebrew are up to date. Do this with the command

`brew upgrade`

Lastly, to verify that your system is current, run

`brew doctor`.

If things do not go smoothly, list the errors you received in your Canvas submission.

## Connect With Your Classmates (Canvas assignment)

You will be able to complete this assignment once the course Slack channel has been created, which typically happens 7-14 days before the first day of class. See the assignment in Canvas for more details.

## Codecademy: jQuery (Canvas assignment)

Complete all of the free portions of the Codecademy course in jQuery. The Canvas submission is a screenshot indicating that the course is complete.

## Bonus: Prework Extra Credit JavaScript Practice (Canvas assignment)

Details for completing this assignment can be found in Canvas after the course has been published.

---

Congrats! You're all done. :wink:
