**Raspberry Pi Motion Detection<br/>**
This project is a Python-based home security system that uses a Raspberry Pi, a PIR motion sensor, and the Raspberry Pi Camera Module to detect motion, capture an image, and send an email alert with the captured photo as an attachment.<br/>

**How It Works**<br/>
A PIR (passive infrared) motion sensor continuously monitors for movement.</br>
When motion is detected:<br/>
-The raspberry pi camera captures an image and saves it with a timestamp.</br>
-A notification email is automatically composed using SMTP (Gmail).</br>
-The image is attached and sent to the specified email address as an alert.</br>
This runs in a continuous loop while the application is on. </br>

**Features**</br>
-Real time motion detection</br>
-Automatic photo capture with timestamp</br>
-Email alerts with attached photo for remote monitoring</br>
-Uses Gmail's SMTP server to send notifications</br>

**Hardware Requirements**</br>
-Raspberry Pi</br>
-Raspberry Pi Camera Module</br>
-PIR Motion Sensor</br>
-Internet Connection</br>

**Software Requirements**<br/>
-Raspberry Pi OS<br/>
-Python 3<br/>
-Python libraries:<br/>

**Installation & Setup**<br/>
1. Enable Raspberry Pi Camera:<br/>
2. Connect PIR sensor to GPIO<br/>
3. Clone repository and run the script:<br/>
   git clone https://github.com/j-luu/Pet-Detection.git<br/>
   cd Pet-Detection<br/>
   python3 Pet-Detection.py<br/>
Email Configuration<br/>
1. Enable 2-Step Verification on your Gmail account.<br/>
2. Go to Google Accounts > Security > App Passwords. <br/>
3. Generate an App Password for "Mail" and use it in your script instead of your real password. <br/>


