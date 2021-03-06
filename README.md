# MedTracker


This app is designed for people who need to take a lot of
different medication everyday (like chronically ill people). You enter your
treatment plan through the settings and the app will then keep track of every medication and
how many days it will still last, updating it automatically every day. I wrote this application in <b>Java</b>, using <b>Android Studio</b>.



You can swipe through the different months on the calendar.
Every colored point corresponds to the day where that specific medication will
run out:

<img src="https://imgur.com/LMArYgu.png" width="300" />       <img src="https://imgur.com/0iXvw0H.png" width="300" />


You can use the '+' buttons to restock your medication in terms of how many packs you bought. 
After clicking 'Save', the app updates the remaining days for each medication:

<img src="https://imgur.com/0TrAqvf.png" width="300" />       <img src="https://imgur.com/JsGjG0n.png" width="300" />






You can change your treatment plan as well as initialize the app in the settings.
To initialize, enter your treatment plan (Name, Pills/Box, Pills/Day) and how many pills you already possess
for each medication (initial number of pills). Finally, enter your current unix timestamp. The app will take that timestamp
as a reference to calculate how much medication remains, everytime you open the app.

<img src="https://imgur.com/wm3T3dk.png" width="300" />


# <b>Credits: </b>
  
  The calendar module that I used is the "CompactCalendarView", by SundeepK (https://github.com/SundeepK/CompactCalendarView), which has shown to be 
  a more elegant solution than the proprietary Android Studio CalendarView.
