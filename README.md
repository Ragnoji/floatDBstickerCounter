First of all:
-
Install Python ~3.10 from https://www.python.org/ <br />
Install chromedriver for your os from https://chromedriver.chromium.org/downloads and locate it in this folder

Then you need csgo_english file from there https://raw.githubusercontent.com/SteamDatabase/GameTracking-CSGO/master/csgo/resource/csgo_english.txt
locate it in this folder


And csgo_items from there https://raw.githubusercontent.com/SteamDatabase/GameTracking-CSGO/master/csgo/scripts/items/items_game.txt

Then, you need to open Command Line inside this folder (you can do this by clicking LMB on folder route on top and entering "cmd")
And write these commands one by one:

py -m pip install --upgrade pip<br />
py -m pip install --user virtualenv<br />

py -m venv venv<br />venv\Scripts\activate.bat<br />pip3 install -r requirements.txt

Then you can close it and all thing are set up. You just need to add Sticker ids in sticker_ids.txt and run start.bat file(it starts script)