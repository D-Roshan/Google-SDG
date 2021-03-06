# Google-SDG Project


![Python minimum version](https://img.shields.io/badge/Python-3.8%2B-brightgreen)

ABOUT PROJECT:

The goal of this app is to facilitate awareness of every Communicable diseases that is trending in a country by providing relevant data like for example the number of infected people, ect. The app acts as an easy place to find the needed information and updates and it also provides and SOS feature and a tab for advices. For this demo, we used Mauritius as an example and COVID-19 as a main priority and other recently trended diseases such as Malaria and more. The app could be further improved to provide more information such as a map and more.

TO OPEN THIS PROJECT:

git clone the repository to your workspace:
```
git clone https://github.com/D-Roshan/Google-SDG.git
```
Install the required dependencies:
```
pip install -r requirements.txt
```

Next, open the `dinfosease` folder in Android Studio.
Sync project with gradle files if necessary.
Choose emulator, then click on run project and project will be opened and run
OR you can simply install the `.apk` file in your Android Phone.

ABOUT APP:

Navigate the app by interacting with the relevant buttons to explore the various tabs and functionalities.
![](https://i.imgur.com/hvzsFoC.jpg) 
![](https://i.imgur.com/1sDB7te.jpg)
![](https://i.imgur.com/Ouyyyqe.jpg)

ABOUT BACKEND:

The python script `main.py` mines data from the web then appends the data to a JSON file.
Firebase realtime database was initially used to upload the JSON data but the database was disabled due to billing problems, so,
a free alternate hosting service was used to host the generated json file from the python script for the app to retrieve and display. Firebase codes have been kept commented for references.

MORE INFO IN VIDEO: 

[![Google DSC Solution Challenge - DinfoSEASE](https://img.youtube.com/vi/vfsoC0O5C8w/maxresdefault.jpg)](https://youtu.be/vfsoC0O5C8w)
