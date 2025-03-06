# Step by Step Guide to Run the Emotion Detection App

Hello! 👋 Let's set up your emotion detection app together. Just follow these simple steps!

## Step 1: Setting Up Your Computer

1. First, let's install Python:
   - Go to [Python.org](https://www.python.org/downloads/)
   - Click the big yellow "Download Python" button
   - Once downloaded, double-click the file and click "Install Now"
   - Wait for it to finish installing

2. Open Command Prompt (Windows) or Terminal (Mac):
   - Windows: Press Windows key + R, type "cmd", press Enter
   - Mac: Press Command + Space, type "terminal", press Enter

## Step 2: Installing Required Programs

Copy and paste these commands one by one into your Command Prompt/Terminal:
```
pip install streamlit
pip install tensorflow
pip install joblib
pip install numpy
pip install pandas
```
(Press Enter after each line and wait for it to finish)

## Step 3: Setting Up Your Project

1. Create a new folder on your computer:
   - On your Desktop, create a new folder called "emotion-detector"
   - Open this folder

2. Download these important files and put them in your folder:
   - emotion_model.h5
   - tokenizer.jb
   - label_encoder.jb
   - app.py

## Step 4: Running the App

1. Open Command Prompt/Terminal again
2. Type `cd ` (with a space after cd)
3. Drag your "emotion-detector" folder into the Command Prompt/Terminal window
4. Press Enter
5. Type this command and press Enter:
```
streamlit run app.py
```

## Step 5: Using the App

1. Your web browser should open automatically
2. You'll see a text box that says "Enter text:"
3. Type any sentence like "I am so happy today!"
4. Click the "Analyze Emotion" button
5. The app will tell you what emotion it detected!

## Common Problems and Solutions

If you see an error:

1. "Command not found":
   - Close and reopen Command Prompt/Terminal
   - Try running the pip install commands again

2. "Files not found":
   - Make sure all files are in your emotion-detector folder
   - Check if the file names are exactly correct (including .h5, .jb)

3. "Module not found":
   - Run the pip install commands again

## Need More Help?

If you're stuck:
1. Make sure Python is installed correctly
2. Make sure you copied all commands exactly
3. Try closing everything and starting fresh
4. Ask an adult to help you double-check the steps

Remember: It's okay if it doesn't work the first time! Just try again carefully 😊

## Fun Things to Try

Once your app is running, try these messages:
- "I just won a game!"
- "This ice cream is delicious"
- "I'm feeling scared of the dark"
- "The surprise party was amazing"

See if the app can guess your emotions correctly! 🎮
