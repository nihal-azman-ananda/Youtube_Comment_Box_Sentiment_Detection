# Youtube_Comment_Box_Sentiment_Detection

## Creating venv for the project

Windows (PowerShell / CMD)
# Create virtual environment
python -m venv env

# Activate the environment
env/Scripts/activate

macOS / Linux (bash / zsh)
# Create virtual environment
python3 -m venv env

# Activate the environment
source env/bin/activate

## Install the requirements
pip install -r requirements.txt

## For DVC run from gitbash

dvc init

dvc repro

## run the application from local machine (in gitbash) : Make sure you’re in the project root directory (where main.py is located):

python flask_api/main.py

## add the yt-chrome-plugin-frontend folder:
go to link ** chrome://extensions **
swith to developer mode
add the folder

## Test the application
go to youtube 
play any video 
select the extension from the extension icon