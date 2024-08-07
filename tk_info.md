1. to install tkinter use: ``pip install tkinter``.
2. to use it: `` import tkinter as tk``.
3. to create a window: ``root = tk.Tk()``, and at the end of the file write: ``root.mainloop()``.
#####create widget:
	there are many widgets:
		I. Label
		II. Button
		III. Entry
		IV. Frame
		... and some other.

	use: ``tk.Lable(root, text='some-text').pack()``
	-pack method to display the widget.

4. to write a window's title: ``root.title('write title here')``.
5. to use modren widgets use: `` from tkinter import ttk``,
 and use: ``ttk.Label(root, text='sometxt')``.
