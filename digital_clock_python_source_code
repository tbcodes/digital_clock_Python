#Digital Clock Python

# Import essential modules
import tkinter
from time import strftime

#Create the container + title of the container(window)
root = tkinter.Tk()
root.title("Digital Clock using Python")

#Display some dummy text on the screen
myClock = tkinter.Label()
myClock['text'] = '21:18:00'
myClock.pack()

#Change font family, font size, font style
myClock['font'] = 'Tahoma 150 bold'

#Use the strftime function to get the current time of the system
strftime('%H:%M:%S')

#Create 2 functions to manipulate the time
def tic():
    myClock['text'] = strftime('%H:%M:%S')

tic()

def tac():
    tic()
    myClock.after(1000, tac)

tac()

#Add custom color to the background of your digital clock, change the color of the text...etc
#myClock['text']
myClock['fg'] = 'white'
#myClock['fg'] = 'black'
myClock['bg'] = '#af25f0'
#myClock['bg'] = '#2ffbf0'
