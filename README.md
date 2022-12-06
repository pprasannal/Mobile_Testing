# Mobile_Testing

I. Mobile App: - 

    Track the operation on the  given task use of “WORK TRACKER APP”. It will display how many tasks were done on particular day , month , year and week and it used to calculate the time taken for task to complete and it can use as a stopwatch before starting the working we open the app and calculate the time it took and addition operation we can add break time of each operation (optional). 

II. Choose Device: - Real/Physical device 

III. Website(APK): - https://apkpure.com/work-tracker/de.bigchipmunk.worktracker

IV. How to Execute the Operations – 

  1. Software Required: -  
  
    a. Katalon 
    b. Appium
    c. Node.js
    d. Java 

  2. Set Up: - open cmd...
    
    a. To check java installed successfully or not
        Java --version 
        Javac --version 
    
    b. To check node.js installed or not 
			  Node -v or 
			  Node –version
		
    c. To install appium 
			  npm -v 
			  npm install -g appium (or) npm install -g appium@XXXX (version)
		
    d. open katalon set the path location of Appium in –
			   windows > katalon system preferences > katalon > mobile > path (c: /user /…. /Appdata /Roaming/npm /node_modules /Appium) > apply > okay 
		
    e. set the real device to the system – 
			  connect the USB cable to phone on one side and connect another side to the system once  it connect set PTP transformations , phone – go to developer option > enable USB dubbing > install via USB > USB debugging(security settings) 
	  
    f. check the device connected or not – 
			  open cmd and set path to adb directory (C:\Users\............\.katalon\tools\android_sdk\platform-tools) once it got set write “adb devices” it shows the real device serial number which got connected to system. 

V. Functionality Testing: - 

    1. CreateTaskTime – create the time taken to complete the given task 
    2. VerifyTaskTime – to check the given task is present in day or not (need to verify with task name) (we can check in either way how may tasks are present in particular day or monthly or yearly or weekly).
    3. DeleteTaskTime – delete the entire tasks in the work tracker app 

VI. Execution: -
 
    1. After the setup is done, open the project – File>open>project Folder (saved location)
    2. In start application set the apk file path
    3. Once phone got connected, Run the tasks in android, it will show the available real devices which connected to the system select the device 
    4. Start the Execution
