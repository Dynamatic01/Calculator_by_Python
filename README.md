# #  Calculator using Python
 
A calculator is a device or software that performs mathematical calculations. It can handle basic arithmetic operations such as addition, subtraction, multiplication, and division, as well as more complex functions like trigonometry, logarithms, and exponential functions. Calculators come in various forms, including physical handheld devices, desktop applications, and built-in functions on smartphones and computers. They are essential tools for students, professionals, and anyone needing quick and accurate mathematical computations.
## Screenshots

![App Screenshot](https://github.com/Dynamatic01/Calculator_by_Python/blob/main/Screenshot%202024-07-03%20135047.png)


## CODE

```javascript
ffrom tkinter import *

win=Tk()
win.title("Simple Calculator")



def button1(number):

    current = e.get()
    e.delete(0, END)
    e.insert(0, str(current) + str(number))

def button_clear():
    e.delete(0, END)

def button_add():
    first_number =e.get()
    global f_num
    global math
    math = "additon"
    f_num =int(first_number)
    e.delete(0,END)

def button_equal():
    second_number= e.get()
    e.delete(0, END)

    if math == "addition" :
        e.insert(0,f_num + int(second_number))

    if math == "subtraction":
        e.insert(0, f_num - int(second_number))

    if math == "multiplication":
        e.insert(0, f_num * int(second_number))

    if math == "division":
        e.insert(0, f_num / int(second_number))




def button_sub():
        first_number = e.get()
        global f_num
        global math
        math = "subtraction"
        f_num = int(first_number)
        e.delete(0, END)

def button_multiple():
    first_number =e.get()
    global f_num
    global math
    math = "multiplication"
    f_num =int(first_number)
    e.delete(0,END)

def button_divide():
    first_number =e.get()
    global f_num
    global math
    math = "division"
    f_num =int(first_number)
    e.delete(0,END)







e = Entry(win, width=35, borderwidth=5)
e.grid(row=0, column=0,columnspan=3, padx=10, pady=10)

button_1 = Button(win, text="1",padx=40,pady=20 ,command=lambda: button1(1))
button_2 = Button(win, text="2", padx=40,pady=20 ,command=lambda:button1(2))
button_3 = Button(win, text="3",padx=40,pady=20 , command=lambda:button1(3))
button_4 = Button(win, text="4",padx=40,pady=20 , command=lambda:button1(4))
button_5 = Button(win, text="5", padx=40,pady=20 ,command=lambda:button1(5))
button_6 = Button(win, text="6",padx=40,pady=20 , command=lambda:button1(6))
button_7 = Button(win, text="7", padx=40,pady=20 ,command=lambda:button1(7))
button_8 = Button(win, text="8",padx=40,pady=20 , command=lambda:button1(8))
button_9 = Button(win, text="9",padx=40,pady=20 , command=lambda:button1(9))
button_0 = Button(win, text="0",padx=40,pady=20 , command=lambda:button1(0))
button_add= Button(win,text="+", padx=40, pady=20,command=button_add)
button_sub= Button(win,text="-", padx=40, pady=20,command=button_sub)
button_equal = Button(win,text="=", padx=40, pady=20,command=button_equal)
button_divid = Button(win,text="÷", padx=40, pady=20,command=button_divide)
button_multiple = Button(win,text="X", padx=40, pady=20,command=button_multiple)
button_clear = Button(win,text="C", padx=40, pady=20,command=button_clear)

button_1.grid(row=1,column=0)
button_2.grid(row=1,column=1)
button_3.grid(row=1,column=2)
button_4.grid(row=2,column=0)
button_5.grid(row=2,column=1)
button_6.grid(row=2,column=2)
button_7.grid(row=3,column=0)
button_8.grid(row=3,column=1)
button_9.grid(row=3,column=2)
button_0.grid(row=4,column=0)
button_add.grid(row=4,column=1)
button_sub.grid(row=4,column=2)
button_equal.grid(row=5,column=0)
button_divid.grid(row=5,column=1)
button_multiple.grid(row=5,column=2)
button_clear.grid(row=6,column=0)




win.mainloop()
```


## License

[GNU](https://github.com/Dynamatic01/Calculator_by_Python/blob/main/LICENSE)


## Related

Here are some related projects

[Awesome README](https://github.com/matiassingers/awesome-readme)


## Support

For support, email mehtamohit514@gmail.com or join our Slack channel.


## 🛠 Skills
Javascript, HTML, CSS, Python
