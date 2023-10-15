from tkinter import*
tk=Tk()
Label(tk,text="Lookbook Profile",bg="blue",bd=50).grid(row=0,column=0)

label1=Label(tk,text="Search :",bd=20,bg="green").grid(row=0,column=3)
button0=Entry(tk).grid(row=0,column=4)

button1=Button(tk,text="Home",fg="red",bd=5,bg="yellow").grid(row=1,column=0)

button2=Button(tk,text="friends",fg="red",bd=5,bg="yellow").grid(row=1,column=1)

button3=Button(tk,text="Video",fg="red",bd=5,bg="yellow").grid(row=1,column=2)


button4=Button(tk,text="Marketplace",fg="red",bd=5,bg="yellow").grid(row=1,column=3)

button5=Button(tk,text="Notification",fg="red",bd=5,bg="yellow").grid(row=1,column=4)
flile1=Button(tk,text="File menu",fg="red",bd=5,bg="yellow").grid(row=1,column=5)








tk.mainloop()
