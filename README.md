# Learn `python` for the Duke of Edinburgh bronze challenge

I am a Y9 student from Essex, UK. I am preparing for participating in the [Duke of Edinburgh](https://www.dofe.org/about/) bronze challenge in 2024.
I have decided to learn to write code in Python for my 'skill' challenge, and I will use GitHub to record my progress for my assessor.

I start almost from scratch, so my objectives are not very ambitious:
- to learn some Python,focused on data analysis (I like basketball, so it will be mostly about sports stats)
- to learn to work using version control in GitHub
- to learn Markdown and the use of Notebooks to give context to my code

I will record my progress below in diary format.

## Nov 12, 2023

- I set up an account in GitHub
- I downloaded GitHub desktop
- I learned what a repository and commit is.
- I learned a bit of GitHub markdown
- I have set up the environment manager Anaconda in my Acer Chromebook 314
- I have started to learn to use the `pandas` library

## Nov 25, 2023

- Anaconda is going to be my environment manager.
- JupyterLab is going to be my IDE (interactive development environment).
- GitHub is going to be my version control system.

- An IDE is an application that helps develop software by providing a code editor, debugging software, and a system to run the code to check it works.
- An Environment Manager is an application that helps develop software by providing a controlled environment for the interpretation of the code: I will write my code in Python 3 and will use some specific libraries, like `pandas`, `matplotlib` and `nba_api`), and Anaconda will make sure that my code will be interpreted with the appropriate versions of Python and those and other libraries.
- A version control system will allow me to save my work without eliminating earlier versions, so I can go back in time and recover an older version of my code if I make a mistake. This will also help me keep a log of my progress for my DofE assessor.

My first aim is to set up my workflow. I can't yet use GitHub Desktop to synchronise my code repository in GitHun with the code in my chromebook.
That is what I will try oi resolve today. I am going to test other software, as proposed [here](https://www.systemadmin.uk/other/using-git-on-a-chromebook/).

The software proposed in that link unfortuntley is only acccesable with the operative system Ubuntu but the operative system i have right now is chromeOS. both are versiions of Linux however i am still not able to run GitKraken and GitAhead in my system.

I have read in [this question in Reddit](https://www.reddit.com/r/github/comments/mrssml/comment/guptdqt/) that another way to do this is directly from my IDE, using "GitHub integration". I am going to try this.

I have tried to install in my Anaconda enviroment two differnt jupyterlab-github

I have tried installing anaconda environment
- jupyter-github.
- jupyter-git.

But this did not work, because I am using Anaconda cloud, and I do not have the permissions to install anything new.
So in my next session I will try:
- set up my Anaconda cloud account to allow adding extensions.
- set up a local Anaconda environment where I run JupyterLab in my computer, so I have control over what I install.

## Jan 13 2024

It is clear now that we cannot run Python locally in my computer. For this, we would need a version of ChromeOS that allows "using Linux" and my computer (an Acer Chromebook 314) is not in [the list of Chromebooks that can support that version of ChromeOS](https://sites.google.com/a/chromium.org/dev/chromium-os/chrome-os-systems-supporting-linux).

So we are going to look for an online platform that allows to code in Python using my computer just as a terminal.
We are looking for a platform that:
- Allows me to control my environment, so I can use the NBA scraping libraries.
- Has integration with GitHub to make my code nicely visible to my DofE assessor.

We start today by considering [this list of recommended 'Python online compilers'](https://noeticforce.com/python-online-compiler-interpreter-code-editors):
- Paiza.io: this has GitHub integration but we did not like the interface; besides, it did not seem to have many of the libraries we need available, nor can we add more.
- Trinket.IO: all the usual moduels for data analysis and visualisation seem avalable, (import pandas, import numpy, import scipy, import sklearn) so far so good, however there seems to be no GitHub integration.
- Google Colab: Only Notebook formats, it seems, and there is no way to add 'exotic' modules like `nba_scraper`, and no GitHub integration that we could obviously see
- Replit: the interface looks like a full IDE, it has GitHub integration, and it can install new libraries (including `nba_scraper`) so we could make the environment we need. It is commercial but there is a free plan. This is the one we are going to try first, though it does not seem to have an obvious way to use Notebooks.

#### Progress so far with Replit
Setting up a 'project' or 'repl' in Replit was easy. We quickly imported my existing GitHub repository as a repl, and after some experimenting, managed to 'push' and 'pull' to GitHub from Replit.
Unfortunately, running code is not straight-forward at all:
- the 'run' button/command runs the code of a single, specific file within the 'project'! This file is specified in a configuration file `.replit`, and it took us some time to find out how to set this up.
- even after this was sorted out, the 'virtual machine' that runs our code seems to struggle to find the appropriate language/files/etc to run properly.

All this because my ChromeBook is not modern/powerful enough!

(ó﹏ò｡)

We still need to sort some of these problems but today it's been over 2h so we are going to leave this here.

## Jan 21 2024

Session started: &nbsp;&nbsp;&nbsp;&nbsp; 15:30

Session ended: &nbsp;&nbsp;&nbsp;&nbsp; 17:15

We have given up on trying to find an cloud python compiler so I can use my Chromebook after trying Anaconda Cloud, Google Colab and Replit. None of these allow me to install `nba-scraper`, which I will need to collect NBA data, nor any other library not in their preset environments. 

Today we have:
- set up GitHub, Anaconda manager and Jupyterlab on my father's computer as the problem before was my chromebook.
- practised using version control making changes to my repository's README file:
  - change in GitHub (remote) -> commit -> fetch for desktop-> pull to desktop
  - change in desktop (local) -> commit -> push to remote

We have installed nba_scraper; however, I have put that matter aside and started learning how to use the library `pandas`.




