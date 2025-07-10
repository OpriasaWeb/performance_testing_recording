# 📈 BlazeMeter Performance Test Recording
This guide walks you through how to record a performance test using the BlazeMeter Chrome Extension, and export it as a .jmx file for use in Apache JMeter.

🛠️ Requirements
✅ Google Chrome browser

✅ BlazeMeter Chrome Extension

✅ Apache JMeter installed (optional for viewing/editing .jmx files)

🔴 Step-by-Step: Record a Performance Test
Install the BlazeMeter Chrome Extension

Click here to install

Pin the extension for easy access.

Login (Optional but recommended)

You can sign in with your BlazeMeter account for cloud features, but local recording and exporting is free and doesn’t require login.

Start Recording

Click the BlazeMeter icon → Press "Start Recording".

Open a new tab and perform your typical user actions (e.g. login, browse pages, fill forms).

Stop Recording

Return to the BlazeMeter extension and press "Stop".

Export to JMeter

After stopping the recording:

Click "Download JMX" or "Export to JMeter".

Save the .jmx file to your local machine.

🧪 Run the Test in Apache JMeter
Optional, if you want to edit or run the test in JMeter manually.

Open Apache JMeter.

Click File → Open and select the .jmx file.

(Optional) Adjust thread groups, add assertions, listeners, or timers.

Click Start ▶️ to run the test.