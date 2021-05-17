# covid_slot_notifier
install python on your system
install the packages in requirement.txt

set the following parameters in line 10,11,12 in cowin.py
age: The age you are looking for vaccination
pinCodes : Pincode of your place
num_days: The number of days from today that you want to check availability for

set how frequent you want the script to run in line 74
timedelta(minutes=???)

run the script using 
python cowin.py

It will give notify you with music in "sample.mp3" once slots are available 
You can also change the music to any mp3 or wave file by giving the path in line 69
