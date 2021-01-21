# AviSOFT | Script to syncronise states between various applications

We can see from the script how we can connect to a mqtt server. Subcribe a topic , filter the data we are looking for, despite receiving 100-1000msg per second per topic.
Once we receive a a packet we can make decision and publish something onto another topic.

Making sure that we are maintaining states locally, as you can seen this script helps one to maintain same states on which the server is running on.
This scripts does override server states so as to make the system fail safe for hotel rooms.
