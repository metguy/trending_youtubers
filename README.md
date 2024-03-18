# *Trending YouTuber Data*
![alt text](https://images.pexels.com/photos/3227986/pexels-photo-3227986.jpeg)
### Project Overview
Here in this project we'll be exploring the data analysis of the most recent top YouTubers and their insights compared to 2023's top YouTubers. What led me to choose this topic was how often I found myself watching YouTube videos. When I have a lot going on at once, I tend to avoid NetFlix and streaming services of the like because I can easily binge watch a season in a couple of days. It's rather unhealthy and being preoccupied with wrapping up school among other things lately, I just don't have time for it so I avoid it like the plague! Instead, I'll watch YouTube. YouTube gives me a bit more control on the length of time for whatever video interests me and I do have a couple favorite YouTubers, myself! I thought it would be pretty interesting to see which YouTubers were consistently at the top and if any of my favorites made the list. I wanted to make this project user friendly so I gave step-by-step instructions and shared hyperlinks on how to perform this on multiple systems. So, without further a do, let's get to it and see what we find! <br>
### Install and Setup
For this project, I utilized Jupyter Notebook as my editor and Git as the terminal to setup the virtual environment. I recommend downloading both if not already installed on your system. 
* Click [here](https://github.com/git-guides/install-git) to install Git.
* For intructions on installing Jupyter Notebook, click [here](https://docs.jupyter.org/en/latest/install/notebook-classic.html). <br>
### Clone Project
1. Click on my highlighted repo and navigate to my github [respository](https://github.com/metguy/trending-youtube-videos).
2. From there, click on the green box that says, "**Code**", then under **HTTPS**, copy the url.
3. Open your terminal and type the command, "**jupyter notebook**"
4. Navigate to the directory you wish to clone the repo in.
5. Once there click on following from the top: *File>New>Terminal*
6. In the terminal check to make sure you're in the directory that you want to clone the repo into.
7. Now type, "**git clone** *paste my copied repo here*"
8. Hit Enter! Now you can create the virtual environment.
### Creating a Virtual Environment
Be sure to create and activate the virtual environment before running the project! This will save your system storage space and won't create any problems when running the project. Always deactivate the virtual environment when finished with the project.
#### For Windows:
1. Open the Git terminal by navigating to your File Explorer.
2. Navigate to the directory you cloned the repo into.
3. Right-click in the folder the repo is in and select, "**Show more options**".
4. Then click on, "**Open Git Bash here**".
5. In the git terminal, type the command, "**python -m venv .venv**"
6. Now to activate the virtual environment type, "**source .venv/Scripts/activate**"
7. You should now see **(.venv)** below your previous command.
8. You can now run the project worry free!
9. When done reviewing, return to the git terminal and simply type, "**deactivate**". <br>
#### For Linux/Mac:
1. Locate and launch the Bash terminal by searching for it in your desktop menu.
2. In the terminal type, "**python3 -m venv .venv**"
3. Activate the virtual environment by typing, "**source .venv/bin/activate**"
4. You should now see **(.venv)** after your previous command.
5. You can now run the project worry free!
6. When done reviewing, return to the terminal and simply type, "**deactivate**". <br>
#### Notable Features
* This README for starters!
* I read in two csv files using pandas.
* Cleaned and preped both datasets.
* Then joined the datasets using pandasql.
* I utilized Tableau to visualize my insights and give a better overview of the results.
* The virtual environment I intialized was a venv using the git bash terminal to create and activate it. To setup this environment, follow the instructions above. <br>
#### Quick Note
I've added comments in the markdown cells throughout the setup of the project to explain the process taken within each step. This is to provide better readability and understanding while reviewing the work. I hope you enjoy the project!
#### Sources
Kaggle: [Top YouTubers Worldwide](https://www.kaggle.com/datasets/shiivvvaam/top-youtuber-worldwide) <br>
Kaggle: [Global YouTube Statistics 2023](https://www.kaggle.com/datasets/nelgiriyewithana/global-youtube-statistics-2023)