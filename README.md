# flashbang
Flashbang yourself (in Python) with this code

Now, to start off with flashbanging yourself. You may look at a video on youtube but there is nothing.
Maybe load up a game of CS:GO and keep right clicking a flashbang. You may notice that takes too long and makes no sense to use your beautiful GPU on.
Here is the code:




# stim's Flashbang code to flashbang yourself because you feel like it.
from tkinter import *
root = Tk()
button = Button(root, text="Click to Flashbang yourself.", bg="black", fg="white", width=800, height=800)
def on_button_press():
    button["text"] = ""
button["command"] = on_button_press
button.pack()
root.mainloop()




Now run that code, a GUI will open that should (hopefully) fill up your screen. The Instructions will be clear. Enjoy flashbanging yourself. :D
