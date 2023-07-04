import tkinter as tk
import webbrowser
import tkinter
import datetime

root = tkinter.Tk()
root.title("PYTHON explorer BETA de Louis vieu")

btn = tkinter.Button(root, bg="light blue", command=root.quit, text="bienvenue sur PYTHON explorer beta, ce bouton sert a entre dans le web et a y en sortir").pack()

root.mainloop()

def openweb():
    url = entry.get()
    webbrowser.open_new(url)

root = tk.Tk()
root.title("PYTHON explorer BETA de Louis Vieu")
entry = tk.Entry(root)
entry.pack()

button = tk.Button(root, bg="light blue",text="rechercher", command=openweb)
button.pack()

root.mainloop()

