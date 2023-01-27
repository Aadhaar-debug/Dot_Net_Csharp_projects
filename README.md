# AUTOMATING RETRO GAMES USING THE REINFROCEMENT LEARNING 
## TEAM NAME - TEAM Trex

- TEAM LEADER - AADHAAR KOUL (5th semester cse dept)
- TEAM MEMBER - ARJUN CHARAK (5th semester cse dept)
- TEAM MEMBER - SHOBIT KITCHLOO (5th semester cse dept)
- TEAM MEMBER - SIDDHARTH BHAWANI (5th semester cse dept)
- TEAM MEMBER - ANIL KUMAR (5th semester cse dept)

CLASS COORDINATOR - ARJUN PURI

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Complete Automation of some of the most renouned game titles using the reinforcement learning.

- EQUAL CONTRIBUTION
- NO PLAGIARISM
- COPYRIGHT RESERVED TO MIET JAMMU 5TH SEMESTER CLASS A1 STUDENTS

## ABSTRACT


General game testing relies on the use of
human play testers, play test scripting, and prior knowledge
of areas of interest to produce relevant test data. Using deep
reinforcement learning (DRL), we introduce a self-learning
mechanism to the game testing framework. With DRL, the
framework is capable of exploring and/or exploiting the
game mechanics based on a user-defined, reinforcing reward
signal. As a result, test coverage is increased and unintended
game play mechanics, exploits and bugs are discovered in
a multitude of game types. In this paper, we show that
DRL can be used to increase test coverage, find exploits,
test map difficulty, and to detect common problems that
arise in the testing of first-person shooter (FPS) games.In
this paper, we study applying Reinforcement Learning to
design a automatic agent to play the game Super Mario
Bros. One of the challenge is how to handle the complex
game environment. By abstracting the game environment
into a state vector and using Q learning — an algorithm
oblivious to transitional probabilities — we achieve tractable
computation time and fast convergence. After training
for 5000 iterations, our agent is able to win about 90
percent of the time. We also compare and analyze the choice
of different learning rate (alpha) and discount factor (gamma)


## Tech

- PYTHON - V3.10 , 3.8 AND 3.7
- PYTHON IDE

## Specifications (Minimum requirement)

- RAM - 2GB
- PROCESSOR - CORE 2 DUO OR HIGHER FOR Q LEARNING TABLE PLOTTING
- WINDOWS VERSION - 10 OR HIGHER
- PYTHON INTERPRETER VERSION - PYTHON 3.7 AND PYTHON 10.0
- INTERNET CONNECTIVITY - NOT REQUIRED 

NOTE : To install some of the packages the internet connectivity might be a requirement.

## IMPLEMENTATION
# The below given implementation is done for the snake game , so use the given below instructions for your benifit.

Open up the IDE command terminal . In our case we have used the VSCODE IDE and install the following packages:
- pygame
```
pip install pygame
```
- numpy
```
pip install numpy
```
- torch
```
pip install torch
```
- matplotlib
```
pip install matplotlib
```



* After the above are executed head on to the agent.py file and run the python code. A pygame window should appear with the snake game on it 
* let it run and generate some of the punishment and rewards for the until it maintains a Q- table .
* At a certain point the snake should be able to get the rewards all the time with less errors
* At this stage the snake Ai will be trained to play the all on its own.


## DOCUMENT AND THE PPT FILE CAN BE FOUND IN THIS REPOSITORY ONLY JUST CHECK THE REPOSITORY CONTENTS ABOVE 


# SAMPLES / PICTURES 

![Code Sample]([https://github.com/Aadhaar-debug/PYTHON_PROGRAMMING_5TH_SEMESTER_PROJECT/blob/main/Screenshots/Screenshot%20(316).png])
![Initial Training]([https://github.com/Aadhaar-debug/PYTHON_PROGRAMMING_5TH_SEMESTER_PROJECT/blob/main/Screenshots/Screenshot%20(317).png])
![Rewards and Punishments]([https://github.com/Aadhaar-debug/PYTHON_PROGRAMMING_5TH_SEMESTER_PROJECT/blob/main/Screenshots/Screenshot%20(318).png])



# First Contributions

This project aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

_If you're not comfortable with command line, [here are tutorials using GUI tools.](#tutorials-using-other-tools)_

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

#### If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/this-is-you/first-contributions.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.




## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> to Contributors list"
```

replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll encounter often as a contributor!

Celebrate your contribution and share it with your friends and followers by going to [web app](https://firstcontributions.github.io/#social-share).

You could join our slack team in case you need any help or have any questions. [Join slack team](https://join.slack.com/t/firstcontributors/shared_invite/zt-vchl8cde-S0KstI_jyCcGEEj7rSTQiA).

Now let's get you started with contributing to other projects. We've compiled a list of projects with easy issues you can get started on. Check out [the list of projects in the web app](https://firstcontributions.github.io/#project-list).

### [Additional material](additional-material/git_workflow_scenarios/additional-material.md)

## Tutorials Using Other Tools

| <a href="gui-tool-tutorials/github-desktop-tutorial.md"><img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100"></a> | <a href="gui-tool-tutorials/github-windows-vs2017-tutorial.md"><img alt="Visual Studio 2017" src="https://upload.wikimedia.org/wikipedia/commons/c/cd/Visual_Studio_2017_Logo.svg" width="100"></a> | <a href="gui-tool-tutorials/gitkraken-tutorial.md"><img alt="GitKraken" src="https://firstcontributions.github.io/assets/gui-tool-tutorials/gitkraken-tutorial/gk-icon.png" width="100"></a> | <a href="gui-tool-tutorials/github-windows-vs-code-tutorial.md"><img alt="VS Code" src="https://upload.wikimedia.org/wikipedia/commons/2/2d/Visual_Studio_Code_1.18_icon.svg" width=100></a> | <a href="gui-tool-tutorials/sourcetree-macos-tutorial.md"><img alt="Sourcetree App" src="https://wac-cdn.atlassian.com/dam/jcr:81b15cde-be2e-4f4a-8af7-9436f4a1b431/Sourcetree-icon-blue.svg" width=100></a> | <a href="gui-tool-tutorials/github-windows-intellij-tutorial.md"><img alt="IntelliJ IDEA" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/IntelliJ_IDEA_Icon.svg/512px-IntelliJ_IDEA_Icon.svg.png" width=100></a> |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [GitHub Desktop](gui-tool-tutorials/github-desktop-tutorial.md)                                                                                             | [Visual Studio 2017](gui-tool-tutorials/github-windows-vs2017-tutorial.md)                                                                                                                          | [GitKraken](gui-tool-tutorials/gitkraken-tutorial.md)                                                               | [Visual Studio Code](gui-tool-tutorials/github-windows-vs-code-tutorial.md)                                                                                                                  | [Atlassian Sourcetree](gui-tool-tutorials/sourcetree-macos-tutorial.md)                                                                                                                                      | [IntelliJ IDEA](gui-tool-tutorials/github-windows-intellij-tutorial.md)                                                                                                                   |
添加内容


## License

MIT

**Free Software, Hell Yeah!**
