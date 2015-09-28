# Phonegap / Estimote Beacon Project 

### Install Cordova
1. http://cordova.apache.org/docs/en/3.6.0/guide_cli_index.md.html#The%20Command-Line%20Interface

### Install Evothings Studio and Configure App in the IDE
1. https://evothings.com/download/
2. Download the Evothings App for iOS or Android
3. Clone this repo 
4. Go to the www folder. Drag and drop the index.html file in the Evothings Studio 
5. Open the file config.xml (located in your Cordova project folder) in a text editor. On this line, replace the start page of the Cordova project ("index.html") with the connect address of the Workbench (in your mobile app):

`<content src="index.html" />`

For example, if the address is "192.168.43.131:4042", you would enter this URL: 

`<content src="http://192.168.43.131:4042" />`

6. Load the Evothings iOS App on your phone. Make sure your computer and phone are on the same WIFI network. From the mobile app, scan for the Evothings workbench. It should connect immediately.
7. From the Evothings Studio on your computer, look for the index.html file you dropped in and hit the [ RUN ] button. The code should now execute on your mobile app and you can see the beacon signal. ALL DONE!


### Useful Items and Tools for Development
1. We may use some of this code - https://github.com/petermetz/cordova-plugin-ibeacon 
2. Some more javascript code - https://evothings.com/how-to-develop-beacon-apps-in-javascript-with-evothings-studio-and-estimote/


### Building the cordova app
1. https://evothings.com/doc/build/cordova-guide.html#SummaryOfBuildSteps