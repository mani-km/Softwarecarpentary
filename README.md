# Softwarecarpentary
The workshop organised by GSLS, learning git, github, gitbash shell
It contains great and multi-use software but need time to learn for performaning data analysis.

## Usage of software
Description

### First section
description of first tol

### second tool
description of second tool

###Third Tool
description of fancy tool

## Things to do in the future 

-item1
-item2
-item3

need to check the changes you made

-item4

##########workshop learning material
Software Carpentry workshop Würzburg: 2020-11-17  - 2020-11-19

This pad is synchronized as you type, so that everyone viewing this page sees the same text. This allows you to collaborate seamlessly on documents.

Use of this service is restricted to members of The Carpentries community; this is not for general purpose use (for that, try https://etherpad.wikimedia.org ).

Code of Conduct https://software-carpentry.org/conduct/  => Be excellent to each other!

All content is publicly available under the Creative Commons Attribution License: https://creativecommons.org/licenses/by/4.0/

 ----------------------------------------------------------------------------
 
Material for recap and more:

    Schedule: https://swcarpentry-wuerzburg.github.io/2020-11-17-Wuerzburg/

    Shell: https://swcarpentry.github.io/shell-novice/

    Python: https://swcarpentry.github.io/python-novice-inflammation/

    Git: https://swcarpentry.github.io/git-novice/

    Pandas: https://pandas.pydata.org/

    HackyHour: https://hackyhour.github.io/Wuerzburg/

    Project Z03: http://z03.physik.uni-wuerzburg.de (within the uni network)


Misc.
You are on linux and face issues with the zoom whiteboard? try to install and run xcompmgr

Shell
https://swcarpentry.github.io/shell-novice/data/data-shell.zip
Man pages
https://man7.org/linux/man-pages/

Commands we learned:

    ls

    pwd

    cd

    mkdir

    rmdir

    touch

    rm

    cp

    mv

    cat

    head

    tail

    wc

    sort

    grep


Other important things:

    * glob

    > redirect

    | pipe

    {} brace expansion


How to filter rows in a file depending on the value in a column:
awk -F"\t" '$3>112' table.tsv >table_filtered.tsv

Python
https://swcarpentry.github.io/python-novice-inflammation/data/python-novice-inflammation-data.zip
https://swcarpentry.github.io/python-novice-inflammation/code/python-novice-inflammation-code.zip
MPI4Py: https://mpi4py.readthedocs.io/en/stable/
Jupyter Hub is not restricted to Python, there's even a Mathematica Kernel: https://github.com/jupyter/jupyter/wiki/Jupyter-kernels

Useful Python libraries

     [pandas](http://pandas.pydata.org/)

     [numpy](http://www.numpy.org/)

     [scipy](https://www.scipy.org/)

     [Biopython](http://biopython.org/) 

     [scikit-learn](http://scikit-learn.org) - Machine learning

     [scikit-image](http://scikit-image.org/) - Image analysis

    [matplotlib](http://matplotlib.org/) - 2D plotting library

    [seaborn](https://seaborn.pydata.org/) - statistical data visualization

     [bokeh](http://bokeh.pydata.org)

    [statsmodel](http://statsmodels.sourceforge.net/)


git
Create a github account: ( https://github.com/ )
If you want to keep your E-Mail Address private on github, see these resources:
https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address

git commands:

    To check whether git is properly installed

    git --version

    Tell git your name

    git config --global user.name "Max Lastname"

    Tell git your email address

    git config --global user.email "name@domain.de"

    Setting correct line ending for Windows

    git config --global core.autocrlf true

    Setting correct line ending for Linux/Mac

    git config --global core.autocrlf input

    Telling git which text editor to use (e.g. nano)

    git config --global core.editor "nano -w"

    View configuration

    git config --list

    Initialize new repository

    git init

    See status of git repository

    git status

    Stage file(s) for commit

    git add <list of files>

    Commit staged changes

    git commit -m "<commit message>"

    View commit history

    git log

    View changes not staged

    git diff

    View changes of specified commit

    git show <commit> [filename]

    View changes since specified commit

    git diff <commit> [filename]

    "Travel in time"

    git checkout <commit> [filename]

    Move HEAD

    git checkout <commit>

    get remote changes

    git pull

    publish changes to the world

    git push

    get a repository from the internet

    git clone <repo>


Choosing a license: https://choosealicense.com/

"Error Recovery" https://xkcd.com/1597/

GUIs: https://git-scm.com/downloads/guis

Markdown, a markup language: https://en.wikipedia.org/wiki/Markdown

Text Editors / IDEs (integrated development environment)
Try for something that suits your needs and taste. It should ideally have features like autocompletion and syntax highlighting.

    [vim](http://www.vim.org/)

    [emacs](https://www.gnu.org/software/emacs/)

    [gedit](https://wiki.gnome.org/Apps/Gedit)

    [kate](https://kate-editor.org/)

    [Spyder](https://pythonhosted.org/spyder/)

     [PyCharm](https://www.jetbrains.com/pycharm/)

    [Atom](https://atom.io/)


Ideas for the last day

    gitlab (Physics Department specific)

    gitlab pipelines + LaTeX

    bash: xargs + parallelization (maybe with rsync)

    More Plotting with Python

    Project Management with gitlab

    Logarithmic colorbar Plots with python (Charlotte B.)

    The Python process module (Charlotte B.)

    bash: combining it with awk and perl (Charlotte B.). Covered by Markus in a break? yes!

    Python function

    Stand-alone Python scripts

    self-defined GUIs?

    Intro Spyder

    Spotlight Software Engineering/Design(Marius Fuchs, teaches from 14-16)

    Python + HDF5

    Your own project!


"Schedule"/Building Blocks for the last session *Vote required*<

    gitlab: 1 + 2 + 5: Vote: 1,1,1

    Processes + commandline Arguments: 7 + 10: Votes 1,1,1,1,1,1,1,1,1,1

    self-defined GUIs via easyGUI: 11 : Votes 1,1

    bash scripts + xargs + rsync: 3 : Votes,1

    Python + HDF5: Votes 1,1

    Plotting Data: Votes


#Schedule for the last day
14:00-15:30 1 + 2 (session for all)
15:30-16:00 Break
16:00-17:00 Separate Sessions with Breakout Rooms (ASK TO BE ASSIGNED!)
17:00-17:15 Spotlight Software Design(Each instructor quickly gives his thoughts)
17:15-17:30 Wrapup, Post-workshop Survey
