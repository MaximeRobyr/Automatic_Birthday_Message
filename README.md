# Automatic_Birthday_Message
# 1. README
Have you ever forgotten to wish a friend or family member a happy birthday? Now, thanks to Automatic_Birthday_Message, that will never happen again! If you upload the birth dates of all your friends to an Excel spreadsheet (CSV), our code will automatically send the birthday message for you via WhatsApp Web. You will never have to remember your relatives' birthdays again, our programme does it for you. First of all, before running our code, you need to manually enter the data on an Excel sheet. You need to add the person's name, phone number and date of birth. You can add as many people as you wish, even if several of them are born on the same day. Then, you can run the code and it will automatically send the message. In the code itself, every single step is described and can thus answer open questions.
# 2. How to run the programm 
1. You have to be logged in to WhatsApp on your computer and opened the application at least one time. 
2. Make sure that your excel sheet is in the file corresponding to your code
3. Add manually the data in the excel sheet. It must be written in the following way (name; year/month/day; phone number) in one cell.
4. You have to install the Python Libraries Pywhatkit (pip install pywhatkit) and pyautogui (pip install pyautogi)
5. Before running the code, you must change the coordinates that correspond to the exact location of the send button in your WhatsApp browser at line 96 of the code. print(pyautogui.position()) It will show you the coordinates of the position of your courser.
# 3. Features
- Automatic message sender
- Add data manually into csv file in the same folder as your py program
- Upload Excel sheet 
- Send messages on WhatsApp automatically
- Conversion of Excel Data to a WhatsApp message
# 4. Authors
- Fabio Capuano (Capo98)
- Matthias Kilchenmann (Mats1998)
- Maxime Robyr (MaximeRobyr)
