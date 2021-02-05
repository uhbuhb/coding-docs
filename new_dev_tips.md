## Basic dev environment setup

#### INTRO

Useful tools/ideas to jumpstart the setup process, generally oriented towards 
python but not only. 

#### NOTE

These are keywords/ideas, not step by step instructions. 
Getting started guides should be searched on google.
#### TOOLS

+ Git 
    + Create ssh key - bc you don’t want to enter your user/password every time you clone/push code
        + https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
    + Configure editor - using vim as the git editor is a nice way to get familiar with vim without spending too much time on tutorials:
        + git config --global core.editor "vim"
+ Pyenv - “Simple python version management” 
    + https://github.com/pyenv/pyenv
+ Pipenv - improved package manager
    + https://pypi.org/project/pipenv/
+ IPython - improved interactive python
+ Pdbpp - improved pdb debugging
+ IDE - Choose one/two and learn them - 
    + PyCharm, VSCode are 2 popular modern ones with full UI, project support, virtualenv capabilities
    + Sublime text for the more minimalists
    + Vim/Gvim for the more hardcore
+ Tmux/tmate - terminal multiplexer
    + Multiple terminal panes in a window
    + Tmate - useful for pair programming

#### GENERAL TIPS
+ Project Structure
    + Python recommendation: https://docs.python-guide.org/writing/structure/
+ Code style guide:
    + https://www.python.org/dev/peps/pep-0008/

#### COMMON WORKFLOW
+  Clone/create the project
+  Create virtual environment (pipenv)
+ Install relevant python libraries from requirements/Pipfile
+ Run tests (to see everything is set up).
+ Git checkout new branch
+ Write code
+ Write tests
+ Build commits
+ Rebase
+ Push code
+ Open PR


#### GIT TIPS
These are also ideas. If something isn’t clear, time to hit google :)

+ A commit is an email. Should contain a subject line and then body with explanation.
    + Should include why you did something, not what you did. What you did is clear to see in the code. 
+ Never merge, only rebase
+ Name your branches with a common prefix so they’re easy to find
+ Useful flags:
    + --autosquash, --autostash
    + git commit --amend
    + git commit --fixup=hash234joi42h3h23
    + git rebase -i (interactive)

