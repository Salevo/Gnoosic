<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Song recommendation App Gnoosic
*Sarah Vonderberg*

*[DAFT, Remote Campus & MAR21]*

## Content
- [Project Description](#project-description)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
I developed a simple app that will be able to recommend you a song depending on your input. If the song is in the current billboard Top 100 you will be recommended a song from there. If the song is not in the cureent billboard Top 100 I will use the spotify API to recommend you a song according to their music rating algorithm.


## Workflow
1) Organisation and scope of the project on trello
2) github repo setup
3) webscraping the billboard top 100, saving to a dataframe
3) prototype app (recommendation if the song is in the billboard top 100)
4) config file for spotify api
5) webscraping the big data from spotify for my machine learning algorithm
6) machine learning algorithm
7) finish app
8) update readme
9) video presentation


## Organization
I organised my project with trello into tasks which are either in progress, done or in review. I also assigned deadlines to some tasks in order to be reminded.

I tried to keep my github repo as clean and lean as possible, so it contains:
- a gitignore
- Prototyp App (inludes: the code for the app, the code for the spotify music clustering algorithm)
- a readme file
- Spotify.csv (a csv file with the necessary spotify songs for my machine learning algorithm)
- webscraping_datframes (the code used for collecting the data needed for spotify.csv)

## Links

[Repository](https://github.com/Salevo/Gnoosic)  

[Slides](https://drive.google.com/file/d/1mmOFZpkBeuvlXcW-ySUY82JALJ4sTN6V/view?usp=sharing)

[Trello](https://trello.com/b/U06GB3Eg/gnoosic)  
