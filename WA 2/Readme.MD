Then, execute the following commands:

$ pip install pyautogui
$ pip install webbrowser

I built this program. These are the params of the wasend.send() function:

wasend.send(message, number)
> message
    The message in plain text. (Use * for bold, _ for italic, and plain Whatsapp formatting)
    Write "\n" to make a line break.
> number
   The phone number in the format: IIINNNNNNNNN (i = indicative, n = number, without the plus sign)
The program takes 11.5 seconds to execute (you can change the sleep to make it fast, but give some time to WhatsApp to load. If you already have WhatsApp loaded, change line 7 in wasend.py to sleep(1), so the program takes only 2.5 seconds to load.
