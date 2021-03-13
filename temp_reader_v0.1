import tkinter as tk
import time

from gpiozero import CPUTemperature
cpu = CPUTemperature()

class App():
    def __init__(self):   
        self.root = tk.Tk()            
        self.label = tk.Label(text="", fg="black", padx=10, pady=10)
        self.label.pack()
        self.update_window()
        self.root.mainloop()

    def update_window(self):
        temp = round(cpu.temperature,1)
        message = "CPU temp:\n"+ str(temp) +"°C"
        
        if temp <= 41:
            color = "green"
        if 41 < temp < 42:
            color = "yellow"
        if temp >= 42:
            color = "red"
        
        self.label.configure(text=message, bg=color)
        self.root.after(1000, self.update_window)

app=App()
