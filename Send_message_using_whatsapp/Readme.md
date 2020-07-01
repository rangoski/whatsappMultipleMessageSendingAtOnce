
# vivekdw-project
Send Whatsapp Messages using Python Selenium


////////////////////////////////////////////////////////////////////////////////////

Points to note before you run the script :- 

1- You must be using python3 to run the code

2- You Google Chrome and chrome driver version must be same. I have Google Chrome of Version 73.0.3683.103 (Official Build) (64-bit) so I downloaded chrome driver accordingly.

3- You can download another version of chrome driver from the link - http://chromedriver.chromium.org/downloads please read my blog for more details on this.

4- I built this code to leverage Google Chrome driver.

5- You must have Selenium downloaded as well. You can use the command - `pip3 install selenium` to download selenium

6- You must download the webdriver manager. Use command - `pip3 install  webdriver-manager` to download this.

7- As we use an Excel file here (tt.xlxs), you must have openpyxl downloaded. Use command - pip3 install openpyxl to download this.

8- In tt.xlxs file you have to mention the names that are saved in your contact list.

Now you are good to go.

//////////////////////////////////////////////////////////////////////////////////////////

How to run -

Download or clone these three file in same folder. tt.xlxs is an excel file where you have to edit the names of your contacts. After saving these contacts, run  whatsapp_sendmessage.py using python3 and enter the message that you want to send. Scan the QR code (to login on whatsappweb), and you are done! All the mentioned contacts will recieve the message with a delay time of 5 seconds between contacts, and then the tab will close.

/////////////////////////////////////////////////////////////////////////////////////

Note that this tutorial is only for educational purposes. We are not responsible if your friends or Whatsapp itself blocks you for excess use of this.

/////////////////////////////////////////////////////////////////////////////////////////

# whatsappMultipleMessageSendingAtOnce
