# **Python Tutorial**

The following instructions are applied for Windows system but can also serve as a reference if you are using a different system.

This tutorial is written for Python language. If you want to use graphical code programming, please refer to the manual "Makecode Tutorial.pdf". In the root directory of the resource you downloaded, there is a folder named "Python tutorial", which stores all the Python code of Microbit smart home. The Python code file is a file ending with ".py".

## Getting Started With Python

Python is a scripting language. It has embraced a huge ecology after years of development evidenced by the fact that many of hot artificial intelligence are written in it. It is worth learning.

Micro:bit can be programmed in Python language. While since the micro:bit main board is a microcontroller, the hardware difference makes the micro:bit unable to fully support Python. Thus here comes the MicroPython, which is specially designed for micro:bit and can be regarded as the micro:bit version of Python.

MicroPython is a lean and efficient implementation of the [Python 3](http://www.python.org/) programming language that includes a small subset of the Python standard library and is optimised to run on microcontrollers and in constrained environments. It is very suitable for those who want to continue to learn programming in depth, with a series of code snippets, various images and music to help you program.

More details about it please log in official micro:bit website:

<https://microbit-micropython.readthedocs.io/en/latest/tutorials/introduction.html>

Python has two types of editors（web version and offline version).

Web version: <https://python.microbit.org/v/1.1>

![](media/img/693f76f5975fc256dbc1d2880c80edeb.png)

The other one is the offline compiler tool-----Mu![IMG_256](media/img/153c77edd571f12fce0e3282ab6fb530.png)

(Download Mu：https://codewith.mu/en/download)

**Mu**

The official website for Mu is: <https://codewith.mu/>.

Mu is a Python code editor for beginner programmers based on extensive feedback given by teachers and learners.Mu doesn’t support 32-bit Windows. The latest version is Mu 1.1.0-beta 2.

**Follow steps below to install Mu:**

Download Mu

Click“This PC”and right- click to select Properties to check the version of your computer.

![](media/img/3a58be549e85e640654494c09f3a219f.png)

Below is shown system type of your computer.

![](media/img/e774ae15dcb81968d9a2a553af57ac96.png)

Enter link: <https://codewith.mu/en/download> to download the corresponding version of Mu.

![](media/img/ceb4cfa6c81ce3959cec504412767e39.png)

Run and Install Mu

Find out the folder where Mu is downloaded and double-click file to install Mu.

![IMG_256](media/img/8bcfe24cd37e0e5accae1f94cf155640.png)

Installation for Mac OSX please refer to：https://codewith.mu/en/howto/1.1/install_macos .

The installation method is similar and we will demonstrate how to download Mu on Windows 10.

Windows 10

You will view the page pop up, then click More info;

![](media/img/877beb7b3f5ccf7e5d849b7aaa8d661d.png)

Then click“Run anyway”;

![](media/img/c87475e50dd03a0d0d2dcf166f33a837.png)

Check the license agreement and tick to agree and tap”Install”;

![](media/img/cc52e57332beae056b2dc9cd7fdd1651.png)

Just wait for a few seconds until the installation is finished;

![](media/img/d75042c926b6e89463ef41c47220cdcc.png)

Finally,click“Finish”. ![](media/img/62abaf11f6dfe7ba9d61b278bb7031b8.png)

Start Mu:

Click Mu icon to get started. It may take a while for the first time;

![](media/img/c4adbdd1b2bf01cee8783ce659ac420f.png)

Mu’s main interface is shown below:

![](media/img/20ecc591f144b83d83515aab136219d5.png)



## On Board Projects：

### Project 1: Heartbeat

**(1)Project Introduction**

This project is easy to conduct with a micro:bit main board, a Micro USB cable and a computer.This experiment serves as a starter for your entry to the magical programming world of Micro:bit.

**(2)Preparations:**

A. Attach the Micro:bit main board to your computer via the USB cable;

B.Open the offline version of Mu.

**(3)Test Code：**

Open Mu software, click Mode, then click“BBC micro：bit”and“OK”

![](media/img/876db77a3d73b093a9c125db948a2789.png)

Tap“Load”, select“Project 1：Heartbeat.py”file and click“open”:

| File Type   | Route                                                                       | File Name               |
|-------------|-----------------------------------------------------------------------------|-------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 1：Heartbeat | Project 1：Heartbeat.py |

![](media/img/f3f4e9af9976cc84e655fdb324c45935.png)

![IMG_256](media/img/0b07995a56f40d8f323c6639b40d0690.png)

There is another way to import code. Open Mu software and drag file”Project1:Heartbeat.py”into it.

![dsBuffer.bmp](media/img/6e64d7130edc0902f0a5f18a42ef6217.png)

You can also input code in the edit window yourself.(note:all English words and symbols must be written in English.)

![](media/img/6bc64e63c9a9a706311b09a063205faa.png)

The following is a list of built-in images.

• Image.HEART

• Image.HEART_SMALL

• Image.HAPPY

• Image.SMILE

• Image.SAD

• Image.CONFUSED

• Image.ANGRY

• Image.ASLEEP

• Image.SURPRISED

• Image.SILLY

• Image.FABULOUS

• Image.MEH

• Image.YES

• Image.NO

• Image.CLOCK12, Image.CLOCK11, Image.CLOCK10, Image.CLOCK9, Image.CLOCK8,
Image.CLOCK7, Image.CLOCK6, Image.CLOCK5,

Image.CLOCK4, Image.CLOCK3, Image.CLOCK2,Image.CLOCK1

• Image.ARROW_N, Image.ARROW_NE, Image.ARROW_E, Image.ARROW_SE, Image.ARROW_S,
Image.ARROW_SW, Image.ARROW_W, Image.ARROW_NW

• Image.TRIANGLE

• Image.TRIANGLE_LEFT

• Image.CHESSBOARD

• Image.DIAMOND

• Image.DIAMOND_SMALL

• Image.SQUARE

• Image.SQUARE_SMALL

• Image.RABBIT

• Image.COW

• Image.MUSIC_CROTCHET

• Image.MUSIC_QUAVER

• Image.MUSIC_QUAVERS

• Image.PITCHFORK

• Image.PACMAN

• Image.TARGET

• Image.TSHIRT

• Image.ROLLERSKATE

• Image.DUCK

• Image.HOUSE

• Image.TORTOISE

• Image.BUTTERFLY

• Image.STICKFIGURE

• Image.GHOST

• Image.SWORD

• Image.GIRAFFE

• Image.SKULL

• Image.UMBRELLA

• Image.SNAKE，Image.ALL_CLOCKS，Image.ALL_ARROWS

Connect micro:bit board to computer with USB cable, click“Flash”to download code
to micro:bit board.

![6(1)](media/img/f00f946e1f194811b1c84725e0eb5d16.png)
![5(1)](media/img/18c70cf16dcf8c9694a1af8b12530cf9.png)

![](media/img/84852c5e09be53e69e3b4f464356aca2.png)

The code, even it is wrong, can be downloaded to micro:bit board successfully, yet not working on micro:bit board.

Click“Flash”to download code to micro:bit.

![](media/img/0d8b7cee560b9cb0cad8b118e0ff97d7.png)

Click“REPL”and press the reset button on micro:bit, the error information will be displayed on REPL window, as shown below:

![](media/img/d30d16a76f92dba67336dc4830d52b5f.png)

Click“REPL”again to turn off REPL mode, then you could refresh new code.

To make sure code correct, you only need to tap“Check”. The errors will be shown on the window.

![](media/img/60e5eed141debded555ec859f2a3c93a.png)

Modify the code according to the prompt and click“Check”.

![](media/img/3a532c253832a4fd5fb07f0a0d4655b2.png)

More tutorials, log in website please:<https://codewith.mu/en/tutorials/>.

**(4)Test Results:**

After uploading test code to micro:bit main board, clicking“Flash”again and keeping the connection with the computer to power the main board, the LED dot matrix shows pattern “![](media/img/f496ba08ff8af3164cdbd5fc56cc5abb.png)”and then “![](media/img/04fdfc9060943954e7938bb1a741d626.png)”alternatively.

**(5)Code Explanation：**

| **from**  microbit **import** \* | Import the library file of micro：bit                                 |
|----------------------------------|-----------------------------------------------------------------------|
| **while True:**                  | This is a permanent loop that makes micro:bit execute the code of it. |
| display.show(Image.HEART)        | micro：bit shows “❤”                                                  |
| sleep(500)                       | Delay in 500ms                                                        |
| display.show(Image.HEART_SMALL)  | micro：bit displays“![](media/img/04fdfc9060943954e7938bb1a741d626.png)”  |

### Project 2: Light A Single LED

![](media/img/8c3f540a07aab97e1608ba8770837f7b.png)

**(1) Project Introduction**

The LED dot matrix consists of 25 LEDs arranged in a 5 by 5 square. In order to locate these LEDs quickly, as the figure shown below, we can regarded this matrix as a coordinate system and create two aces by marking those in rows from 0 to 4 from top to bottom, and the ones in columns from 0 to 4 from the left to the right. Therefore, the LED sat in the second of the first line is (1,0）and the LED positioned in the fifth of the fourth column is (3,4) and others likewise.

![](media/img/fe710eb3e622ac0e3544576acce9f03f.png)

**(2)Preparations:**

A. Attach the Micro:bit main board to your computer via the USB cable;

![5(1)](media/img/18c70cf16dcf8c9694a1af8b12530cf9.png)

B.Open the offline version of Mu.

**(3)Test Code：**

Enter Mu software and open the file“Project 2： Light A Single LED.py”to import code:

| Type        | Route                                                                                 | File Name                         |
|-------------|---------------------------------------------------------------------------------------|-----------------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 2： Light A Single LED | Project 2： Light A Single LED.py |

You can also input code in the editing window yourself.

(Note:all English words and symbols must be written in English)

![](media/img/4272f64e96e79533881d3b68e8a0637f.png)

Click“Check”to examine error in the code. The program proves wrong if underlines and cursors are shown.

![](media/img/db94db7dc813cb3e9ce5147d5376c688.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/345c4cb3eab80030c8fc5360f12c095b.png)

**(4)Test Results:**

After uploading test code to micro:bit main board and powering the main board via the USB cable, the LED in (1,0) lights up for 0.5s and the one in (3,4) shines for 0.5s and repeat this sequence.

**(5)Code Explanation:**

| from microbit import \*                                                                                                                                                     | Import the library file of micro：bit                                                                                                                                                                                                                                                  |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| val1 = Image("09000:""00000:""00000:""00000:""00000:")      val2 = Image("00000:""00000:""00000:""00000:""00090:")  val3 = Image("00000:""00000:""00000:""00000:""00000:")  | Set Image() to val1 Set pixel of LED on micro:bit to the value in 0\~9  Pixel of each LED on micro:bit can be set in one of ten values If set pixel to 0 (zero) ，which means in close state, literally, 0 is brightness, 9 is best brightness Set Image() to val2 Set Image() to val3 |
| while True:                                                                                                                                                                 | This is a permanent loop that makes micro:bit execute the code of it.                                                                                                                                                                                                                  |
| display.show(val1)  sleep(500)  display.show(val3)  sleep(500)                                                                                                              |  LED at (1,0) blinks for 0.5s                                                                                                                                                                                                                                                          |
| display.show(val2)  sleep(500)  display.show(val3)  sleep(500)                                                                                                              |  LED at (3,4) flashes for 0.5s                                                                                                                                                                                                                                                         |

**(6)Reference**

sleep(ms) : delay time

For more details about delay, please refer to:

https://microbit-micropython.readthedocs.io/en/latest/utime.html

### Project 3: LED Dot Matrix

![](media/img/8c3f540a07aab97e1608ba8770837f7b.png)

**(1)Project Introduction**

Dot matrices are very commonplace in daily life. They have found wide applications in LED advertisement screens, elevator floor display, bus stop announcement and so on.

The LED dot matrix of Micro: Bit main board contains 25 LEDs in a grid. Previously, we have succeeded in controlling a certain LED to light by integrating its position value into the test code. Supported by the same theory, we can turn on many LEDs at the same time to showcase patterns, digits and characters.

What’s more, we can also click”show icon“ to choose the pattern we like to display. Last but not the least, we can design patterns by ourselves as well.

**(2)Preparations:**

A. Attach the Micro:bit main board to your computer via the USB cable;

B. Open the offline version of Mu.

**(3)Test Code：**

You could open“Project 3：LED Dot Matrix.py“file to Import code（[How to load the project code?](##AS)）

| File Type   | Route                                                                            | File Name                    |
|-------------|----------------------------------------------------------------------------------|------------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 3：LED Dot Matrix | Project 3：LED Dot Matrix.py |

You can also input code in the editing window yourself.

(note:all words and symbols must be written in English.)

![](media/img/87a9b4b979bbca818a20dae67925455e.png)

Click“Check”to examine error in the code. The program proves wrong if underlines and cursors are shown.

![](media/img/1ac5d0ccf239a5cfff02b8d67055ba79.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/c5bc4c8f2524237a0e5a58ee922b9309.png)

**(4)Test Results:**

After uploading test code to micro:bit main board and powering the main board via the USB cable, we find that the 5\*5 dot matrix start to show numbers 1,2,3,4 and 5, and then it alternatively shows a downward arrow![](media/img/2d4524f650129197874d4d62985e47c6.png), word “Hello”, a heart pattern![](media/img/9b18b2b8dfaa0533d8859d08ff12611e.png), an arrow pointing at northeast
![IMG_256](media/img/364f2e355d6c354155b2e6db80830a62.png), then at southeast![](media/img/fb3ba009a20245ab6076e537159a229c.png), then at southwest![](media/img/7ec21961398787ca5155f0648bbd82cc.png), and then at northwest![](media/img/ced0bb410c8269205fe18554aa2c9926.png).

**(5)Code Explanation:**

| **from** microbit **import** \*                                                                                      | Import the library file of micro：bit                                                                                                 |
|----------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| val = Image("09000:""00000:""00000:""00000:""00000:")                                                                |  Set Image() to variable val                                                                                                          |
| display.show(val)                                                                                                    | micro:bit shows“→”                                                                                                                    |
| display.show('1')                                                                                                    | micro:bit shows“1”                                                                                                                    |
| sleep(500)                                                                                                           | Delay in 500ms                                                                                                                        |
| display.scroll("hello!")                                                                                             | micro:bit scrolls to show“hello!”                                                                                                     |
| display.show(Image.HEART)                                                                                            | micro:bit displays“❤”pattern                                                                                                          |
| display.show(Image.ARROW_NE) display.show(Image.ARROW_SE) display.show(Image.ARROW_SW)  display.show(Image.ARROW_NW) | micro:bit shows“Northeast”arrow micro:bit displays“Southeast”arrow micro:bit shows“Southwest”arrow micro:bit displays“Northwest”arrow |
| display.clear()                                                                                                      | The LED dot matrix of micro:bit clears                                                                                                |

**(6) Reference:**

display.scroll() ：

The display scrolls to show the values, if it is integer or float, we use str（）to transfer into character strings.

More details, please refer to

<https://microbit-micropython.readthedocs.io/en/latest/utime.html>

### Project 4: Programmable Buttons

![](media/img/06be84fb11b1fd07cd0cbb392132b903.png)

1.  **Project Introduction**

![](media/img/2ff75a1d81bfe0228b83931a0b7cc860.png)

Buttons can be used to control circuits. In an integrated circuit with a push button, the circuit is connected
when pressing the button and it is open the other way around.

Both ends of button are like two mountains. There is a river in between.

The internal metal piece connect the two sides to let the current pass, just like building a bridge to connect two mountains.

![](media/img/d2a204e61c768f18924150db58aee093.png)

Micro: Bit main board boasts three push buttons, two are programmable buttons(marked with A and B), and the one on the other side is a reset button. By pressing the two programmable buttons can input three different signals. We can press button A or B alone or press them together and the LED dot matrix shows A,B and AB respectively. Let’s get started.

**(2)Preparations:**

 Attach the Micro:bit main board to your computer via the USB cable.

Open the offline version of Mu.

**(3)Test Code1：**

Enter Mu software and open the file“Project 4：Code-1.py”to import code:

（[How to load the project code?](##AS)）

| File Type   | Route                                                                                  | File Name             |
|-------------|----------------------------------------------------------------------------------------|-----------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 4：Programmable Buttons | Project 4：Code-1.py  |

You can also input code in the editing window yourself.

(note:all words and symbols must be written in English)

![](media/img/9c71c5c161479c62b31547da468beda9.png)

Click“Check”to examine error in the code. The program proves wrong if underlines and cursors are shown.

![](media/img/4da7649f8aa52203ca5b4819c6f55e3c.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/8ea1d431608cb42b68b9d3b3e8d1e080.png)

**(4)Test Results1:**

After uploading test code to micro:bit main board and powering the main board via the USB cable, the 5\*5 LED dot matrix shows “A”if button A is pressed and then released, “B” if button B pressed and released, and “AB” if button A and B pressed together and then released.

**(5)Test Code2：**

Enter Mu software and open the file “Project 4：Code-2.py” to import code:（[How to load the project code?](##AS)）

| File Type   | Route                                                                                  | File Name             |
|-------------|----------------------------------------------------------------------------------------|-----------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 4：Programmable Buttons | Project 4：Code-2.py  |

You can also input code in the editing window yourself.

(note:all English words and symbols must be written in English)

![](media/img/085c1b1d83cb8033cae91e8d7e08ae1d.png)

![](media/img/b5a07ef865b2194d66ea4adb688af04d.png)

Click“Check”to examine error in the code. The program proves wrong if underlines and cursors are shown.

![](media/img/7dc4ec64e3d6bc4f38738e7828210ec3.png)![](media/img/b5a07ef865b2194d66ea4adb688af04d.png)

Please notice that the following sentences are just for warning so the presence of them doesn’t mean the code is wrong.

![](media/img/8cb6b22dec97317861ec6b7cdea2537e.png)

![](media/img/5e073b8c5efe9a901637da0886a9266e.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/247d84c9ff532d2ce8ce55ca08f5b31f.png)

![](media/img/b5a07ef865b2194d66ea4adb688af04d.png)

**(6)Test Results2：**

After uploading test code to micro:bit main board and powering the main board via the USB cable, when the button A is pressed, the LEDs turning red increase while when the button B pressed, the LEDs turning red reduce.

**(7)Code Explanation：**

| from microbit import \*                                                                                                                                                                                                                                                                                                                                                                                                       | Import the library file of micro：bit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| while True:                                                                                                                                                                                                                                                                                                                                                                                                                   | This is a permanent loop that makes micro:bit execute the code of it.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| if button_a.is_pressed():  display.show("A")  elif button_a.is_pressed() and button_b.is_pressed(): display.scroll("AB")  elif button_b.is_pressed():  display.show("B")                                                                                                                                                                                                                                                      | If button A is pressed micro:bit shows“A” If button A and B are pressed at same time micro:bit displays“AB” If button B is pressed micro:bit shows“B”                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| while button_a.is_pressed() == True: sleep(10) if button_a.is_pressed() == False: a = a + 1 if(a \>= 5): a = 5 break while button_b.is_pressed() == True: sleep(10) if button_b.is_pressed() == False: a = a - 1 if(a \<= 0): a = 0 break if a == 0: display.show(val1) if a == 1: display.show(val2) if a == 2: display.show(val3) if a == 3: display.show(val4) if a == 4: display.show(val5) if a == 5: display.show(val6) | When the button A is pressed Delay in 10ms to eliminate the shaking of button A when button A is released, Variable a adds 1 If variable a≥5 Variable a=5 exit the loop  when button B is pressed Delay in 10ms to eliminate the shaking of button B When the button B is released Variable a reduces 1 gradually When a≤0 Variable a=0 exit the loop When a=0 micro:bit shows pattern val1 When a=1 micro:bit displays pattern val2 When a=2 micro:bit shows pattern val3 If a=3 micro:bit displays pattern val4 If a=4 micro:bit shows pattern val5 If a=5 micro:bit displays pattern val6 |

### Project 5: Temperature Detection

**(1)Project Introduction**

The Micro:bit main board is not equipped with a temperature sensor, but uses the temperature sensor built into NFR52833 chip for temperature detection. Therefore, the detected temperature is more closer to the temperature of the chip, and there maybe deviation from the ambient temperature. The sensor can detect temperature of external environment with the range of 40℃\~105℃.

In this project, we use the sensor to test the temperature in the current environment, and display the test results in the display data (device). And then control the LED dot matrix to display different patterns by setting the temperature range detected by the sensor.

Note: the temperature sensor of Micro:bit main board is shown below:

![](media/img/206c8ec1c3f11d2de8d0f42fdf5b6b47.png)

**(2)Preparations:**

A. Attach the Micro:bit main board to your computer via the USB cable;

B. Open the offline version of Mu.

**(3)Test Code1:**

Enter Mu software and open the file“Project 5：Code-1.py”to import code:

| File Type   | Route                                                                                   | File Name            |
|-------------|-----------------------------------------------------------------------------------------|----------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 5：Temperature Detection | Project 5：Code-1.py |

You can also input code in the editing window yourself.(note:all English words and symbols must be written in English)

![](media/img/671a013ac4c3fcf96fca4ba80c135294.png)

Click“Check”to examine error in the code. The program proves wrong if underlines and cursors are shown.

![](media/img/27b955e41ece7008e868496146e5899f.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/78707cf5af730427b2fe6f254733c9b3.png)

**(4)Test Results1:**

After downloading test code 1 to micro:bit board, keep USB connected and click“REPL”and press the reset button on micro:bit. Then REPL window will show the ambient temperature value, as shown below:( C stands for temperature unit)

![](media/img/4e898ece063dea280b14d7c91da5f4c9.png)

**(5)Test Code2:**

Enter Mu software and open the file“Project 5：Code-2.py”to import code:

| File Type   | Route                                                                                   | File Name            |
|-------------|-----------------------------------------------------------------------------------------|----------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 5：Temperature Detection | Project 5：Code-2.py |

You can also input code in the editing window yourself.(note:all English words and symbols must be written in English)

The temperature value can be set in compliance with the real temperature.

![](media/img/b6d1f13273a060eae4f823af538799cf.png)

Click“Check”to examine error in the code. The program proves wrong if underlines and cursors are shown.

![](media/img/87997c38b6fd53fcf4d45d68f9d47f8e.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/1275487908a69556e2d2f232636ce35a.png)

**(6)Test Results2:**

After uploading the code 2 to the board, when the ambient temperature is less than 35℃, the 5\*5 LED dot matrix shows
![](media/img/4b1765e12b413dc5d562f2a16d32392f.png). When the temperature is equivalent to or greater than 35℃, the pattern![](media/img/f2705fbc4886efcfaac96589ca255f66.png) appears.

**(7)Code Explanation:**

| **from** microbit **import** \*                                                                     | Import the library file of micro：bit                                                                                                        |
|-----------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| **while True:**                                                                                     | This is a permanent loop that makes micro:bit execute the code of it.                                                                        |
| Temperature = temperature()                                                                         | Set temperature() to Temperature                                                                                                             |
| print("Temperature:", Temperature, "C")                                                             | BBC micro:bit REPL prints temperature value                                                                                                  |
| sleep(500)                                                                                          | Delay in 500ms                                                                                                                               |
| **if** temperature() \>= 35: display.show(Image.HEART)  **else**:  display.show(Image.HEART_SMALL)  | If temperature value ≥35℃  micro:bit shows“♥” If temperature value\<35℃  micro:bit displays“![](media/img/04fdfc9060943954e7938bb1a741d626.png)” |

### Project 6: Geomagnetic Sensor

![](media/img/24c31bb0174e2ac672203e5c36c6875e.png)

**(1)Project Introduction**

This project aims to explain the use of the Micro: bit geomagnetic sensor, which can not only detect the strength of the geomagnetic field, but also be used as a compass to find bearings. It is also an important part of the Attitude and
Heading Reference System (AHRS).

Micro: Bit main board uses LSM303AGR geomagnetic sensor, which supports four modes namely 100 kHz,400 kHz,1 MHz and 3.4 MHz and the dynamic range of magnetic field is ±50 gauss.

In the board, the magnetometer module is used in both magnetic detection and compass. In this experiment, the compass will be introduced first, and then the original data of the magnetometer will be checked.The main component of a common compass is a magnetic needle, which can be rotated by the geomagnetic field and point toward the geomagnetic North Pole (which is near the geographic South Pole) to determine direction.

Attention: this geomagnetic sensor built in the board can help us determine bearings by showing readings in the value from 0 to 360. And the system will ask us to calibrate it the first time it is put into operation by rotating the board.Please note that metal materials around may attenuate the accuracy of the reading and calibration.

**(2)Preparations:**

A. Attach the Micro:bit main board to your computer via the USB cable;

B. Open the offline version of Mu.

**(3) Test code1：**

Enter Mu software and open the file“Project 6：Code-1.py”to import code:

| File Type   | Route                                                                               | File Name            |
|-------------|-------------------------------------------------------------------------------------|----------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 6 Geomagnetic Sensor | Project 6：Code-1.py |

You can also input code in the editing window yourself.

(note:all English words and symbols must be written in English)

![](media/img/9f300bc24bcd7abb0604b8d71790ea43.png)

Click“Check”to examine error in the code. The program proves wrong if underlines and cursors are shown.

![](media/img/47d5a9ce25a4838ab5724ae0e1d10ea8.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/81de8b68e8a686fa34463ef641ce9982.png)

Note: We need to calibrate micro：bit due to different magnetic field in different areas. Micro:bit will prompt you to calibrate when you use it first time.

**(4)Test Result1：**

After uploading test code1 to micro:bit main board and powering the board via the USB cable, and pressing the button A, the board asks us to calibrate compass and the LED dot matrix shows “TILT TO FILL SCREEN”. Then enter the calibration page. Rotate the board until all 25 red LEDs are on as shown below.

![1(5)](media/img/acf3b8c0dee027d9e555fc708831f874.jpeg)

After that, a smile pattern![IMG_256](media/img/55ad39536dff7bdf66379a1da7a4c137.png) appears, which implies the calibration is done. When the calibration process is completed, pressing the button A will make the magnetometer reading display directly on the screen. And the direction north, east, south and west correspond to 0°, 90°, 180° and 270° respectively.

**(5)Test code2:**

For the below picture, the arrow pointing to the upper right when the value ranges from 292.5 to 337.5. Because 0.5 can’t be input in the code, the values we get are 293 and 338.

Then add other statements to make a set of complete code.

![](media/img/d1a4e9f62bdf690ba809ae35c347b233.png)

Enter Mu software and open the file“Project 6：Code-2.py”to import code:

| File Type   | Route                                                                               | File Name            |
|-------------|-------------------------------------------------------------------------------------|----------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 6 Geomagnetic Sensor | Project 6：Code-2.py |

You can also input code in the editing window yourself.(note:all English words and symbols must be written in English)

![](media/img/a4e455ea30e71670a31287ba20b04301.png)

Click“Check”to examine error in the code. The program proves wrong if underlines and cursors are shown.

![](media/img/5ff7c2fb4c5460e58dc85c77ba8791b3.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/c9a41e762b9c6f617523a3280f1ff28f.png)

**(6)Test Results2:**

Upload code 2 and plug micro:bit into power. After calibration, tilt micro:bit board, and the LED dot matrix displays the direction signs.

**(6)Code Explanation：**

| **from** microbit **import**                                 | Import the library file of micro：bit                        |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| compass.calibrate()                                          | Compass calibration                                          |
| **while True:**                                              | This is a permanent loop that makes micro:bit execute the code of it. |
| **if** button_a.is_pressed():  display.scroll(compass.heading()) | When the button A is pressed Micro:bit scrolls to show the value of compass |
| x = 0                                                        | Set variable x=0                                             |
| x = compass.heading()                                        | Set the value of compass to variable x                       |
| **if**...**elif**...**else**                                 | Condition judgement statement:if...else if...else            |
| display.show(Image("00999:""00099:""00909:""09000:""90000")) display.show(Image("99900:""99000:""90900:""00090:""00009")) display.show(Image("00900:""09000:""99999:""09000:""00900")) display.show(Image("00009:""00090:""90900:""99000:""99900")) display.show(Image("00900:""00900:""90909:""09990:""00900")) display.show(Image("90000:""09000:""00909:""00099:""00999")) display.show(Image("00900:""00090:""99999:""00090:""00900")) display.show(Image("00900:""09990:""90909:""00900:""00900")) | Micro:bit shows the Northeast arrow sign Micro:bit shows the Northwest arrow sign Micro:bit shows the west arrow sign Micro:bit shows the Southwest arrow sign Micro:bit shows the South arrow sign Micro:bit shows the South arrow sign  Micro:bit shows the East arrow sign Micro:bit shows the North arrow sign |

### Project 7: Accelerometer

![](media/img/24c31bb0174e2ac672203e5c36c6875e.png)

**(1)Project Introduction**

The Micro: Bit main board V2 has a built-in LSM303AGR gravity acceleration sensor, also known as accelerometer, with a resolution of 8/10/12 bits. The code section sets the range to 1g, 2g, 4g, and 8g.

We often use accelerometer to detect the status of machines.

In this project, we will introduce how to measure the position of the board with the accelerometer. And then have a look at the original three-axis data output by the accelerometer.

**(2)Preparations:**

A. Attach the Micro:bit main board to your computer via the USB cable;

B. Open the offline version of Mu.

**(3)Test Code1:**

Enter Mu software and open the file“Project 7：Accelerometer-1.py”to import code:

（[How to load the project code?](##AS)）

| File Type   | Route                                                                           | File Name                     |
|-------------|---------------------------------------------------------------------------------|-------------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 7：Accelerometer | Project 7：Accelerometer-1.py |

You can also input code in the editing window yourself.(note:all English words and symbols must be written in English)

![](media/img/e679777617dbfd2d1dddca26d670e2c5.png)

Click“Check”to examine error in the code. The program proves wrong if underlines and cursors are shown.

![](media/img/ff2cfa0f81328aa2431a6cc162954869.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/0090bd186e05df01900e3f485d8e5cbb.png)

**(4)Test Results1：**

After uploading the test code 1 to micro:bit main board and powering the board via the USB cable, if we shake the Micro: Bit main board，no matter at any direction, the LED dot matrix displays the digit “1”.

When it is kept upright（make its logo above the LED dot matrix）, the number 2 shows.

![\_DSC3687](media/img/1600323e3e61e331c248cbeda5ccdcfc.jpeg)

When it is kept upside down( make its logo below the LED dot matrix) , it shows as below.

![\_DSC3688](media/img/3be80acf957e53117f695801ce19c449.jpeg)

When it is placed still on the desk, showing its front side, the number 4 appears.

When it is placed still on the desk, showing its back side, the number 5 exhibits.

When the board is tilted to the left , the LED dot matrix shows the number 6 as shown below.

![\_DSC3703](media/img/326095934bcff0a925b4f9a09d6cf7d2.jpeg)

When the board is tilted to the right , the LED dot matrix displays the number 7 as shown below：

![\_DSC3697](media/img/185b0ac204e9b2c54dd8fa93d852568c.jpeg)

When the board is knocked to the floor, this process can be considered as a free fall and the LED dot matrix shows the number 8. (Please note that this test is not recommended for it may damage the main board.)

Attention: if you’d like to try this function, you can also set the acceleration to 3g, 6g or 8g. But still ,we do not recommend.

**(5)Test code2:**

Enter Mu software and open the file“Project 7：Accelerometer-2.py”to import code:

| File Type   | Route                                                                           | File Name                     |
|-------------|---------------------------------------------------------------------------------|-------------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 7：Accelerometer | Project 7：Accelerometer-2.py |

You can also input code in the editing window yourself.(note:all English words and symbols must be written in English)

![](media/img/d60bc5f04247351bb8a3d064911b8703.png)

Click“Check”to examine error in the code. The program proves wrong if underlines and cursors are shown.

![](media/img/578db73be841eeca543e8a0c97a43594.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/8ac0dc7298475fda0bd09192d52c18d2.png)

After referring to the MMA8653FC data manual and the hardware schematic diagram of the Micro: Bit main board, the accelerometer coordinate of the Micro: Bit are shown in the figure below:

![10](media/img/6303a0ac122680207fe856d9be38d01c.png)

**(6)Test Results2:**

Upload the test code 1 to micro:bit main board and power the board via the USB cable.

Click“REPL”and press the reset button. The value of acceleration on X axis, Y axis and Z axis are shown below:

![](media/img/52486ea525f5892b9407414b152524bf.png)

**(7)Code Explanation：**

| **from** microbit **import**                                 | Import the library file of micro：bit                        |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| gesture = accelerometer.current_gesture()                    | Set accelerometer.current_gesture() to gesture               |
| **while True:**                                              | This is a permanent loop that makes micro:bit execute the code of it. |
| **if** gesture == "shake":  display.show("1")  **if** gesture == "up":  display.show("2")  **if** gesture == "down":  display.show("3")  **if** gesture == "face up":  display.show("4")  **if** gesture == "face down":  display.show("5")  **if** gesture == "left":  display.show("6")  **if** gesture == "right":  display.show("7")  **if** gesture == "freefall":  display.show("8") | Shaking micro:bit board, number 1 will appear When log points to the North, number 2 will show up. When log points to the South, number 3 will be shown When the LED dot matrix is upward, the number 4 is shown. the number 5 is displayed when the LED dot matrix is downward. When Micro:bit board is tilt to the left, number 6 is shown. When micro:bit is tilt to the right When Micro:bit board is inclined to the right, number 7 is displayed. When it is free fall(accidentally making it fall), number 8 appears on dot matrix. |
| x = accelerometer.get_x()  y = accelerometer.get_y()  z = accelerometer.get_z() | Read the acceleration value on x axis，the return value is integer, and set x= the read value on x axis Read the acceleration value on y axis，the return value is integer, and set y= the read value on y axis Read the acceleration value on z axis，the return value is integer, and set z= the read value on z axis |
| print("x, y, z:", x, y, z)                                   | The value of acceleration will be shown                      |
| sleep(100)                                                   | Delay in 100ms                                               |

### Project 8: Light Detection

![](media/img/8c3f540a07aab97e1608ba8770837f7b.png)

**(1)Project Introduction**

In this project, we focus on the light detection function of the Micro: Bit main board. It is achieved by the LED dot matrix since the main board is not equipped with a photoresistor.

**(2)Preparations:**

A. Attach the Micro:bit main board to your computer via the USB cable;

B. Open the offline version of Mu.

**(3)Test Code:**

Enter Mu software and open the file“project 8：Light Detection.py”to import code:

（[How to load the project code?](##AS)）

| File Type   | Route                                                                             | File Name                     |
|-------------|-----------------------------------------------------------------------------------|-------------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 8：Light Detection | project 8：Light Detection.py |

You can also input code in the editing window yourself.

(note:all English words and symbols must be written in English)

![](media/img/b7420516b7192d2e8dc317c9a1b5e1b0.png)

Click“Check”to examine error in the code. The program proves wrong if underlines and cursors are shown.

![](media/img/419dbd60d837588e958a6154e49eae3e.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/bd01f7bbecc6972d4f3d51fcdc4c7f09.png)

**(4)Test Results:**

Upload the test code to micro:bit main board, power the board via the USB cable and click “Show console Device”.

Download code onto micro:bit board, don’t plug off USB cable. Click “REPL”and press the reset buttons, the light intensity value will be displayed, as shown below.

When the LED dot matrix is covered by hand, the light intensity showed is approximately 0; when the LED dot matrix is exposed to light,the light intensity displayed gets stronger with the light.

The 20 in the code is an arbitrary value of light intensity. If the current light level is less than or equal to 20, the icon moon will appear on the LED dot matrix. If it's bigger than 20, the sun will appear.

![](media/img/bfc3448e30f3f594602f837d06e70085.png)

**(5)Code Explanation:**

| **from** microbit **import**                | Import the library file of micro：bit                        |
| ------------------------------------------- | ------------------------------------------------------------ |
| gesture = accelerometer.current_gesture()   | Set accelerometer.current_gesture() to gesture               |
| **while True:**                             | This is a permanent loop that makes micro:bit execute the code of it. |
| Lightintensity = display.read_light_level() | Set display.read_light_level() to Lightintensity             |
| print("Light intensity:", Lightintensity)   | BBC microbit REPL prints the detected light intensity value  |
| sleep(100)                                  | Delay in 100ms                                               |



### Project 9: Speaker

![](media/img/ac515b9ae8891dc32f368a29f194a2fb.png)

**(1)Project Introduction**

Micro: Bit main board has an built-in speaker, which makes adding sound to the programs easier. It can also be programmed to air all kinds of tones, like playing the song *Ode to Joy.*

**(2)Preparations:**

A. Attach the Micro:bit main board to your computer via the USB cable;

B. Open the offline version of Mu.

**(3)Test Code1:**

Enter Mu software and open the file“Project 9：Speaker-1.py”to import code:

（[How to load the project code?](##AS)）

| File Type   | Route                                                                     | File Name               |
|-------------|---------------------------------------------------------------------------|-------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 9：Speaker | Project 9：Speaker-1.py |

You can also input code in the editing window yourself.

(note:all English words and symbols must be written in English)

![](media/img/97c53a60a6a7cf85d5b5f52fa9ef3b82.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/761d5e647d7e4d99e5ca0d144ae30e24.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/3dd37817037ce632148b383196f29ba2.png)

**(4)Test Results1:**

After uploading the test code1 to micro:bit main board and powering the board via the USB cable, the speaker utters sound and the LED dot matrix shows the logo of music.

**(5)Test Code2：**

Enter Mu software and open the file“Project 9：Speaker-2.py”to import code:

（[How to load the project code?](##AS)）

| File Type   | Route                                                                     | File Name               |
|-------------|---------------------------------------------------------------------------|-------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 9：Speaker | Project 9：Speaker-2.py |

You can also input code in the editing window yourself.

(note:all English words and symbols must be written in English)

![](media/img/1e78035f827b44322d6c4607b7a72880.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/52333d06756e26ed269000df8a8d47a0.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/8874215a0b73acd0e1c893d14c613474.png)

The musical score of *Ode to Joy* is attached below:

![乐谱](media/img/4a79470cc28f087a3834d168bc0c343f.jpeg)

Find more information about musical notations via this link:

https://en.wikipedia.org/wiki/Numbered_musical_notation

**(6) Test Results2:**

After uploading the test code2 to micro:bit main board and powering the board via the USB cable, the speaker on built-in the Micro:bit board plays the sound *Ode to Joy* and the LED dot matrix shows the logo of music.

**(7)Code Explanation：**

| **from** microbit **import** \*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Import the library of micro：bit                                      |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------|
| **import** audio                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Audio library                                                         |
| **while True:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | This is a permanent loop that makes micro:bit execute the code of it. |
| audio.play(Sound.GIGGLE)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Emit the“giggle”sound                                                 |
| display.show（Image.MUSIC_QUAVER）                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Music logo shows on the LED dot matrix on the micro:bit               |
| **import** music                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Import music library controlling sounds                               |
| tune = [ "E5:4"， "E5:4"， "F5:4"， "G5:4"， "G5:4"， "F5:4"， "E5:4", "D5:4"， "C5:4"， "C5:4"， "D5:4"， "E5:4"， "E5:4"， "D5:4", "D5:4"， "E5:4"， "E5:4"， "F5:4"， "G5:4"， "G5:4"， "F5:4", "E5:4"， "D5:4"， "C5:4"， "C5:4"， "D5:4"， "E5:4"， "D5:4", "C5:2"， "C5:4"， "D5:4"， "D5:4"， "E5:4"， "C5:4"， "D5:4", "E5:2"， "F5:2"， "E5:4"， "C5:4"， "D5:4"， "E5:2"， "F5:2", "E5:4"， "D5:4"， "C5:4"， "D5:4"， "G4:4"， "E5:4"， "E5:4", "E5:4"， "F5:4"， "G5:4"， "G5:4"， "F5:4"， "E5:4"， "D5:4", "C5:4"， "C5:4"， "D5:4"， "E5:4"， "D5:4"， "C5:2"， "C5:4", "D5:4"， "D5:4"， "E5:4"， "C5:4"， "D5:4"， "E5:2"， "F5:2", "E5:4"， "C5:4"， "D5:4"， "E5:2"， "F5:2"， "E5:4"， "D5:4", "C5:4"， "D5:4"， "G4:4"， "E5:4"， "E5:4"， "E5:4"， "F5:4", "G5:4"， "G5:4"， "F5:4"， "E5:4"， "C5:4"， "C5:4"， "C5:4", "D5:4"， "E5:4"， "D5:4"， "C5:2"， "C5:4"， "D5:4"， "C5:2", "C5:4"， "G5:4"， "F5:4"， "E5:2"， "E5:4"， "C5:4"， "B5:4", "A5:2"， "A5:4"， "F5:2"， "D5:2"， "C5:2"， "B4:2"， "D5:2", "B4:2"， "A4:2"， "G4:2"， "A4:2"， "B4:2"， "C5:2"， "E5:2", "D5:2"， "B4:2"， "C5:4"， "C5:2"， "C5:1"， "C5:4" ]  | Create variable”tune”to save notes                                    |
| music.play(tune)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Use the function play（）to play the notes reserved in “tune”         |
| sleep(1000)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | delay in 1000ms                                                       |



### Project 10: Touch-sensitive Logo

![](media/img/644695850097c5ade080bb4848b4b481.png)

**(1)Project Introduction**

The Micro: Bit main board V2 is equipped with a golden touch-sensitive logo, which can act as an input component and function like an extra button.

It contains a capacitive touch sensor that senses small changes in the electric field when pressed (or touched), just like your phone or tablet screen do. When you press it , you can activate the program.

**(2)Preparations:**

A. Attach the Micro:bit main board to your computer via the USB cable;

![5(1)](media/img/18c70cf16dcf8c9694a1af8b12530cf9.png)

B. Open the offline version of Mu.

**(3)Test Code：**

Enter Mu software and open the file“Project 10：Touch-sensitive Logo.py”to import code:

（[How to load the project code?](##AS)）

| File Type   | Route                                                                                     | File Name                           |
|-------------|-------------------------------------------------------------------------------------------|-------------------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 10：Touch-sensitive Logo   | Project 10：Touch-sensitive Logo.py |

You can also input code in the editing window yourself.

(note:all English words and symbols must be written in English)

![](media/img/6413ac46fad570a3c4020816f5825b95.png)

**How Micro:bit works?**

1.  The runtime is recorded in milliseconds(ms) .

2.  When you press button A, a variable named start is set to the current running time.
    
3.  When you press button B, the start time will be subtracted from the new running time to calculate how much time has passed since you started the stopwatch. This difference is added to the total time, which is stored in a variable named time.
    
4.  If you press the golden logo, the program will display the total elapsed time on the LED display. It converts time from milliseconds (thousandths of a second) to seconds by dividing by 1000. It uses the integer division operator to give an integer (integer) result.
    
5.  The program is also controlled by a Boolean variable named running. Boolean variable can only have two values: true or false. If "running" is "true", it means that the stopwatch has started. If "running" is false, it means that the stopwatch has not started or has stopped.
    
6.  If "running" is true, the beating heart pattern is displayed on the LED dot matrix screen.
    
7.  If the stopwatch has stopped and the "running" is false, when you press the golden logo, it will only display the time.
    
8.  If the stopwatch has been started and"running" is true, it only need to ensure that the time variable will only change when button B is pressed, and the code can also prevent false readings.

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/d5d7780d6a30d1958dfcc60f2808156f.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/bc1f18419b861de8677f658862f11c1b.png)

**(4)Test Results:**

Upload the test code to micro:bit main board and power the board via the USB cable, and press button A to start the stopwatch. When timing, the beating heart pattern will be displayed on the LED dot matrix screen. Press button B to stop it and you can start and stop it at any time. It will keep recording time, just like a real stopwatch. Press the golden logo on the front of the micro:bit to
display the measured time in seconds. And time can be reset to zero by pressing the reset button on the back of it.

### Project 11: Microphone

![](media/img/3073a8af772ab91ecf264843b37d3b74.png)![](media/img/7f0741158e734ff8449d5b87d5ba85f4.png)

**(1)Project Introduction**

The Micro: Bit main board is built with a microphone which can test the volume of ambient environment. When you clap, the microphone LED indicator turns on. Since it can measure the intensity of sound, you can make a noise scale or disco lighting changing with music. The microphone is placed on the opposite side of the microphone LED indicator and in proximity with holes that lets sound pass. When the board detects sound, the LED indicator lights up.

**(2)Preparations:**

A. Attach the Micro:bit main board to your computer via the USB cable;

B. Open the offline version of Mu.

**(3)Test Code：**

Enter Mu software and open the file“Project 11：Microphone-1.py”to import code:

（[How to load the project code?](##AS)）

| File Type   | Route                                                                          | File Name                   |
|-------------|--------------------------------------------------------------------------------|-----------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 11：Microphone  | Project 11：Microphone-1.py |

You can also input code in the editing window yourself. (note:all English words and symbols must be written in English)

![](media/img/f8e54928b80661d8556421995e15b131.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/8ea90194d301809309046a8100a21aa2.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/bfbf10a220b61035eda0c33b1b76597a.png)

**(4)Test Results1:**

After uploading test code to micro:bit main board and powering the board via the USB cable, the LED dot matrix displays pattern
“![](media/img/f496ba08ff8af3164cdbd5fc56cc5abb.png)”when you claps and pattern ![](media/img/04fdfc9060943954e7938bb1a741d626.png) when it is quiet around.

**(5)Test Code2：**

Enter Mu software and open the file“Project 11：Microphone-2.py”to import code:

（[How to load the project code?](##AS)）

| File Type   | Route                                                                         | File Name                   |
|-------------|-------------------------------------------------------------------------------|-----------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 11：Microphone | Project 11：Microphone-2.py |

You can also input code in the editing window yourself.

(note:all English words and symbols must be written in English)

![](media/img/339657d6a79240eff053511757645771.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/12715d31aa740e60cb791ec20372b787.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

Upload test code to micro:bit main board, power the board via the USB cable

![](media/img/bb5d1678a1c97c5ee241c6bf40031f52.png)

**(6)Test Results2:**

Upload test code to micro:bit main board and power the board via the USB cable. When the button A is pressed, the LED dot matrix displays the value of the biggest volume( please note that the biggest volume can be reset via the Reset button on the other side of the board ) while when clapping, the LED dot matrix shows the pattern of the sound.

**(7)Code Explanation：**

| **from** microbit **import** \*                                                                                                                                                                | Import the library of micro：bit                                                                                                                                                                                                                                                                                   |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **while True:**                                                                                                                                                                                | This is a permanent loop that makes micro:bit execute the code of it.                                                                                                                                                                                                                                              |
| **if** microphone.current_event() == SoundEvent.LOUD: display.show(Image.HEART) sleep(200) **if** microphone.current_event() == SoundEvent.QUIET: display.show(Image.HEART_SMALL)              | If there is a sound LED shows ❤ Delay in 200ms if no sound is detected LED lights show![](media/img/04fdfc9060943954e7938bb1a741d626.png)                                                                                                                                                                              |
| print("Light intensity:", Lightintensity)                                                                                                                                                      | BBC microbit REPL prints the detected light intensity value                                                                                                                                                                                                                                                        |
| maxSound = 0                                                                                                                                                                                   | The initial value of maxSound is 0                                                                                                                                                                                                                                                                                 |
| lights = Image("11111:""11111:""11111:""11111:""11111")                                                                                                                                        | Assign Image() to variable lights                                                                                                                                                                                                                                                                                  |
| soundLevel = microphone.sound_level()                                                                                                                                                          | Assign microphone.sound_level() to the variable soundLevel                                                                                                                                                                                                                                                         |
| **if** button_a.is_pressed(): display.scroll(maxSound) **else:** soundLevel = microphone.sound_level() display.show(lights \* soundLevel) **if** soundLevel \> maxSound: maxSound = soundLevel | if the button A is pressed LED lights show the sound value If not Assign microphone.sound_level() to the variable soundLevel As the sound changes，the micro:bit will display the breathing light effect If the sound value is higher than its maximum value the maximum sound value is equal to sound level value |

### Project 12: Touch-sensitive Logo Controlled Speaker

**(1)Project Introduction**

In the previous projects, we have learned about the touch-sensitive logo and the speaker respectively. In the project, we will combine these two components to play music. That’s the logo will be applied to control the speaker to sing songs.

**(2)Components Needed:**

| ![6(1)](media/img/e8f92efebfb955ca8a5f092f1eddce91.png) |  ![3](media/img/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

![5(1)](media/img/18c70cf16dcf8c9694a1af8b12530cf9.png)

Attach the Micro:bit main board to your computer via the USB cable.

**(4)Test Code:**

Enter Mu software and open the file“Project 12：Touch-sensitive Logo Controlled Speaker.py”to import code:

（[How to load the project code?](##AS)）

| File Type   | Route                                                                                                      | File Name                                              |
|-------------|------------------------------------------------------------------------------------------------------------|--------------------------------------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Project Code/Project 12：Touch-sensitive Logo Controlled Speaker | Project 12：Touch-sensitive Logo Controlled Speaker.py |

You can also input code in the editing window yourself.

(note:all words and symbols must be written in English)

![](media/img/823f061aa388150a575bca16cde3ac9f.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/5c6d153e9e0bdf85b811618a9218b017.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/df1d3cff8799373f8377383d79f450f5.png)

**(5)Test Results:**

After uploading test code to micro:bit main board and powering the board via the USB cable, the speaker plays the song *Happy Birthday to You* when the logo is touched.

**(6)Code Explanation：**

| **from** microbit **import** \*    | Import the library of micro：bit                                      |
|------------------------------------|-----------------------------------------------------------------------|
| **while True:**                    | This is a permanent loop that makes micro:bit execute the code of it. |
| display.show（Image.MUSIC_QUAVER） | Music logo shows on the LED dot matrix on the micro:bit               |
| **if** pin_logo. is_touched( ):    | When the logo is touched, it executes the following command           |
| music.play（music.BIRTHDAY）       | The speaker plays the song”*Happy Birthday to You*”                   |

### Project 13: Bluetooth Wireless Communication

With 16k RAM, micro:bit owns a low-consumption Bluetooth module and support Bluetooth communication. However, BLE heap stack occupies 12K RAM, which implies that there is no enough space to run microPython.

At present, microPython doesn’t support Bluetooth.

https://microbit-micropython.readthedocs.io/en/latest/ble.html

## Expansion Projects：

The former 14 projects are the introduction of sensors and modules. The further lessons are challenging for new starters.

Note: (G), marked on each sensor and module, is the negative pole and connected to “G”, ”-”or “GND”on the sensor shield or control board ; (V) is the positive pole and linked with V , VCC, + or 5V on the sensor shield or control board. And you need to connect a power in case that power supply is weak.

### Project 1：LED Blinks

**![K3](media/img/9ef7fe2f08cb904a3e3ba8713fabf3e1.png)**

**(1)Project Introduction**

We’ve set up the micro:bit smart home. Now let’s get started from the most simple experiment---LED blinks.

LED is a type of semiconductor called "Light Emitting Diode "which is an electronic device made of semiconductor materials (silicon, selenium, germanium, etc.). It features unidirectional conductivity, that is, the positive voltage is applied to the anode (long leg) and the cathode (short leg) of the diode. When the voltage of its anode is higher than the voltage of its cathode, thus, the diode is turned on(LED is on). When a reverse voltage is applied to the anode and cathode, the diode is disconnected(that is, the LED is off). Therefore, the disconnection and connection of the diode is equivalent to turning on and off LED. Light-emitting diodes have an anode (+) and a cathode (-), and they can only allow current to flow from one anode to the cathode. The components will be damaged if LED is directly connected to the power supply. It’s essential that a certain resistor must be connected in series in the LED circuit.

This LED module can be controlled by a basic code to turn on and off the light alternatively, simulating the breathing effect. And the time gap can be changed in the code. When the signal end S is at high level,the LED lights up while when it is at low level the LED reminds off.

**(2)About the Yellow LED：**

| Working Voltage:      | DC 3.3-5V                      | ![](media/img/98a79cea0b6dae9d2b47785668ed2f9b.png) |
|-----------------------|--------------------------------|-------------------------------------------------|
| Working current：     | \< 20mA                        |                                                 |
| Max Power：           | 0.1W                           |                                                 |
| Control Ports:        | Digital ports (digital input） |                                                 |
| Working Temperature： | -10°C \~ +50°C                 |                                                 |
| Display Color：       | Yellow                         |                                                 |

**(3)Test Code**

| Micro：bit Expansion Board | Yellow LED Module |
|----------------------------|-------------------|
| GND                        | G                 |
| 5V                         | V                 |
| S（16）                    | S                 |

Enter Mu software and open the file“Project 1：LED Blinks.py”to import code:

（[How to load the project code?](##AS))

| File Type   | Route                                                                                  | File Name                |
|-------------|----------------------------------------------------------------------------------------|--------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Expansion Project Code/Project 1：LED Blinks | Project 1：LED Blinks.py |

You can also input code in the editing window yourself.

(note:all words and symbols must be written in English)

![](media/img/7eb711b1a8026461d0ffe803dbd4e97c.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/5ad5bba99bc1fb8db89facd4b09ba1d2.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/14f5e55d28d20f1d7c373a67e4a7b3f8.png)

**(4)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON and press“1”on the rocket switch.

The micro:bit will show smile expression，and a yellow LED will flash with an interval of 1000ms.

**(5)Code Explanation：**

| **from** microbit **import** \* | Import the library file of micro：bit                                 |
|---------------------------------|-----------------------------------------------------------------------|
| display.show(Image.HAPPY)       | The LED dot matrix on the microbit displays a "smiley face" pattern   |
| **while True:**                 | This is a permanent loop that makes micro:bit execute the code of it. |
| Pin16.write_digital(1)          | Control pin 16 to output high level to light up the LED               |
| Pin16.write_digital(0)          | Control pin 16 to output low level, turn off the LED                  |
| sleep(1000)                     | Delay in 1000 ms                                                      |

### Project 2：Breathing LED

**![K3](media/img/9ef7fe2f08cb904a3e3ba8713fabf3e1.png)**

**(1)Project Introduction**

![0_LPC1768_PWM](media/img/bbcfcb9ae56abb7e80ee587246fc4be9.GIF)

In previous lesson, we control LED on and off and make it blink.

In this project, we will control LED’s brightness through PWM simulating breathing effect. Similarly, you can change the step length and delay time in the code so as to demonstrate different breathing effects.

PWM is a means of controlling the analog output via digital means. Digital control is used to generate square waves with different duty cycles (a signal that constantly switches between high and low levels) to control the analog output.In general, the input voltages of ports are 0V and 3V. What if the 1.5V is required? Or a switch among 1V, 1.5V and 3V? We cannot change resistors
constantly. For this reason, we resort to PWM.

For Micro:bit digital port voltage outputs, there are only LOW and HIGH levels, which correspond to the voltage outputs of 0V and 3V respectively. You can define LOW as“0”and HIGH as“1”, and let Micro:bit output five hundred“0”or‘1’within 1 second. If output five hundred‘1”, that is 3V; if all of which is‘0’,that is 0V; if output 250 01 pattern, that is 1.5V.

This process can be likened to showing a movie. The movie we watch are not completely continuous. Actually, it generates 25 pictures per second, which cannot be told by human eyes. Therefore, we mistake it as a continuous process. PWM works in the same way. To output different voltages, we need to control the ratio of 0 and 1. The more‘0’or‘1’ output per unit time, the more accurate the control.

In the graphic below, the green lines represent a regular time period. This duration or period is the inverse of the PWM frequency. In other words, with Micro:bit's PWM frequency at about 500Hz, the green lines would measure 2
milliseconds each. A call to analogWrite() is on a scale of 0-255, such that analogWrite(255) requests a 100% duty cycle (always on), and analogWrite(127) is a 50% duty cycle (on half the time).

![图1](media/img/704984700612966b997127cb9bde5c96.jpeg)

PWM is applied to light brightness adjustment, speed adjustment of motor and sound emitting

**Parameters of PWM：**

![IMG_256](media/img/b14db369936f55eef1dd18b050682a10.png)

A.pulse width (minimum / max)

B.Pulse cycle (insertion of pulse frequency within 1 second)

C.Voltage level（0V-3V）

D.There are commonly used PWM ports, namely P0, P1, P2, P3, P4 and P10. And there are other rarely used ports, namely P5, P6, P7, P8, P9, P11, P12, P13, P14, P15, P16, P19 and P20.

In the experiment, we connect the port S of yellow LED Module to the port S (16) of the expansion board. And P16 can also be used as a PWM interface.

**(2)About the Yellow LED：**

| Working Voltage:      | DC 3.3-5V                     | ![](media/img/98a79cea0b6dae9d2b47785668ed2f9b.png) |
|-----------------------|-------------------------------|-------------------------------------------------|
| Working Current：     | \< 20mA                       |                                                 |
| Max Power：           | 0.1W                          |                                                 |
| Control Port:         | digital port（digital input） |                                                 |
| Working Temperature： | -10°C \~ +50°C                |                                                 |
| Display Color：       | Yellow                        |                                                 |

**(3)Test Code**

| Micro:bit Expansion Board | Yellow LED Module |
|---------------------------|-------------------|
| GND                       | G                 |
| 5V                        | V                 |
| S（16）                   | S                 |

Enter Mu software and open the file“Project 2：Breathing LED .py”to import code:

（[How to load the project code?](##AS))

| File Type   | Route                                                                                     | File Name                    |
|-------------|-------------------------------------------------------------------------------------------|------------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Expansion Project Code/Project 2：Breathing LED | Project 2：Breathing LED .py |

You can also input code in the editing window yourself.

(note:all English words and symbols must be written in English)

![](media/img/62d4532d1ff4d05caa733f5c4db33bdd.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/30f1310b02f12f0bcac44e5718c5c635.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/5225389bdbd02e42479857975fa54c8c.png)

**(4)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON and press“1”on the rocket switch.

The micro:bit will show a smile expression, and LED smoothly changes its brightness from light to dark and back to light, continuing to do so, which is similar to a lung breathing in and out.

**(5)Code Explanation：**

| **from** microbit **import** \*      | Import the library file of micro：bit                                          |
|--------------------------------------|--------------------------------------------------------------------------------|
| display.show(Image.HAPPY)            | The LED dot matrix on the microbit displays a "smiley face" pattern            |
| **while True:**                      | This is a permanent loop that makes micro:bit execute the code of it.          |
| **for** index **in** range (0, 255): | range() is a function; for index in range(0, 255) is to assign 0\~255 to index |
| pin16.write_analog(index)            | Control pin 16 output analog index                                             |
| sleep(10)                            | Delay in 10 ms                                                                 |

### Project 3：6812 2x2 Full Color RGB

**![K9](media/img/5c6ab1e8af486882669028ff332f754a.png)**

**(1)Project Introduction**

6812 2X2 full-color RGB module integrates the controlling circuit and the illuminating circuit. Each LED is the same as a 5050 LED lamp bead, and each component is a pixel point. The inner pixel point includes a amplify driving circuit that latch signal from digital ports shapes, a high-precision internal oscillator and and a 12V high voltage programmable current control portion,
which effectively ensures that the color of the pixel point.

The data protocol uses a single-line zero code communication method. After the pixel point is reset, the S-terminal receives the data transmitted from the controller. First, the 24bit data sent by the first pixel is extracted by the first pixel point, and sent to the internal portion of the pixel point.

It has the advantages of low-voltage driving, environmental protection, high brightness, large scattering angle, good consistency, ultra-low power, long life expectancy.

**(2)About the 6812 2x2 Full-color RGB:**

| Working Voltage：                               | DC 3.3-5V  | Max Working Current： | 200mA        | Max Power:          | 1W                                |
|-------------------------------------------------|------------|-----------------------|--------------|---------------------|-----------------------------------|
| Working Temperature：                           | -10℃\~+50℃ | Source of light：     | SMD 5050 RGB | IC Type：           | 4 pcs/WS2811                      |
| Gray Scale：                                    | 256        | Illuminating Angle：  | 180°         | Illuminating Color: | Red, yellow, blue,green and white |
| ![](media/img/29efaf32be2cfacb8d2f8f3438772236.png) |            |                       |              |                     |                                   |

**(3)Test Code1**

| Micro:bit Expansion Board | 6812 2x2 Full-color RGB Module |
|---------------------------|--------------------------------|
| GND                       | G                              |
| 5V                        | V                              |
| S（14）                   | S                              |

Enter Mu software and open the file“Project 3：6812 2x2 full color RGB-1.py”to import code:

（[How to load the project code?](##AS))

| File Type   | Route                                                                                               | File Name                               |
|-------------|-----------------------------------------------------------------------------------------------------|-----------------------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Expansion Project Code/Project 3：6812 2x2 Full Color RGB | Project 3：6812 2x2 full color RGB-1.py |

You can also input code in the editing window yourself.(note:all English words and symbols must be written in English)

![](media/img/a737775a44fe43cf1b1b633c121f82c8.png)

![](media/img/1bf83384705504e2eed2d5c00b1e9958.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/85c0bee042fca2fcfcae8d4437f3c85a.png)

![](media/img/1bf83384705504e2eed2d5c00b1e9958.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/f4ac5e42ac0b64d447790f901df61358.png)

![](media/img/1bf83384705504e2eed2d5c00b1e9958.png)

**(4)Test Results1:**

Upload the test code1 to the micro:bit，plug in power, dial the DIP switch to ON and press “1”on the rocket switch. You will view the 6812 RGB module display red, orange,yellow, green, blue,Indigo, violet, purple and white, in loop way.

**(5)Test Code2:**

Enter Mu software and open the file“Project 3：6812 2x2 full color RGB-2.py”to import code:

（[How to load the project code?](##AS))

| File Type   | Route                                                                                               | File Name                               |
|-------------|-----------------------------------------------------------------------------------------------------|-----------------------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Expansion Project Code/Project 3：6812 2x2 Full Color RGB | Project 3：6812 2x2 full color RGB-2.py |

You can also input code in the editing window yourself.(note:all English words and symbols must be written in English)

![](media/img/e55988b9cbe8d9cbb07f947faa6fb530.png)

![](media/img/e1ea5fb6ffeca4e9ec0f57a55ad98159.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/8373c17bc6d7d5d1629c267a71e7541b.png)

![](media/img/e1ea5fb6ffeca4e9ec0f57a55ad98159.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/bff28bc32ecd2b74322d2829abc9985f.png)

![](media/img/e1ea5fb6ffeca4e9ec0f57a55ad98159.png)

**(6)Test Results2:**

Upload the test code 2 to the micro:bit，plug in power, dial the DIP switch to ON and press“1”on the rocket switch.

You can view four WS2812RGB lights light up，like a flowing light.

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

**(7)Test Code3:**

Enter Mu software and open the file“Project 3：6812 2x2 full color RGB-3.py”to import code:

（[How to load the project code?](##AS))

| File Type   | Route                                                                                               | File Name                               |
|-------------|-----------------------------------------------------------------------------------------------------|-----------------------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Expansion Project Code/Project 3：6812 2x2 Full Color RGB | Project 3：6812 2x2 full color RGB-3.py |

You can also input code in the editing window yourself.

(note:all words and symbols must be written in English)
![](media/img/f17e7bfa4980794c0613636140fe74df.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/3de934e3c0c3bcd19359f7566338eaee.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.
![](media/img/4f149f74c89ee476fd192322bcca3723.png)

**(8)Test Results3：**

Upload the test code 3 to the micro:bit，plug in power, dial the DIP switch to ON and press“1”on the rocket switch.

Then you will see 4 WS2812RGB lights light up with random colors, like a flowing light.

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

**(9)Code Explanation：**

| **from** microbit **import** \*                                                                                                                                                                                                                                             | Import the library file of micro：bit                                                                                                                                                                                                                                                                                                           |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **import** neopixel                                                                                                                                                                                                                                                         | Import the library file of neopixel                                                                                                                                                                                                                                                                                                             |
| np = neopixel.NeoPixel(pin14, 4)                                                                                                                                                                                                                                            | Set Neopixel as pin P14 to initialize the light with 4 LEDs                                                                                                                                                                                                                                                                                     |
| np.clear()                                                                                                                                                                                                                                                                  | RGB on Neopixel are all off                                                                                                                                                                                                                                                                                                                     |
| **while True:**                                                                                                                                                                                                                                                             | This is a permanent loop that makes micro:bit execute the code of it                                                                                                                                                                                                                                                                            |
| **for** pixel_id1 **in** range(0, len(np)):                                                                                                                                                                                                                                 | Set pixel of RGB in （0，len（np））to pixel_id1                                                                                                                                                                                                                                                                                                |
| for index in range(0, 4):                                                                                                                                                                                                                                                   | Set pixel of RGB in (0,4) to index                                                                                                                                                                                                                                                                                                              |
| np.show()                                                                                                                                                                                                                                                                   | Display current pixel on Neopixel                                                                                                                                                                                                                                                                                                               |
| np[pixel_id1] = (255, 0, 0) np[pixel_id2] = (255, 165, 0) np[pixel_id3] = (255, 255, 0) np[pixel_id4] = (0, 255, 0) np[pixel_id5] = (0, 0, 255) np[pixel_id6] = (75, 0, 130) np[pixel_id7] = (238, 130, 238) np[pixel_id8] = (160, 32, 240) np[pixel_id9] = (255, 255, 255) |  Set pixel_id1 to display red color Set pixel_id2 to display orange color Set pixel_id3 to display yellow color Set pixel_id4 to display green color Set pixel_id5 to display blue color Set pixel_id6 to display indigo color Set pixel_id7 to display violet color Set pixel_id8 to display purple color Set pixel_id9 to display white color |
| from random import randint                                                                                                                                                                                                                                                  | Import randint from random variables                                                                                                                                                                                                                                                                                                            |
| np[pixel_id] = (R, G, B)                                                                                                                                                                                                                                                    | Set pixel_id to display rainbow color                                                                                                                                                                                                                                                                                                           |
| R = 0 G = 0 B = 0                                                                                                                                                                                                                                                           | Set the initial value of R to 0 Set the initial value of G to 0 Set the initial value of B to 0                                                                                                                                                                                                                                                 |
| R = randint(10, 255) G = randint(10, 255) B = randint(10, 255)                                                                                                                                                                                                              | Set R=randint(10, 255) Set G=randint(10, 255) Set B=randint(10, 255)                                                                                                                                                                                                                                                                            |

### Project 4：PIR Motion Sensor

**![K18](media/img/83f7a844eac4e1ef73cea6494f9238c7.png)**

**(1)Project Introduction**

The Pyroelectric infrared motion sensor can detect infrared signals from moving objects, and output switching signals. Applied to a variety of occasions, it can detect movement of human body.

Conventional pyroelectric infrared sensors are much more bigger, with complex circuit and lower reliability. Yet, this new pyroelectric infrared motion sensor, is more practical. It integrates a digital pyroelectric infrared sensor and connecting pins. It features higher sensibility and reliability, lower power consumption, light weight, small size, lower voltage working mode and simpler peripheral circuit.

**(2)About PIR Motion Sensor:**

| Working Voltage：      | DC 4.5-6.5V                                          | ![](media/img/ee515734c07dde5b3e5c06f3916e6b74.png)![KS0052 (1)](media/img/3ced83ccadf7d3ef5783ddb224cf3e4d.jpeg) |
|------------------------|------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| Max Working Current：  | 50MA                                                 |                                                                                                           |
| Static Current:        | \<50uA                                               |                                                                                                           |
| Control Port：         | Digital output (high level is 3.3V，low level is 0V) |                                                                                                           |
| Control Signals:       | Digital signal 1/0                                   |                                                                                                           |
| Working Temperature：  | -10 \~ 50 ℃                                          |                                                                                                           |
| Max detection distance | 4m                                                   |                                                                                                           |
| Sensing Angle：        | ＜100°                                               |                                                                                                           |
| Trigger Way:           | L doesn’t repeatedly trigger/H trigger repeatedly    |                                                                                                           |

Note：

1\. The maximum distance is 4 meters during testing.

2\. In the test, open the white lens to check rectangular sensing part. When the long line of the sensing part is parallel to the ground, the distance is the best.

3\. In the test, covering the sensor with white lens can sense the distance precisely.

4\. The distance is best at 25℃, and the detection distance value will reduce when temperature exceeds 30℃.

5\. After powering up and uploading the code, you can start testing after 5-10 seconds, otherwise the sensor is not sensitive.

**(3)Test Code:**

| Micro:bit Expansion Board | PIR Motion Sensor |
|---------------------------|-------------------|
| GND                       | G                 |
| 5V                        | V                 |
| S（15）                   | S                 |

Enter Mu software and open the file“Project 4：PIR motion sensor.py”to import code:

（[How to load the project code?](##AS))

| File Type   | Route                                                                                         | File Name                       |
|-------------|-----------------------------------------------------------------------------------------------|---------------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Expansion Project Code/Project 4：PIR Motion Sensor | Project 4：PIR motion sensor.py |

You can also input code in the editing window yourself.

(note:all English words and symbols must be written in English)
![](media/img/76e5fc125a5242d8e0040a73f9d42f84.png)

Click “Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/e5c1015f91aa0046a4d4e8dcd9486323.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.
![](media/img/33b25b21ae866b505339d03bfea0d2c0.png)

**(4)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON and press“1”on the rocket switch.

Click“**REPL**”and then press the reset button on the back of the board.

If PIR motion sensor detects someone nearby, the serial monitor will display “1”, and the indicator on the module will be off. If nobody is around, the serial monitor will show “0”, the indicator will be on.

As shown below:

![图片13-2](media/img/d0732dbe9160f8a8f8061388a332b0b4.png)

**(5)Code Explanation：**

| **from** microbit **import** \* | Import the library file of micro：bit                                                    |
|---------------------------------|------------------------------------------------------------------------------------------|
| display.show（Image.HAPPY）     | The LED dot matrix on the microbit displays a "smiley face" pattern                      |
| val = 0                         | Set the initial value of the variable val to 0                                           |
| **while True:**                 | This is a permanent loop that makes micro:bit execute the code of it.                    |
| val = pin15.read_digital()      | Assign the digital signal read by the PIR sensor connected to pin 15 to the variable val |
| print("digital signals:", val)  | BBC microbit REPL window prints the digital signal read by the PIR sensor                |
| sleep(100)                      | Delay in 100 ms                                                                          |

### Project 5：Induction Lamp

**(1)Project Introduction**

In the previous project experiment, we have mastered the working principle of the PIR motion sensor and its control method. In this project, we combine it with a yellow LED to control LED’s brightness.

**(2)Test Code:**

| Micro:bit Expansion Board | PIR Motion Sensor |   | Micro:bit Expansion Board | Yellow LED Module |
|---------------------------|-------------------|---|---------------------------|-------------------|
| GND                       | G                 |   | GND                       | G                 |
| 5V                        | V                 |   | 5V                        | V                 |
| S（15）                   | S                 |   | S（16）                   | S                 |

Enter Mu software and open the file“PProject 5：Induction Lamp.py”to import code:

（[How to load the project code?](##AS))

| File Type   | Route                                                                                      | File Name                    |
|-------------|--------------------------------------------------------------------------------------------|------------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Expansion Project Code/Project 5：Induction Lamp | Project 5：Induction Lamp.py |

You can also input code in the editing window yourself.

(note:all English words and symbols must be written in English)
![](media/img/68be593fb61227b3da2af07ac6835b81.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/91a4c37aec6dc5c887a8cc4837a1ab0f.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.
![](media/img/46aba3bab613db9d40436bf744be9240.png)

**(3)Test Results:**

Upload the test code to the micro:bit, plug in power, dial the DIP switch to ON and press“1”on the rocket switch. The micro:bit will show a smile image.

When the PIR motion sensor detects people, the yellow LED will be on; otherwise, the LED will be off.

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

**(4)Code Explanation：**

| **from** microbit **import** \*                                                             | Import the library file of micro：bit                                                                                                                                                        |
|---------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Pin16.write_digital(0)                                                                      | Set pin 16 to low level to turn off the LED                                                                                                                                                  |
| **while True:**                                                                             | This is a permanent loop that makes micro:bit execute the code of it.。                                                                                                                      |
| **If** pin15.read_digital() == 1： Pin16.write_digital(1) **else：** Pin16.write_digital(0) | If the PIR motion sensor connected to pin 15 detects the movement of nearby people: Pin 16 is set to high level to light up the LED Otherwise,pin 16 is set to low level to turn off the LED |

### Project 6: Servo

![](media/img/6f0776b01b35f18b0568158ffbbc7a77.png)

**(1)Project Introduction**

The servo, window and door of this smart home have been fixed together so the servo can be used to drive the window and door to open or close, which is quite smart. In this project we will focus on the servo.

Servo is a position control rotary actuator. It mainly consists of a housing, a circuit board, a core-less motor, a gear and a position sensor. Unlike motor which is often applied to control rotating speed and direction servo is used to control angle. Generally, the angle range of servo rotation is 0° \~180°.

It has 3 wires which are marked in brown, red, and orange respectively.

For different brands, its application may have slight difference. So it is recommended to refer to some documents before use. The servo we use is a very common one, wires in brown, red, and orange corresponding to "power negative, power positive, control signal" respectively.

![](media/img/69be958142b773acdae33eeef12afed7.png)

**(2)Working Principle of Servo：**

The rotation angle of servo motor is controlled by regulating the duty cycle of PWM (Pulse-Width Modulation) signal. The standard cycle of PWM signal is 20ms(50Hz). Theoretically, the width is distributed between 1ms-2ms, but in fact,
it's between 0.5ms-2.5ms. The width corresponds the rotation angle from 0° to 180°. But note that for different brand motors, the same signal may have different rotation angles.

![6780083(1)](media/img/0982cb7b28f4accde7d378ba812c8bcb.png)

After measurement, it is found that the pulse range of the steering gear is 0.65ms\~2.5ms. See more details in the table:

| high level time | Servo angle | Reference signal cycle time（20ms） |
|-----------------|-------------|-------------------------------------|
| 0.65ms          | 0°          | 0.65ms high level+19.35mslow level  |
| 1.5ms           | 90°         | 1.5ms high level+18.5mslow level    |
| 2.5ms           | 180°        | 2.5ms high level+17.5mslow level    |

**(3)About the Servo:**

| Working voltage：     | DC 4.8V〜6V                                            | Operational Angle： | About 180°(500→2500μsec) |
|-----------------------|--------------------------------------------------------|---------------------|--------------------------|
| Pulse width range：   | 500→2500 μsec                                          | Size：              | 22.9\*12.2\*30mm         |
| No-load speed：       | 0.12±0.01 sec/60°（DC 4.8V） 0.1±0.01 sec/60°（DC 6V） |                     |                          |
| No-load current：     | 200±20mA（DC 4.8V） 220±20mA（DC 6V）                  |                     |                          |
| Stop torque：         | 1.3±0.01kg·cm（DC 4.8V） 1.5±0.1kg·cm（DC 6V）         |                     |                          |
| Stop current：        | ≦850mA（DC 4.8V） ≦1000mA（DC 6V）                     |                     |                          |
| Standby Current：     | 3±1mA（DC 4.8V） 4±1mA（DC 6V）                        |                     |                          |
| Weight:               | 9±1g (without servo horn)                              |                     |                          |
| Working temperature： | -30℃\~60℃                                              |                     |                          |

Note: Supplying power via USB cable or computer may burn the servo; thus, we recommend using batteries.

**(4)Test Code：**

| Micro:bit Expansion Board | Servo       |
|---------------------------|-------------|
| GND                       | Brown Wire  |
| 5V                        | Red Wire    |
| S（8）                    | Orange Wire |

Enter Mu software and open the file“Project 6：Servo .py”to import code:

（[How to load the project code?](##AS))

| File Type   | Route                                                                             | File Name            |
|-------------|-----------------------------------------------------------------------------------|----------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Expansion Project Code/Project 6：Servo | Project 6：Servo .py |

You can also input code in the editing window yourself.(note:all English words and symbols must be written in English)

![](media/img/e429cd655a3135bbc0ac394a963a3116.png)

![](media/img/957357262ce2366326101ea334b4478f.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/671f325a1f6f3f58362f9423c60d87ce.png)

![](media/img/957357262ce2366326101ea334b4478f.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/97bb74e1fc2eef0c1e71a5fc05c29cbb.png)![](media/img/957357262ce2366326101ea334b4478f.png)

**(5)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON and press“1”on the rocket switch. The micro:bit will show smile expression, the servo will rotate 0°\~45°\~90°\~135°\~180°\~0°，in loop way. ([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

### Project 7: 130 Motor

![K38](media/img/f82a3a2efb591dc8dca216554e1d69cb.png)

**(1)Project Introduction**

130 motor adopts the HR1124S chip which is applied to single-channel H-bridge drive chip in direct current motor.

H-bridge driving part uses the PMOS and NMOS power tubes of low on-resistance. In addition, the HR1124S chip has the low standby and static current.

This motor is compatible with all kinds of MCU control boards. It comes with 2.54mm anti-reverse white connectors. In the experiment, you can take advantage of the voltage direction of IN+和IN- to control the rotation of motor and alter its speed via PWM signals.

**(2)Parameters：**

| Working Voltage：                               | 3.3-5V(DC)    | Max Current：             | 200mA (DC5V)                       |
|-------------------------------------------------|---------------|---------------------------|------------------------------------|
| Max Power：                                     | 1W            | Control port：            | Dual digital port（digital input） |
| Working Temperature：                           | -10°C \~+50°C | Environmental Attribute： | ROHS                               |
| ![](media/img/2498f64be175011ed8b3263749146e4f.png) |               |                           |                                    |

**(3)Test Code 1:（high/low level control）**

| Micro:bit Expansion Board | Motor |
|---------------------------|-------|
| GND                       | G     |
| 5V                        | V     |
| S（13）                   | IN+   |
| S（12）                   | IN-   |

Enter Mu software and open the file“Project 7：130 Motor-1.py”to import code:

（[How to load the project code?](##AS))

| File Type   | Route                                                                                 | File Name                 |
|-------------|---------------------------------------------------------------------------------------|---------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Expansion Project Code/Project 7：130 Motor | Project 7：130 Motor-1.py |

You can also input code in the editing window yourself.(note:all English words and symbols must be written in English)

![](media/img/6d8b152c4795b348dc6eef2e855d4f28.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/2dc6a41cbc79a9bc72f1ee4b1c8306cc.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/20f3bd72afac51e67401e04bfae882c7.png)

**(4)Test Code2：（PWM control）**

Enter Mu software and open the file“Project 7：130 Motor-2.py”to import code:

（[How to load the project code?](##AS))

| File Type   | Route                                                                                 | File Name                 |
|-------------|---------------------------------------------------------------------------------------|---------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Expansion Project Code/Project 7：130 Motor | Project 7：130 Motor-2.py |

You can also input code in the editing window yourself.(note:all English words and symbols must be written in English)

![](media/img/4b9b9147f1c44e051c144c059cb2a74a.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/13c7dd5f53eea49704c19c04a7490dfc.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/b153ce3ca32a68311246dfdb24ac1653.png)

**(5)Test Results:**

Upload the test code to the micro:bit, plug in power, dial the DIP switch to ON and press“1”on the rocket switch. The fan will rotate clockwise for 5s, stop 1, rotate anticlockwise for 5s and stop for 1s, in loop way. ([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

### Project 8：Lithium Battery Power Module

**(1)Project Introduction**

This module integrates a charging and discharging chip, which can be interfaced with an external rechargeable battery through the PH2.0MM interface. In the experiment,we use a single lithium battery.

It has a Micro USB port and a charging port for solar panels, which can supply power for an external lithium battery.

In addition, this module has a boost module which can increase the voltage of batteries to 6.6V. The DIP switch on the module is the OUTPUT switch of 6.6V. The pin G and V can output 6.6V and the pin S can read the battery voltage after the resistance 1/2 voltage.

**(2)Parameters：**

| Charging Port                             | Micro USB, HP2.0MM port for solar panels |
|-------------------------------------------|------------------------------------------|
| Input Voltage of ports of the solar panel | 4.4-6V                                   |
| constant-voltage charging                 | 4.15-4.24V                               |
| Max Charging Current                      | 800mA                                    |
| Output Port                               | 3 P 2.54mm Pins                          |
| Input Voltage                             | 6.6V                                     |
| Max Output Current                        | 800mA                                    |
| Batteries                                 | Single-cell Lithium Battery              |
| Environmental Attribute                   | ROHS                                     |

**(3)Schematic Diagram：**

![](media/img/189777dcc6b180028d01671c2ea49186.png)

**(4)Features：**

![](media/img/07e545ee5517782911cb24aac7b87a2d.png)

OLAR4.8-6.0V, the input port of power, is connected to polar panels.

The solar energy is converted into electric energy via solar panels.

![](media/img/ca26c0fdc91084511b3d9a948df1fd66.png)

BAT, the output port of power, is interfaced with the lithium battery holder(rechargeable batteries) and saves the electric energy into batteries.

![](media/img/252c3ee03fefe739a910924413f1cc62.png)

This is the switch. Slid to ON end, then the external lithium battery will be connected, supplying to the expansion board; on the contrary, slide to OFF, then the current of lithium battery will be disconnected.

![](media/img/92b0c19b4eab104090d92d8c8c7b8391.png)

You can charge the lithium battery via USB cable.

**Test the solar battery panel：**

We can connect the solar battery panel and an LED we provide together, as shown below.

Disconnect the power, after a while, you will see the LED light up.

![IMG_256](media/img/a4c83004e0303b67f36de54a9425c920.png)**![图2](media/img/5cbf09cac4f56831baf6224b1e9c546d.jpeg)**

### Project 9：1602 LCD

![KS0062 (4)](media/img/b28242c31d938ab51c634aa121490ffa.jpeg)

**(1)Project Introduction**

With I2C communication module, this is a display module that can show 2 lines with 16 characters per line.

It shows blue background and white word and connects to I2C interface of MCU, which highly save the MCU resources.

On the back of LCD display, there is a blue potentiometer for adjusting the backlight. The communication address defaults to 0x27.

The original 1602 LCD can start and run with 7 IO ports, but ours is built with Arduino IIC/I2C interface, saving 5 IO ports. Alternatively, the module comes with 4 positioning holes with a diameter of 3mm, which is convenient for you to fix on other devices.

Notice that when the screen gets brighter or darker, the characters will become more visible or less visible.

![](media/img/fc7e69308162f73eda88903c6caf90e5.png)

**(2)About 1602 I2C：**

| Working Voltage ：                                               | DC5V                                             | I2C Address：                                                      | 0x27                     | Control Port： | I2C      |
|------------------------------------------------------------------|--------------------------------------------------|--------------------------------------------------------------------|--------------------------|----------------|----------|
| Working Current：                                                | \< 130mA                                         | Working Temperature：                                              | 0°C \~ 45°C（recommend） | Driving Chip： | PCF8574T |
| GND: a pin connected to the ground                               |  VCC：A pin that connects to a +5V power supply  | SDA： A pin that connects to analog port A4 for IIC communication  |                          |                |          |
| SCL: a pin interfaced with SCL or A5，used for IIC communication | Backlight                                        | Adjustable contrast                                                |                          |                |          |

**(3)Test Code:**

| Micro:bit Expansion Board | I2C 1602 LCD Module |
|---------------------------|---------------------|
| GND                       | GND                 |
| 5V                        | 5V                  |
| SDA                       | SDA                 |
| SCL                       | SCL                 |

Enter Mu software and open the file“Project 9：1602 LCD.py”to import code:（[How to load the project code?](##AS))

| File Type   | Route                                                                                | File Name              |
|-------------|--------------------------------------------------------------------------------------|------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Expansion Project Code/Project 9：1602 LCD | Project 9：1602 LCD.py |

You can also input code in the editing window yourself.(note:all English words and symbols must be written in English)

![](media/img/33253c3d50fd18d7f730ac9e4a22c297.png)

![](media/img/3fbd2765e27deeacc1bf413abba317a3.png)

![](media/img/54c9d450bd1fcd6b7e789c6915e81be0.png)

![](media/img/cd16437ac6ba5a4dc5eaf5168b35c50e.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/8eda731b1de997da6bf61a5149bf3d79.png)

![](media/img/3fbd2765e27deeacc1bf413abba317a3.png)

![](media/img/54c9d450bd1fcd6b7e789c6915e81be0.png)

![](media/img/cd16437ac6ba5a4dc5eaf5168b35c50e.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/6809bcf0ca13eaf66c6a252e32c4ca21.png)

![](media/img/3fbd2765e27deeacc1bf413abba317a3.png)

![](media/img/54c9d450bd1fcd6b7e789c6915e81be0.png)

![](media/img/cd16437ac6ba5a4dc5eaf5168b35c50e.png)

**(4)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON and press“1”on the rocket switch.

The micro:bit board will show a smile image. Then rotate the knob of the potentiometer at the back of the LCD module, you will see“Keyestudio”at one row and numbers at the second row. In addition, the number increases by 1 with an interval of 0.5s.

Note: When the display doesn’t show characters, you can adjust the potentiometer behind the 1602LCD and backlight to make the 1602LCD display the corresponding character string.

### Project 10：Steam Sensor

**![K48](media/img/4aabe381a784188117ef190b4e45334f.png)**

**(1)Project Introduction**

This is a commonly used steam sensor. Its principle is to detect the amount of water by bare printed parallel lines on the circuit board. The more the water content is, the more wires will be connected. As the conductive contact coverage increases, the output voltage will gradually rise. It can detect water vapor in the air as well. The steam sensor can be used as a rain water detector and level switch. When the humidity on the sensor surface surges, the output voltage will increase.

The sensor is compatible with various microcontroller control boards, such as Arduino series microcontrollers. When using it, connect the sensor to the analog port of the Micro:bit microcontroller, and display the corresponding analog value on the serial monitor.

Note: the connection part is not waterproof. Therefore, don’t immerse it in the water please.

**(2)About the Stream Sensor：**

| Working Voltage：           | DC 3.3-5V                                                              | ![](media/img/3b0760476232188966281131ba9da7e5.png) |
|-----------------------------|------------------------------------------------------------------------|-------------------------------------------------|
| Working Temperature Range： | －10℃～＋70℃                                                           |                                                 |
| Max Working Current：       | 5uA (DC5V，when the two pins of the steam sensor are in short circuit. |                                                 |
| Control Port：              | Analog output                                                          |                                                 |

**(3)Test Code:**

| Micro:bit Expansion Board | Steam Sensor |
|---------------------------|--------------|
| GND                       | G            |
| 3V3                       | V            |
| S(0)                      | S            |

Enter Mu software and open the file“Project 10：Steam Sensor.py”to import code:

（[How to load the project code?](##AS))

| File Type   | Route                                                                                     | File Name                  |
|-------------|-------------------------------------------------------------------------------------------|----------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Expansion Project Code/Project 10：Steam Sensor | roject 10：Steam Sensor.py |

You can also input code in the editing window yourself.(note:all English words and symbols must be written in English)

![](media/img/13282ef7f6152eda08a03b40f86f33e4.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/e54c3f9c5e83f471b89646cfaf240194.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/aab6e72cbc91d6a39faf018d5e3f9218.png)

**(4)Test Results:**

Upload the test code, and plug in power with micro USB cable. Then the micro:bit will show“❤”. Click“REPL” and then press the reset button on the back of the board.The serial monitor will show the output data, and the steam sensor will read the analog signals at the signal end. The more the immersed area of the module, the larger the analog value.

As shown below;

![](media/img/b95535dc11fce9350feb80cc910dcdba.png)

### Project 11：Rains Alarm

**(1)Project Introduction**

Steam Sensor is a wide range of applications, such as raining alarm, automotive automatic scraping system, intelligent lighting system, and smart sunroof system. In the previous project experiment, we already know the working principle of Steam Sensor, then in this project experiment, we combine Steam Sensor, Micro:bit, and yellow LEDs, making a simple rain alarm.

**(2)Test Code:**

| Micro:bit Expansion Board | Steam Sensor |   | Micro:bit Expansion Board | Yellow LED Module |
|---------------------------|--------------|---|---------------------------|-------------------|
| GND                       | G            |   | GND                       | G                 |
| 3V3                       | V            |   | 5V                        | V                 |
| S（0）                    | S            |   | S（16）                   | S                 |

Enter Mu software and open the file“Project 11：Rains Alarm.py”to import code:（[How to load the project code?](##AS))

| File Type   | Route                                                                                    | File Name                  |
|-------------|------------------------------------------------------------------------------------------|----------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Expansion Project Code/Project 11：Rains Alarm | Project 11：Rains Alarm.py |

You can also input code in the editing window yourself.

(note:all words and symbols must be written in English)

![](media/img/e5097ed1ae414a2d1eb3fbd34cb11808.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/73dbd70a8b6d7b6ac6e2ee331584257a.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/4d4995a318f10bbff5039e73b2ae711c.png)

**(3)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON and press“1”on the rocket switch.The micro:bit will show smile expression. When the detected analog signals are more than 500, the micro:bit will emit “tick, tick”and the yellow LED will flash. Otherwise, no sound and LED is off.

### Project 12：Analog Gas（MQ-2）Sensor

**![K29](media/img/65c0010971634afa9cb0f266ab919617.png)**

**(1)Project Introduction**

This gas sensor is used for household gas leak alarms, industrial combustible gas alarms and portable gas detection instruments. Also, it is suitable for the detection of liquefied gas, benzene, alkane, alcohol, hydrogen, etc.,

The MQ-2 smoke sensor can be accurately a multi-gas detector, with the advantages of high sensitivity, fast response, good stability, long life, and simple drive circuit.

It can detect the concentration of flammable gas and smoke in the range of 300\~10000ppm. Meanwhile, it has high sensitivity to natural gas, liquefied petroleum gas and other smoke, especially to alkanes smoke.

It must be heated for a period of time before using the smoke sensor, otherwise the output resistance and voltage are not accurate. However, the heating voltage should not be too high, otherwise it will cause internal signal line to blow.

It belongs to the tin dioxide semiconductor gas-sensitive material. At a certain temperature, tin dioxide adsorbs oxygen in the air and forms negative ion adsorption of oxygen, reducing the electron density in the semiconductor, thereby increasing its resistance value.

When in contact with flammable gas in the air and smog, and the potential barrier at the grain boundary is adjusted by the smog, it will cause the surface conductivity to change. With this, information about the presence of smoke or flammable gas can be obtained. The greater the concentration of smoke or flammable gas in the air, the greater the conductivity, and the lower the output resistance, the larger the analog signal output. In addition, the sensitivity can be adjusted by rotating the potentiometer.

![](media/img/42e544fa258364c0625cfeb2d47a7f8c.png)

**(2)About Analog Gas Sensor（MQ-2)：**

| Working Voltage：          | 3.3-5V                            | ![](media/img/42a27e658a946a1d9845c5846db4b412.png) |
|----------------------------|-----------------------------------|-------------------------------------------------|
| Working Current：          | 160mA (DC5V)                      |                                                 |
| Working Temperature：      | 0°C \~ 40°C                       |                                                 |
| Control Port：             | Digital and analog output         |                                                 |
| Detection concentration：  | 300-10000ppm (combustible gas )   |                                                 |
| Rake Ratio：               | ≤0.6(R3000ppm/R1000ppm C3H8)      |                                                 |
| Sensitivity：              | Rs(in air)/Rs(1000ppmisobutane)≥5 |                                                 |
| Sensitive Resistance（Rs） | 2KΩ-20KΩ(in 2000ppm C3H8 )        |                                                 |

**Features：**

(1) Have a signal output instruction.

(2) Dual-channel signal output (analog output and TTL level output)

(3) TTL output effective signal is Low Level. (When the Low Level is output, the signal light will be on)

(4) The analog output is 0 \~ 5V voltage. The higher the concentration, the higher the voltage.

(5) a good sensitivity to liquefied gas, natural gas and urban gas.

(6) Have long-term life expectancy and reliable stability

(7) Fast response recovery.

**(3)Test Code:**

| Micro:bit Expansion Board | Analog Gas（MQ-2）Sensor |
|---------------------------|--------------------------|
| GND                       | G                        |
| 5V                        | V                        |
| S（1）                    | D                        |

Enter Mu software and open the file“Project 12：Analog Gas（MQ-2）Sensor.py”to import code:（[How to load the project code?](##AS))

| File Type   | Route                                                                                                 | File Name                               |
|-------------|-------------------------------------------------------------------------------------------------------|-----------------------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Expansion Project Code/Project 12：Analog Gas（MQ-2）Sensor | Project 12：Analog Gas（MQ-2）Sensor.py |

You can also input code in the editing window yourself.(note:all English words and symbols must be written in English)

![](media/img/04c54b30c1b5e457d537fbdb1f97a330.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/2dae16142f636cb55099764bc14b560a.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/e43e7710fa8ad1a63d9fe5c47bb7e197.png)

**(4)Test Results:**

Upload the test code to the micro:bit, plug in power and dial the DIP switch to ON. Then the micro:bit will show smile expression.Click“REPL”and then press the reset button on the back of the board.

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

When the gas sensor detects no flammable gases, the serial monitor prints 1. While when you turn on a fire lighter near it, it detects gases, the serial monitor prints 0 and the red indicator on the module lights up as shown below:

(By the way, the sensitivity of this sensor can be adjusted by rotating the blue potentiometer on it.)

![](media/img/9a316e7d34da86b441507970a4d03042.png)

### Project 13：Gas Leakage Detector

**(1) Project Description:**

This MQ-2 gas sensor is used for household gas leak alarms, industrial combustible gas alarms and portable gas detection instruments. And it is suitable for the detection of liquefied gas, benzene, alkane, alcohol, hydrogen, etc., and widely used in various fire alarm systems. It can be accurately a multi-gas detector, and has the advantages of high sensitivity, fast response,
good stability, long life, and simple drive circuit.

It can detect the concentration of flammable gas and smoke in the range of 300\~10000ppm.Meanwhile, it has high sensitivity to natural gas, liquefied petroleum gas and other smoke, especially to alkanes smoke.

We will make a gas leakage detector with a MQ-2 gas sensor, a yellow LED and a 1602 LCD.

**(2)Test Code:**

| Micro:bit Expansion Board | Analog Gas（MQ-2）Sensor |   | Micro:bit Expansion Board | Yellow LED Module |
|---------------------------|--------------------------|---|---------------------------|-------------------|
| GND                       | G                        |   | GND                       | G                 |
| 5V                        | V                        |   | 5V                        | V                 |
| S（1）                    | D                        |   | S（16）                   | S                 |

Enter Mu software and open the file“Project 13：Gas Leakage Detector.py”to import code:

（[How to load the project code?](##AS))

| File Type   | Route                                                                                             | File Name                           |
|-------------|---------------------------------------------------------------------------------------------------|-------------------------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Expansion Project Code/Project 13：Gas Leakage Detector | Project 13：Gas Leakage Detector.py |

You can also input code in the editing window yourself.

(note:all words and symbols must be written in English)

![](media/img/9761b6d63396f9f886158b32c5409b37.png)

![](media/img/1e4e5a70d91f42626e909b16594725fc.png)

![](media/img/c89faf119e35a5c9c77c550d305e74ce.png)

![](media/img/f3dd576d2c01c6a96c4b3cf4d1826acf.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/b21e04fb8b415c379948292e96c0e03a.png)

![](media/img/1e4e5a70d91f42626e909b16594725fc.png)

![](media/img/c89faf119e35a5c9c77c550d305e74ce.png)

![](media/img/f3dd576d2c01c6a96c4b3cf4d1826acf.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/46ff9e9a8748d1411f03dbeb14ab5653.png)

![](media/img/1e4e5a70d91f42626e909b16594725fc.png)

![](media/img/c89faf119e35a5c9c77c550d305e74ce.png)

![](media/img/f3dd576d2c01c6a96c4b3cf4d1826acf.png)

**(3)Test Results：**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON and press“1”on the rocket switch.

The micro:bit will show a smile image. Make a fire lighter close to the gas sensor, 1602 LCD will display“MQ-2”at the first row and show“gas leakage”at the second row. At same time, it will emit“tick,tick” sound and LED will flash.

### Project 14：Multiple Functions

**(1)Project Description:**

The final lesson is the combination of all modules and sensors. It is an analog smart home.

**(2)Test Code:**

Enter Mu software and open the file“Project 14：Multiple Functions.py”to import code:

（[How to load the project code?](##AS))

| File Type   | Route                                                                                           | File Name          |
|-------------|-------------------------------------------------------------------------------------------------|--------------------|
| Python file | KS4027 folder/Python Tutorial/Python Code/Expansion Project Code/Project 14：Multiple Functions | Multiple Functions |

You can also input code in the editing window yourself.(note:all English words and symbols must be written in English)

![IMG_256](media/img/d757bb27de772d29758c46158f19b9b7.png)

![](media/img/0475e7151be7306862d985885707e237.png)

![](media/img/8d2e672c049a8331ea23b7f000ece8b1.png)

![](media/img/7d8e7129fabd64fed59c64376ebf66ed.png)

![](media/img/0a11382ba694f469c6dac319ba41809c.png)

![](media/img/fbc59f4020d7668c8c9f50ce4a7a04eb.png)

![](media/img/81697a2932ebff0be59acf562fa11d3e.png)

![](media/img/cfa0f66c61c12df1f1678914fa5f9f60.png)

Click“Check”to examine error in the code. The underlines and cursors signal that the program is wrong.

![](media/img/e68af9abe57120253d3d52a2369e6f51.png)

![](media/img/0475e7151be7306862d985885707e237.png)

![](media/img/8d2e672c049a8331ea23b7f000ece8b1.png)

![](media/img/7d8e7129fabd64fed59c64376ebf66ed.png)

![](media/img/0a11382ba694f469c6dac319ba41809c.png)

![](media/img/fbc59f4020d7668c8c9f50ce4a7a04eb.png)

![](media/img/81697a2932ebff0be59acf562fa11d3e.png)

![](media/img/cfa0f66c61c12df1f1678914fa5f9f60.png)

If the code is correct, connect micro:bit to computer and click“Flash”to download code to micro:bit board.

![](media/img/faa0a4849467bebae875ab5dd739ad0e.png)

![](media/img/0475e7151be7306862d985885707e237.png)

![](media/img/8d2e672c049a8331ea23b7f000ece8b1.png)

![](media/img/7d8e7129fabd64fed59c64376ebf66ed.png)

![](media/img/0a11382ba694f469c6dac319ba41809c.png)

![](media/img/fbc59f4020d7668c8c9f50ce4a7a04eb.png)

![](media/img/81697a2932ebff0be59acf562fa11d3e.png)

![](media/img/cfa0f66c61c12df1f1678914fa5f9f60.png)

**(3)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON and press“1”on the rocket switch.The micro:bit will show a smile image.

When the analog value detected by the steam sensor is bigger than 400, the 5 WS2812 RGB lights on the 6812 RGB module are all on, displaying in red, orange,yellow, green, blue, Indigo, violet, purple and white, in loop way.

Then the window is closed, the door and the fan rotate;

Make a fire lighter close to the gas sensor, 1602 LCD will display“MQ-2”at the first row and show“gas leakage”at the second row. At same time, it will emit“tick,tick” sound and the yellow LED will flash. Otherwise,the speaker makes no sound, the LED reminds off and the 1602LCD displays no characters.

## Resources:

[https://fs.keyestudio.com/KS4027-4028](https://fs.keyestudio.com/KS4027-4028)














