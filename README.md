# Spambot
A simple bot to spam anywhere. 
# Installation
Open Cmd Type pip install pynput.

from pynput.keyboard import Key, Controller
import time

message = "the message"
keyboard = Controller()
time.sleep(5)
for num in range(100):
    for letter in message:
        keyboard.press(letter)
        keyboard.release(letter)
    keyboard.press(Key.enter)
    keyboard.release(Key.enter)

import pyautogui,time
time.sleep(5)
f = open("anytextfile.txt",'r')
for word in f:
    pyautogui.typewrite(word)
    pyautogui.press("enter")

