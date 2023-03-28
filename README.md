# Send-automatic-whatsapp-message
The above code is a Python script that allows a user to send a WhatsApp message at a specified time using the pywhatkit library. The user is prompted to input the recipient's mobile number, the message they want to send, the hour and minute they want to schedule the message for.

The datetime.now() method from the datetime module is used to get the current time, which is then formatted to get the current hour using the strftime() method.

The pywhatkit.sendwhatmsg() function is used to send the message at the scheduled time. It takes four arguments:

The recipient's mobile number (string)
The message to be sent (string)
The hour at which the message should be sent (integer)
The minute at which the message should be sent (integer)
Before running the code, ensure that you have installed the pywhatkit library using pip or any other package manager
