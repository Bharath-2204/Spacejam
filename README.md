# Spacejam
import random
import string as s
from tkinter import *


root=Tk()
root.geometry('400x400')
root.title('rpg')

Label1=Label(root,text='Type ur password')
Label1.pack()
e=Entry(root,width=50)
e.pack()
e.insert(0,"Type ur password")
def pas():
        if len(e.get())>=8:
             message="Password is strong"
        else:
             message="Password is weak"
            
        lb1=Label(root,text=message)
        lb1.pack()
bt1=Button(root,text="Click",command=pas,bg="blue",fg="white")
bt1.pack()
pass_str=StringVar()






root.mainloop()
