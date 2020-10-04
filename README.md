# googlemeetbot
A chatbot that can reply when someone calling you by your name. And instant reply in your google meet chat box. It is a simple automation with python.

# Step 1
Enable Stereo Mix on Windows. 
Tutorial: https://youtu.be/65eh7P_kIAI
If you are using mac or linux just google it how to enable  Stereo Mix  and fix this .

Install vs code
https://code.visualstudio.com/
# Step 2
Download or git clone the code. Extract the zip file. Then open the folder and open cmd or terminal.

# step 3
If you are using windows run: <br>
```
pip install -r requirements.txt 
```
```
pipwin install PyAudio==0.2.11
```

If you are using mac or linux run:<br>
```
pip3 install -r requirements.txt
```
```
pipwin install PyAudio==0.2.11
```

# step 4:
Then run ```chatbox_position.py ``` to find your Google Meet chat box position and notedown the position.

# step 5
open ```gmeet.py``` in a text editor .<br>
Find 
```pyautogui.click(x=400, y=600)```
Replace x,y with your chat box position.<br>

Find 
```target_text=["Alex","alex.","ALEX.","Alex?","Alex."] ```
<br>
Just replace the different names with your name. Also give your name in different way something like me.<br>
If you want to add more your name just write a coma and give quataion and add the name (```,"alexx"```).<br>

Find 
``` output = ["hmm","internet slow","yes","yes sir","Sir I can't hear you","sir can you repeat again","internet is very slow","hmmm"]```<br>
Replace the response with your response.

# step 6
Run gmeet.py 


