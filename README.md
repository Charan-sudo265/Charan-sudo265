import pyautogui as pg      
import time
import random

animals = ['ariffuk','donkey','dog','pig','loffoot']
time.sleep(8)
for i in range(100):
    a = random.choice(animals)
    pg.write(f"you are a {a}")
    pg.press('enter')
