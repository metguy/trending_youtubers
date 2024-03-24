# *Trending YouTuber Data*
![alt text](https://images.pexels.com/photos/3227986/pexels-photo-3227986.jpeg)
### Project Overview
Here in this project we'll be exploring the data analysis of the Top YouTubers 6 months a part, from July 2023 to January 2024. What led me to choose this topic was how often I found myself watching YouTube videos. When I have a lot going on at once, I tend to avoid NetFlix and streaming services of the like because I can easily binge watch a season in a couple of days. It's rather unhealthy and being preoccupied with wrapping up school among other things lately, I just don't have time for it so I avoid it like the plague! Instead, I'll watch YouTube. YouTube gives me a bit more control on the length of time for whatever video interests me and I do have a couple favorite YouTubers, myself! I thought it would be pretty interesting to see which YouTubers were consistently at the top within a half year period and if any of my favorites made the list. I wanted to make this project user friendly so I gave step-by-step instructions and shared hyperlinks on how to perform this on multiple systems. So, without further a do, let's get to it and see what we find! <br>
***(Will be adding dictionary here for column abbreviations)***
### Install and Setup
For this project, I utilized Jupyter Notebook as my editor and Git as the terminal to setup the virtual environment. I recommend downloading both if not already installed on your system. 
* Click [here](https://github.com/git-guides/install-git) to install Git.
* For intructions on installing Jupyter Notebook, click [here](https://docs.jupyter.org/en/latest/install/notebook-classic.html). <br>
### Clone Project
1. Click on my highlighted repo and navigate to my github [respository](https://github.com/metguy/trending-youtube-videos).
2. From there, click on the green box that says, "**Code**", then under **HTTPS**, copy the url.
3. Open your *command prompt* (Windows users) or *terminal* (Linux/Mac users) and type the command: <br> "**jupyter notebook**" <br> It should pull up in your web browser after this command.
4. Navigate to the directory you wish to clone the repo into. I recommend creating a folder with my username and choosing this as your directory. The directory could end up looking something like this: "**Documents/metguys_project**"
5. In Jupyter Notebook, click on the following from the top: *File>New>Terminal*
6. In the terminal under jupyter notebook, check to make sure you're in the directory that you created to clone the repo into.
7. Now type, "**git clone** ***paste my copied repo here***"
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
8. In the terminal type: <br> "**pip install -r requirements.txt**"
9. You can now run the project worry free!
10. When done reviewing, return to the git terminal and simply type, "**deactivate**". <br>
#### For Linux/Mac:
1. Locate and launch the Bash terminal by searching for it in your desktop menu.
2. In the terminal type, "**python3 -m venv .venv**"
3. Activate the virtual environment by typing, "**source .venv/bin/activate**"
4. You should now see **(.venv)** after your previous command.
5. In the terminal type: <br> "**pip install -r requirements.txt**"
6. You can now run the project worry free!
7. When done reviewing, return to the terminal and simply type, "**deactivate**". <br>
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
Here I've listed the sources for the uncleaned datasets I used in this project; along with the site sources of any missing or incorrect information requiring research. <br> <br>
<u>Kaggle</u>: <br> [Top YouTubers Worldwide](https://www.kaggle.com/datasets/shiivvvaam/top-youtuber-worldwide) <br>
[Global YouTube Statistics 2023](https://www.kaggle.com/datasets/nelgiriyewithana/global-youtube-statistics-2023) <br> <br>
<u>SPEAKRJ Stats</u>: <br> 
[BLACKPINK](https://www.speakrj.com/audit/report/UCOmHUn--16B90oW2L6FRR3A/youtube) <br>
[Justin Bieber](https://www.speakrj.com/audit/report/UCIwFjwMjI0y7PDBVEO9-bkQ/youtube) <br>
[Taylor Swift](https://www.speakrj.com/audit/report/UCqECaJ8Gagnn7YCbPEzWH6g/youtube) <br>
[Ed Sheeran](https://www.speakrj.com/audit/report/UC0C-w0YjGpqDXGB8IHb662A/youtube) <br>
[Goldmines](https://www.speakrj.com/audit/report/UCs570zdFq_NNA5OcV8chnHw/youtube/summary/2023-07-01/2023-07-31) <br>
[5-Minute Crafts](https://www.speakrj.com/audit/report/UC57XAjJ04TY8gNxOWf-Sy0Q/youtube/summary/2023-07-01/2023-07-31) <br>
[T-Series Bhakti Sagar](https://www.speakrj.com/audit/report/UCaayLD9i5x4MmIoVZxXSv_g/youtube/summary/2023-07-01/2023-07-30) <br>
[LooLoo Kids - Nursery Rhymes and Children's Songs](https://www.speakrj.com/audit/report/UC4NALVCmcmL5ntpV0thoH6w/youtube/summary/2023-07-01/2023-07-31) <br>
[Badabun](https://www.speakrj.com/audit/report/UCYWOjHweP2V-8kGKmmAmQJQ/youtube/summary/2023-07-01/2023-07-31) <br>
[A4](https://www.speakrj.com/audit/report/UC2tsySbe9TNrI-xh2lximHA/youtube/summary/2023-07-01/2023-07-31) <br>
[Bad Bunny](https://www.speakrj.com/audit/report/UCiY3z8HAGD6BlSNKVn2kSvQ/youtube/summary/2023-07-01/2023-07-31) <br> <br>
<u>HypeAuditor</u>: <br> 
[BLACKPINK](https://hypeauditor.com/youtube/UCOmHUn--16B90oW2L6FRR3A/) <br>
[Justin Bieber](https://hypeauditor.com/youtube/UCIwFjwMjI0y7PDBVEO9-bkQ/) <br>
[Taylor Swift](https://hypeauditor.com/youtube/UCqECaJ8Gagnn7YCbPEzWH6g/) <br>
[Ed Sheeran](https://hypeauditor.com/youtube/UC0C-w0YjGpqDXGB8IHb662A/) <br> <br>
<u>Worldometer</u>: <br>
[Puerto Rico Pop.](https://www.worldometers.info/world-population/puerto-rico-population/#google_vignette)