This project is a simple digital clock built using Python’s Tkinter library. It displays the current system time in hours, minutes, and seconds, and updates every second automatically. The clock is styled using a custom digital font ('ds-digital') to give it an authentic digital look.

Language Used:
Python

Libraries Used:
- tkinter (for GUI components)
- tkinter.ttk (for enhanced themed widgets)
- time (to get and format the current time)

Additional Notes:
- The clock uses a custom font called 'ds-digital' which can be downloaded from: https://www.dafont.com/ds-digital.font
- To display the clock in a 12-hour format, modify `strftime('%H:%M:%S %p')` to `strftime('%I:%M:%S %p')`.
