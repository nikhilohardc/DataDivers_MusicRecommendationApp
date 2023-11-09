
# Data Divers: Music Recommendation App
The GitHub respository for the Data Divers: Music Recommendation App capstone project

Tech Lead: Andrew Mark Dale || 100491442<br />
Team Member: Abednego Ndegwa || 100941581<br />
Team Member: Ashutosh Pandey || 100941194<br />
Team Member: Darren Saguil || 100458141<br />
Team Member: Nikhil Lohar || 100925168

## Application name: RecNN

Reasoning: Portmanteau of Recommendation + Nearest Neighbours and a play on reckoning. Since we're calculating or estimating recommendations for a particular song, we feel this is perfect.

Most of the work has been done without constantly uploading to GitHub. We will correct this for future portions of the project.

Uploaded documents:
Kick-Off Meeting PowerPoint, MVP PowerPoint

## **MVP**
To run the project:

Get the code by either cloning this repository using git

    git clone https://github.com/TLAndrewMarkDale/DataDivers_MusicRecommendationApp.git


... or [downloading source code](https://github.com/TLAndrewMarkDale/DataDivers_MusicRecommendationApp/archive/refs/heads/dev.zip) as a zip archive

## Front-end

Demo : http://soundsuggest.online

###  Prerequisites

You will need [Node.js](https://nodejs.org) version 18.0 or greater installed on your system.

### Setup

Once downloaded, open the terminal in the project directory and navigate to music-recommendation-frontend , and install dependencies with:

    npm install

After all the dependencies is being installed. Then start the frontend app with:

    npm run dev

This hosts the front-end on http://localhost:3000/.

### Screenshots

**Home page**
![Home page with search bar and 10 trending songs](https://github.com/TLAndrewMarkDale/DataDivers_MusicRecommendationApp/blob/dev/screenshot/Home.png)

**Home with search result**
![When a user enter upto 3 letter the song suggestion are been showed which contains those word](https://github.com/TLAndrewMarkDale/DataDivers_MusicRecommendationApp/blob/dev/screenshot/Home%20with%20search%20bar.png)

**Recommendation page**
![After selecting first song from search result we got the following recommendation using KNN algorithm](https://github.com/TLAndrewMarkDale/DataDivers_MusicRecommendationApp/blob/dev/screenshot/Recommendation.png)

## Back-end

###  Prerequisites

You will need [Python](https://www.python.org/downloads/) version 3.10.12 or greater installed on your system

### Setup

Once downloaded, open the terminal in the project directory and navigate to music-recommendation-backend , and install dependencies with:

    pip install flask
    pip install nump
    pip install flask-cors
    pip install scikit-learn


After all the dependencies is being installed. Then start the backend app with:

    python flask_NN.py

This hosts the python back-end on localhost:5000.
