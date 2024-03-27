# ***Trending YouTuber Data***
![alt text](https://images.pexels.com/photos/3227986/pexels-photo-3227986.jpeg)

### Project Overview
Here in this project we'll be exploring the data analysis of the Top YouTubers 6 months a part, from July 2023 to January 2024. What led me to choose this topic was how often I found myself watching YouTube videos. When I have a lot going on at once, I tend to avoid NetFlix and streaming services of the like because I can easily binge watch a season in a couple of days. It's rather unhealthy and being preoccupied with wrapping up school among other things lately, I just don't have time for it so I avoid it like the plague! Instead, I'll watch YouTube. YouTube gives me a bit more control on the length of time for whatever video interests me and I do have a couple favorite YouTubers, myself! I thought it would be pretty interesting to see which YouTubers were consistently at the top within a half year period and if any of my favorites made the list. I wanted to make this project user friendly so I gave step-by-step instructions and shared hyperlinks on how to perform this on multiple systems. So, without further a do, let's get to it and see what we find! <br> <br>

#### Click the link below for a quick look at my Tableau Dashboard: <br>
* [YouTuber Visuals](https://public.tableau.com/views/YouTuberVisuals/YouTuberVisuals?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link) <br> <br>

### Data Dictionary
I've listed two data dictionaries below giving a description on the column names and categories.
|<p>**Column Titles**</p>|<p></p><p>**Description**</p>|
| :-: | :-: |
|'23/'24 YouTubers|YouTubers of 2023/2024|
|'23/'24 Subs|Subscriber count of each YouTuber|
|'23/'24 Rank|How each YouTuber ranked based on subscriber count|
|'23/'24 Category|Category of YouTuber's channel|
|'23/'24 Country|Country YouTuber's channel originates from|
|'23 Uploads|Total number of videos uploaded on the channel|
|'23 Video Views|Total views across all videos on the channel|
|'23 Pop.|Total population of the country|
|'24 Avg. Views|Average number of views on the channel|
|'24 Avg. Likes|Average number of likes on the channel|
|'24 Avg. Comments|Average number of comments on the channel| <br>

|<p>**Category**</p>|<p></p><p>**Description**</p>|
| :-: | :-: |
|Music & Dance|In relation to music and/or dance|
|Educational|In relation to learning material|
|Film & Animation|In relation to movies and/or shows|
|Entertainment|In relation to a variety of categories such as challenges/react videos/gaming/random vlogs|
|Sports|In relation to mainly sports|
|Gaming|In relation to streaming live or non-live games|
|DIY & Tutorials|In relation to do it yourself videos|
|News & Politics|In relation to mainly news & politics|

### Install and Setup
For this project, I utilized Jupyter Notebook as my editor and Git as the terminal to setup the virtual environment. I recommend downloading both if not already installed on your system. 
* Click [here](https://github.com/git-guides/install-git) to install Git.
* For intructions on installing Jupyter Notebook, click [here](https://docs.jupyter.org/en/latest/install/notebook-classic.html). <br>

### Clone Project
1. Click on my highlighted repo and navigate to my github [respository](https://github.com/metguy/trending-youtube-videos).
2. From there, click on the green box that says, "**Code**", then under **HTTPS**, copy the url.
3. Open your *command prompt* (Windows users) or *terminal* (Linux/Mac users) and type the command: <br> `jupyter notebook` <br> It should pull up in your web browser after this command.
4. Navigate to the directory you wish to clone the repo into. I recommend creating a folder with my username and choosing this as your directory. The directory could look something like this: *Documents/metguys_project*
5. In Jupyter Notebook, click on the following from the top: **File>New>Terminal**
6. In the terminal under jupyter notebook, check to make sure you're in the directory that you created to clone the repo into.
7. Now type: <br> ```git clone <paste my copied repo here>```
8. Hit Enter! Now you can create the virtual environment.

### Creating a Virtual Environment
Be sure to create and activate the virtual environment before running the project! This will save your system storage space and won't create any problems when running the project. Always deactivate the virtual environment when finished with the project. <br>

#### For Windows:
1. Open the Git terminal by navigating to your File Explorer.
2. Navigate to the directory you cloned the repo into.
3. Right-click in the folder the repo is in and select, "**Show more options**".
4. Then click on, "**Open Git Bash here**".
5. In the git terminal, type the command: `python -m venv .venv`
6. Now to activate the virtual environment type: `source .venv/Scripts/activate`
7. You should now see **(.venv)** below your previous command.
8. In the terminal type: <br> `pip install -r requirements.txt`
9. You can now run the project worry free!
10. When done reviewing, return to the git terminal and simply type: `deactivate` <br>

#### For Linux/Mac:
1. Locate and launch the Bash terminal by searching for it in your desktop menu.
2. In the terminal type: `python3 -m venv .venv`
3. Activate the virtual environment by typing: `source .venv/bin/activate`
4. You should now see **(.venv)** after your previous command.
5. In the terminal type: <br> `pip install -r requirements.txt`
6. You can now run the project worry free!
7. When done reviewing, return to the terminal and simply type: `deactivate` <br>

### To Run Project:
After completing the steps above, open the **2023_YouTuber_Analysis.ipynb** notebook and at the top select: *Run>Restart kernel and run all cells*. Repeat this process for both **2024_YouTuber_Analysis** and **Combined_YouTuber_Analysis** notebooks. Then, look through the notebooks and see how it was all done!

### Notable Features
* Annotated code in Jupyter Notebook, wrote clear code comments, and introduced this README section for better readability.
* Read in two csv files using pandas.
* Cleaned and prepped both datasets.
* Concatenated the datasets using pandas.
* Utilized Tableau, and Matplotlib to visualize my insights and give a better overview of the results.
* The virtual environment I intialized was a venv using the git bash terminal to create and activate it. To setup this environment, follow the instructions above. <br>

#### Quick Note
I've added comments in the markdown cells throughout the setup of the project to explain the process taken within each step. This is to provide better understanding for both newcomers and pros alike, while reviewing the work. I hope you enjoy the project!

### Results and Evaluation
We were able to see a steady trend of the top 50 YouTubers from 2023 to 2024 in gaining a similar amount of subscribers, although one YouTuber stood out adding on an estimated total of 70,100,000 subscribers from then to now! That specific YouTuber being MrBeast. This blew my mind so I double checked the data and sure enough, the information is correct! Some other insights I gathered was which countries had the most popular YouTubers over this half year period, that being in order from most to least: <br> 
|<p>**Country**</p>|<p></p><p>**Total YouTubers**</p>|
| :-: | :-: |
|India|19|
|United States|17|
|South Korea|3|
|Russia|2|
|Pakistan|2|
|Argentina|1|
|Belarus|1|
|Brazil|1|
|Canada|1|
|Chile|1|
|El Salvador|1|
|Japan|1|
|Mexico|1|
|Puerto Rico|1|
|Spain|1|
|United Kingdom|1| <br>

It makes sense India would take the lead since the overall population count is the highest in this dataset (and second highest in the world)!
Another neat insight was into the most popular categories with Music & Dance being at the top; followed in order (from least to greatest) by Educational content, Film & Animation, Entertainment, Sports, Gaming, DIY Tutorials, and News & Politics.

### Future Work
This project will be ongoing as I plan to add more visuals but also add in new data six months from now to get a more indepth analysis on the trends.
1. Go through and remove special characters in Jupyter Notebooks as best practice. This will entail me needing to recreate current Tableau visualizations, so it will be done after project deadline.
2. I'd like to add more worksheets to my Tableau Dashboard, creating visualizations with the columns '23 Uploads, '23 Video Views, '23 Pop, '24 Avg. Views, '24 Avg. Likes, and '24 Avg. Comments.
3. Extract data using an API or by other scrape methods from a website on the top 50 YouTuber stats in half a year.

### Sources
Here I've listed the sources for the uncleaned datasets I used in this project; along with the site sources of any missing or incorrect information requiring research. <br> <br>
<u>Kaggle</u>: <br> 
[Top YouTubers Worldwide](https://www.kaggle.com/datasets/shiivvvaam/top-youtuber-worldwide) <br>
[Global YouTube Statistics 2023](https://www.kaggle.com/datasets/nelgiriyewithana/global-youtube-statistics-2023) <br> <br>
<u>YouTube</u>: <br>
[SET India](https://www.youtube.com/channel/UCpEhnqL0y41EpW2TvWAHD7Q) <br>
[Kids Diana Show](https://www.youtube.com/channel/UCk8GzjMOrta8yxDcKfylJYw) <br>
[PewDiePie](https://www.youtube.com/user/pewdiepie) <br>
[Like Nastya](https://www.youtube.com/channel/UCJplp5SjeGSdVdwsfb9Q7lQ) <br>
[Vlad and Niki](https://www.youtube.com/c/VladandNiki) <br>
[BLACKPINK](https://www.youtube.com/channel/UCOmHUn--16B90oW2L6FRR3A) <br>
[Goldmines](https://www.youtube.com/channel/UCyoXW-Dse7fURq30EWl_CUA) <br>
[5-Minute Crafts](https://www.youtube.com/channel/UC295-Dw_tDNtZXFeAPAW6Aw) <br>
[Zee TV](https://www.youtube.com/channel/UCppHT7SZKKvar4Oc9J4oljQ) <br>
[Colors TV](https://www.youtube.com/channel/UC55IWqFLDH1Xp7iu1_xknRA) <br>
[El Reino Infantil](https://www.youtube.com/c/elreinoinfantil) <br>
[Dude Perfect](https://www.youtube.com/channel/UCRijo3ddMTht_IHyNSNXpNQ) <br>
[Infobells - Hindi](https://www.youtube.com/channel/UC1ciY6kR3yj3kaKZ6R7ewAg) <br>
[Marshmello](https://www.youtube.com/channel/UCEdvpU2pFRCVqU6yIPyTpMQ) <br>
[YRF](https://www.youtube.com/channel/UCbTLwN10NoCU4WDzLf1JMOA) <br>
[LooLoo Kids](https://www.youtube.com/channel/UC4NALVCmcmL5ntpV0thoH6w) <br>
[Get Movies](https://www.youtube.com/@getmovies) <br>
[Shemaroo](https://www.youtube.com/channel/UCF1JIbMUs6uqoZEY1Haw0GQ) <br>
[Badabun](https://www.youtube.com/@badabunOficial) <br>
[SonyMusicIndiaVEVO](https://www.youtube.com/@sonymusicindiaVEVO) <br>
[Toys and Colors](https://www.youtube.com/channel/UCgFXm4TI8htWmCyJ6cVPG_A) <br>
[A4](https://www.youtube.com/@A4a4a4a4) <br>
[ARY Digital HD](https://www.youtube.com/channel/UC4JCksJF76g_MdzPVBJoC3Q) <br>
[JuegaGerman](https://www.youtube.com/channel/UCYiGq8XF7YQD00x7wAd62Zg) <br>
[Mikecrack](https://www.youtube.com/Mikecrack) <br>
[Bad Bunny](https://www.youtube.com/channel/UCmBA_wu8xGg1OfOkfW13Q0Q) <br>
[Voot Kids](https://www.youtube.com/channel/UCJg19noZp7-BYIGvypu_cow) <br> <br>
<u>SPEAKRJ Stats</u>: <br> 
[BLACKPINK](https://www.speakrj.com/audit/report/UCOmHUn--16B90oW2L6FRR3A/youtube) <br>
[Goldmines](https://www.speakrj.com/audit/report/UCs570zdFq_NNA5OcV8chnHw/youtube/summary/2023-07-01/2023-07-31) <br>
[5-Minute Crafts](https://www.speakrj.com/audit/report/UC57XAjJ04TY8gNxOWf-Sy0Q/youtube/summary/2023-07-01/2023-07-31) <br>
[Justin Bieber](https://www.speakrj.com/audit/report/UCIwFjwMjI0y7PDBVEO9-bkQ/youtube) <br>
[T-Series Bhakti Sagar](https://www.speakrj.com/audit/report/UCaayLD9i5x4MmIoVZxXSv_g/youtube/summary/2023-07-01/2023-07-30) <br>
[LooLoo Kids - Nursery Rhymes and Children's Songs](https://www.speakrj.com/audit/report/UC4NALVCmcmL5ntpV0thoH6w/youtube/summary/2023-07-01/2023-07-31) <br>
[Taylor Swift](https://www.speakrj.com/audit/report/UCqECaJ8Gagnn7YCbPEzWH6g/youtube) <br>
[Ed Sheeran](https://www.speakrj.com/audit/report/UC0C-w0YjGpqDXGB8IHb662A/youtube) <br>
[Badabun](https://www.speakrj.com/audit/report/UCYWOjHweP2V-8kGKmmAmQJQ/youtube/summary/2023-07-01/2023-07-31) <br>
[A4](https://www.speakrj.com/audit/report/UC2tsySbe9TNrI-xh2lximHA/youtube/summary/2023-07-01/2023-07-31) <br>
[Bad Bunny](https://www.speakrj.com/audit/report/UCiY3z8HAGD6BlSNKVn2kSvQ/youtube/summary/2023-07-01/2023-07-31) <br> <br>
<u>HypeAuditor</u>: <br> 
[BLACKPINK](https://hypeauditor.com/youtube/UCOmHUn--16B90oW2L6FRR3A/) <br>
[Justin Bieber](https://hypeauditor.com/youtube/UCIwFjwMjI0y7PDBVEO9-bkQ/) <br>
[Taylor Swift](https://hypeauditor.com/youtube/UCqECaJ8Gagnn7YCbPEzWH6g/) <br>
[Ed Sheeran](https://hypeauditor.com/youtube/UC0C-w0YjGpqDXGB8IHb662A/) <br> <br>
<u>Worldometer</u>: <br>
[Puerto Rico Pop.](https://www.worldometers.info/world-population/puerto-rico-population/#:~:text=Puerto%20Rico%202023%20population%20is,(and%20dependencies)%20by%20population.) <br>
[Mexico Pop.](https://www.worldometers.info/world-population/mexico-population/#:~:text=Mexico%202023%20population%20is%20estimated,(and%20dependencies)%20by%20population.) <br>
[Belarus Pop.](https://www.worldometers.info/demographics/belarus-demographics/) <br>

## Licenses
For this github repository, the license used is an [MIT License](https://opensource.org/license/mit). <br>
For the, "*Top YouTubers Worldwide*" csv used in this project, a [CCO: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/) license was used.