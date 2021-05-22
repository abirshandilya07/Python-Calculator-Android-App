# Python-Calculator-Android-App
A Python BeeWare application that runs on android 

BeeWare is a relatively new framework used to make android or ios or windows application and also web apps 
It is an alternative to the kivy framework and is relatively simple...
Applications made in BeeWare give the native like feel as they use the platforms native UI toolkit


So, now lets go on with the commands..

#First, create a virtual environment..

1.pip install virtualenv
2.virtualenv environment_name
3.cd environment_name
4.cd Scripts
5.activate
6.cd..
7.pip install briefcase

Briefcase is the tool used for developing apps in BeeWare...

#Now for making a project write the following commands..

1.cd calculator
2.briefcase dev

if this opens the application in dev mode then you are ready for deploying it on mobile

#Follow these commands for deploying..

1.briefcase build android(this might take some time if its your first build)
2.briefcase run android

choose the emulator or the device connected..

and your app is installed!!
