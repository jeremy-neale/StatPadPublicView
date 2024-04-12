# Stat-Pad
https://stat-pad.com

This is the public view of my personal NBA website stat-pad.com, which is closed source for security reasons.

Background:
As soon as I started learning how to code, I realized how powerful it was and I could now build virtually anything I wanted to. I love basketball and especially love data and analytics, so this project was a fun hobby I created outside of my schoolwork and never intended for it to try to make a profit or even to just build my resume. I simply just wanted to do it. I started it off by having it scrape a website and pull a players points per game. From there, I kept building it until it was a fully functional GUI that could take input of a player name, year, and stat and return the correct answer. Next, I decided to make a stats guessing game that was the basis of Stat-Pad. My friends were in my dorm and I decided to launch the game and play it with them and they really seemed to enjoy it.  I wanted to let them to be able to play on their own, but realized that sending them my Python code and having them run it on their computer was unreasonable and not a very practical solution. Making the game into a website seemed like a logical next step, so I scrapped the GUI and began a gresh start with building it as a website in mind. Stat-Pad was born.

Technical details:
The website uses Python and Flask for the back end. It uses Flask to launch HTML pages, where I use CSS and some JavaScript to style the website and make functions. The player stats database is generated with a generating function and stores the data locally along with a log file. 
The leaderboards are set up in an AWS database and access by pull requests in the Python code.
The domain was purchased and is owned by me. I use DigitalOcean connected to my GitHub to launch the code from my repository and configure DigitalOcean by using a DockerFile with the needed imports. I use the python code to launch a locally-hosted website to make developer changes and can test anything I need to before launching it live to the web.

Please reach out to statpadwebsite@gmail.com for further questions.
