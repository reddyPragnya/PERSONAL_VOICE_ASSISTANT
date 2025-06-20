# PERSONAL_VOICE_ASSISTANT

# 🛠️ Tools Required
1. Python 3.8 or above <br>
2. VS Code (or any editor) <br>
3. A microphone <br>
4. Internet connection for YouTube/Wikipedia

# Step 1: Create Project Folder
Open VS Code → Create a new folder using the following command <br><br>
mkdir voice-desktop-assistant <br>
cd voice-desktop-assistant

#  Step 2: Set Up a Virtual Environment
Run the below command to create a virtual environment: <br> <br>
python -m venv venv
<br>
<hr>
Activate it using the following commands for respective OS:<br><br>
1. Windows: <br>
venv\Scripts\activate
<br><br>
2. Mac/Linux: <br>
source venv/bin/activate
<br> 
<hr>
You’ll see (venv) in your terminal – that means you’re good to go!

# Step 3: Install Required Libraries
Run the following command to install all dependencies: <br> <br>
pip install SpeechRecognition pyttsx3 pywhatkit wikipedia pyjokes
<hr>
![image](https://github.com/user-attachments/assets/9ea92973-f365-4145-8ee9-aeba4571b6d3)
<hr>

# Step 4: Create the Assistant Script
Create a file assistant.py and paste the above provided code.

# How to Run the Project
1. First activate the venv.<br>
2. After you activate the venv, run: <br> <br>
python assistant.py

# Then say:
"play prabhas songs"<br>
"what's the time"<br>
"open chrome"<br>
"who is Elon Musk"<br>
"who is Pragnya"

# And LUCY will respond like a pro!
