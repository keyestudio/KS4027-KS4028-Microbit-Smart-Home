# **Makecode Tutorial**

## Getting Started with Micro:bit

The following instructions are applied for Windows system but can also serve as
a reference if you are using a different system.

### 1 Write code and program

This chapter describes how to write program and load the program to the Micro:
Bit main board V2.

You are recommended to browse the official website of Micro:bit for more
details, and the link is attached below:

[https://microbit.org/guide/quick/](Https://microbit.org/guide/quick/)

**Step 1: connect the Micro: Bit main board with your computer**

Firstly, link the Micro: Bit main board with your computer via the USB cable.
Macs, PCs, Chromebooks and Linux（including Raspberry Pi）systems are all
compatible with the Micro: Bit main board.

Note that if you are about to pair the board with your phone or tablet, please
refer to this link:

[https:/microbit.org/get-started/user-guide/mobile/](https://microbit.org/get-started/user-guide/mobile/)

![6(1)](media/image/b5a90ee5338cd7fb96e135fe71a79a61.png)
![5(1)](media/image/18c70cf16dcf8c9694a1af8b12530cf9.png)

Secondly, if the red LED on the back of the board is on, that means the board is
powered. When your computer communicates with the main board via the USB cable,
the yellow LED on it will flashes. For example, it will flicker when you burn a
“hex”file.

Then Micro: bit main board will appear on your computer as a driver named
“MICROBIT(E:)”. Please note that it is not an ordinary USB disk as shown below.

![](media/image/a2b53f93f4c24b81fc5cdb5986fd100d.png)

**Step 2: write programs**

View the link <https://makecode.microbit.org/> in your browser;

Click ‘New Project’;

The dialog box‘Create a Project’ appears, fill it with‘heartbeat’and click
‘Create √’to edit.

(If you are running Windows 10 system, it is also viable to edit on the APP
MakeCode for micro:bit , which is exactly like editing in the website. And the
link to the APP is
[https://www.microsoft.com/zh-cn/p/makecode-for-micro-bit/9pjc7sv48lcx?ocid=badgep&rtc=1&activetab=pivot:overviewtab](https://www.microsoft.com/zh-cn/p/makecode-for-micro-bit/9pjc7sv48lcx?ocid=badgep&rtc=1#activetab=pivot:overviewtab)
)

Take Google Chrome as an example as shown below and it is almost the same for
other browsers.

![](media/image/fd741a4a932cf25b5165c8135b512848.png)

![](media/image/f76062b0607cfca5d20bc26199b2f711.png)

Write a set of micro:bit code. You can drag some modules in the Blocks to the
editing area and then run your program in Simulator of MakeCode editor as shown
in the picture below which demonstrates how to edit ‘heartbeat’ program .

The path to the demonstration video:

.../2. Makecode Tutorial\\Makecode Code\\Project Code/Project 1：Heart beat

The next chapter will illustrate more details about Makecode.

![](media/image/215b27bc1633c62d16fe208e06e39ad9.png)

Click the arrow behind “JS JavaScript”to choose between“JavaScript”or
“Python”and you will find the corresponding program in JavaScript language or
Python language as shown below:

![](media/image/67b86dacacfb0d716068af592d79382a.png)

![](media/image/c3950b45a80b660c60d4ca8544c6acbd.png)

**Step 3: download code**

If your computer is Windows 10 and you have downloaded the APP MakeCode for
micro:bit to write program, what you will have to do to download the program to
your Micro: Bit main board is merely clicking the ‘Download’ button, then all is
done.

If you are writing program through the website, following these steps:

Click the ‘Download’ in the editor to download a "hex" file, which is a compact
program format that the Micro: Bit main board can read. Once the hexadecimal
file is downloaded, copy it to your board just like the process that you copy
the file to the USB driver. If you are running Windows system, you can also
right-click and select ‘Send to → MICROBIT(E:) ‘to copy the hex file to the
Micro: Bit main board.

![](media/image/c5b462b6e3acbfedf6c9b22e4651d69a.png)

![无标题](media/image/a81d4430eb152346d13bf67b2233b9db.png)

You can also directly drag the "hex" file onto the MICROBIT (E:) disk.

![无标题](media/image/fe0f2de72ba0b38f00403f1aaef7f514.png)

![无标题](media/image/b4f3602c0e192646f77b150e2acaf947.png)

During the process of copying the downloaded hex file to the Micro: bit main
board, the yellow signal light on the back side of the board flashes. When the
copy is completed, the yellow signal light will stop flashing and remain on.

**Step 4: run the program：**

After the program is uploaded to the Micro: bit main board, you could still
power it via the USB cable or change to via an external power. The 5 x 5 LED dot
matrix on the board displays the heartbeat pattern.

| ![7](media/image/672bfb4d87b938fc586a849bff0229fe.png) | ![8](media/image/d61a26d2f2367f0378974832f679efe1.png) |
|--------------------------------------------------|--------------------------------------------------|
| Power via USB cable                              | Power via external power (3V)                    |

**Caution:**

When you programs each time, the driver of Micro: bit will automatically eject
and return and your hexadecimal files will disappear . And the board can only
have access to hexadecimal files (hex) and save no other files.

**Step 5：about other programming languages**

This chapter has described how to use the Micro:bit main board.

But except for the Makecode graphical programming introduced you can also write
Micro:bit programs in other languages. Go to the link:
<https://microbit.org/code/> to know about other programming languages , or view
the link: <https://microbit.org/projects/>, to find something you want to have a
go.

### 2.Makecode：

Browse <https://makecode.microbit.org/> and enter Makecode online editor or open
the APP MakeCode for micro:bit of Windows 10.

![](media/image/285f5ee70c3d95855f87a17d227b8675.png)

Click“New Project”, and input“heartbeat”, then click “create √”to enter Makecode
editor, as shown below:

![IMG_256](media/image/5d8174f605724953bcb4a00edade8f30.png)

There are blocks“on start”and“forever”in the code editing area.

When the power is plugged or reset,“on start”means that the code in the block
only executes once, while“forever”implies that the code runs cyclically.

### 3 Quick Download

As mentioned before, if your computer is Windows 10 and you have downloaded the
APP MakeCode for micro:bit to write programs, the program written can be quickly
downloaded to the Micro: Bit main board by selecting ‘Download’.

While it is a little more trickier if you are using a browser to enter Makecode.
However, if you use Google Chrome, suitable for Linux，macOS and Windows 10, the
process can be quicker too.

We use the webUSB function of Chrome to allow the internet page to access the
hardware device connected USB.

You could refer to the following steps to connect and pair devices.

**Device pairing:**

Connect micro:bit to your computer by USB cable.

Click“...”beside“Download”and tap“Connect device”;

![Untitled](media/image/39effe268391a9a64558a0438f5f2fe5.png)

Click“Next”;

![](media/image/e843e223f125fdd0448c49d80e576d39.png)

Click another“Next”;

![](media/image/fe5c6991e1ba8bd46f0bc6b7069b91c1.png)

Then select the corresponding device and click“Connect”. If no devices shows up
for selection, please refer to:

[https://makecode.microbit.org/device/usb/webusb/troubleshoot](https://makecode.microbit.org/device/usb/webusb/troubleshoot%20)

And for updating the firmware of the Micro:bit:
[https://microbit.org/guide/firmware/](https://microbit.org/guide/firmware/%20)
.

If the links are too troublesome for you , then you can also turn to our
‘Troubleshooting Downloads with WebUSB’and“upload the firmware”in the folder we
provided in the link:

https://fs.keyestudio.com/KS4027-4028

![Untitled](media/image/4cf10fecd346658a9943e900eef2e265.png)

Click“Done”to finish the pairing.

![](media/image/0b3776a491c27034738926b3f958b3f0.png)

![](media/image/37f01f5a75b4127a193a1099bdd142d3.png)

**Download program:**

After the pairing, click “download”to directly download the program to the
board. If it is successfully downloaded, the icon
![](media/image/af296c6d48f189a98fcb96522182ffa9.png) will shift to
![](media/image/c55e4d43d82301258cbc0367cb3b3d49.png).

![Untitled](media/image/96fbd5a50eb87de8ad464cbbd09624f1.png)

### 4.Makecode extension library:

For your convenience, we have made a makecode extension library for this smart
home kit.

**Add smart home extension library:**

Please follow the following steps to add extension files:

Open Makecode to enter a certain project→click the gear-shaped icon(for setting)
in the upper right corner→choose “Extensions”;

![Untitled](media/image/9bee14f94789507ec63f56c322c8ad88.png)

Or click”Advanced”to select “Extensions”as shown below:

![](media/image/b78a1ba52cf7d70976961bbf12e846ba.png)

Input the link <https://github.com/keyestudio2019/ks_IoT> to search;

Tap the searching result “IoT_keyestudio” to download and install it;

This process may take a few seconds.

![](media/image/ece90bfd9eb4023e7004dfba4abca5ae.png)

After the installation, you can find the extension files DHT11/DHT22 and
I2C_LCD1602 on the left side.

And extension file Neopixel is also installed.

![](media/image/0d4d6d7e47085561894a8beb35312f65.png)

![](media/image/72ec32002774ab76c5d2f2c98cc8cabd.png)

![](media/image/fbf4a61770a2950b5857e17afd88b2e9.png)

Note: the extension files added are only available for this project. Therefore,
when you create a new **IoT_keyestudio** project, you will need to add these
extension files again.

**Update or delete the IoT_keyestudio extension files:**

Please follow the following steps to update or delete extension files:

Click "Js JavaScript" to change to textual version:

![](media/image/9d00388b4e88a55f44d36f0d46d2d20d.png)

Click the “Explorer”on the left side:

![](media/image/a061d1ac034c0767eb5037c9c5f2c8e9.png)

You can find these added files in the list;

Click the dustbin icon beside the file to delete the corresponding file;

Tap the refresh icon to update the corresponding IoT_keyestudio extension file.

![](media/image/818a03c369319240dc38e23af5c21ec2.png)

### 4.Resources and test code

We also provide a link：https://fs.keyestudio.com/KS4027-4028

containing the information of the product from relevant tools to test codes,
tutorials and troubleshooting methods as well, as shown in the figure below:

![](media/image/f7cc0f0ff37a6267dce479048ae6c655.png)

### 5.Input test code

We provide hexadecimal code files (project files) for each project. The file
contains all the contents of the project and can be imported directly, or you
can manually drag the code blocks to complete the program for each project. For
simple projects, dragging a block of code to complete the program is
recommended.For complex projects, it is recommended to conduct the program by
importing the hexadecimal code file we provide.

Let's take the "Heatbeat" project as an example to show how to load the code.

Open the Web version of Makecode or the Windows 10 App version of Makecode;

![](media/image/40e8e36d4a7e9b8a726ff1a832393df5.png)

Click“Import File”;

![](media/image/3358909f898dd9898923f72945613851.png)

![](media/image/ff66d0d78d170913676e361a62078faf.png)

Select“../Makecode Code/Project 1\_ Heart beat/Project 1\_ Heart beat.hex”

Then click “Go ahead”.

![](media/image/c919527e842cb6dd603a03b8f850a7f8.png)

![](media/image/b5f985386359a415c102d3deefecce53.png)

In addition to importing the test code file provided into the Makecode compiler
above, you can also drag the the test code file provided into the code editing
area of the Makecode compiler, as shown in the figure below:

![dsBuffer.bmp](media/image/115cceaf5de0eb4f2079ca09681dbb7c.png)

After a few seconds, it is done.

![](media/image/a451132713cbd16f3f7957c5312673ba.png)

Note: if your computer system is Windows7 or 8 instead of Windows 10, the
pairing cannot be done via Google Chrome. Therefore, digital signal or analog
signal of sensors and modules cannot be shown on the serial port simulator.
However, you need to read the corresponding digital signal or analog signal.So
what can we do? You can use the CoolTerm software to read the serial port data
of the microbit. Next chapter is about how to install CoolTerm.

### 6. Install CoolTerm：

CoolTerm program is used to read the data on serial port.

Download CoolTerm program:

<https://freeware.the-meiers.org/>

After the download, we need to install CoolTerm program file, below is PC Window
system taken as an example.

1.  Choose“win”to download the zip file of CoolTerm

2.  Unzip file and open it. (also suitable for Mac and Linux system)

![](media/image/97f831d38df9ee01dcfedac244bfe281.png)

![IMG_256](media/image/e77548d01727e523e9e8c900d2fa962d.png)

1.  Double-click![](media/image/5f29eed25fc16602cfc0716f047c2da1.png).（please make
    sure that the driver of Micro:bit is installed and the main board is
    connected with the computer.)

![](media/image/74fd81c83f0c0a26b4e299b93ce4ede4.png)

The functions of each button on the Toolbar are listed below:
<http://wiki.keyestudio.com/index.php/File:IDE.png>

![](media/image/70bebd79d7cd20336ae394c916500a28.png)

| ![](media/image/2b728375ed2b8cd288c884e553418001.png)        | Open up a new Terminal                           |
|--------------------------------------------------------|--------------------------------------------------|
| ![](media/image/5f972f2eac5050ca0107416b2be067c2.png)        | Open a saved Connection                          |
| ![](media/image/be6f8b560e0afc447f9c32b4474f633f.png)        |  Save the current Connection to disk             |
| ![IMG_256](media/image/52257d028694a313fc4eea4d9c2469d7.png) | Open the Serial Connection                       |
| ![IMG_256](media/image/6ad366842b18084553a142ab82a613cf.png) | Close the Serial Connection                      |
| ![IMG_256](media/image/8fa3ac342549d33b6c9aa5a9e4688bea.png) | Clear the Received Data                          |
| ![IMG_256](media/image/c8d1dd8c3356b4938e143de1022e5842.png) | Open the Connection Options Dialog               |
| ![IMG_256](media/image/36e13c266fd4b9723d9db40fe30cd203.png) | Display the Terminal Data in Hexadecimal Format  |
| ![](media/image/b505c71c3344036730b1d67f0c62a354.png)        | Display the Help Window                          |



## On Board project

### Project 1: Heartbeat

![](media/image/8c3f540a07aab97e1608ba8770837f7b.png)

**(1)Project Introduction**

This project is easy to conduct with a micro:bit main board, a Micro USB cable
and a computer. The micro:bit LED dot matrix will display a relatively big
heart-shaped pattern and then a smaller one. This alternative change of this
pattern is like heart beating. This experiment serves as a starter for your
entry to the programming world.

**(2)Components Needed:**

| ![6(1)](media/image/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/image/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the USB cable.

![5(1)](media/image/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Path                                                                             | File Name                 |
|-----------|----------------------------------------------------------------------------------|---------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 1：Heart beat | Project 1：Heart beat.hex |

You can also drag blocks to form code. No need to worry though you are not good
at programming.

Firstly, you can view this link
[https://makecode.micro:bit.org/reference](https://makecode.microbit.org/reference)
to find more information about micro: bit blocks. Then this link
[https://makecode.micro:bit.org/](https://makecode.microbit.org/) can help you
write code.

**Command blocks can be found on the right:**

![](media/image/ac78c9efa592693d1a0d6a3f06873e8c.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_McR9J96FJHfK" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>



Click the arrow behind“JS JavaScript”to select between“JavaScript”and “Python”to
show the code in JavaScript language or Python language:

![](media/image/00e2115f7e171c91af90f27889395dde.png)

![](media/image/a938b288e7e24846aac80d6890a7c9a0.png)

**(5)Test Results:**

After uploading test code to micro:bit main board and keeping the connection
with the computer to power the main board, the LED dot matrix shows
pattern“![](media/image/f496ba08ff8af3164cdbd5fc56cc5abb.png)”and
then“![](media/image/04fdfc9060943954e7938bb1a741d626.png)”alternatively.

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_cwW1ofMtYgcD" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

( Please refer to chapter 5.3 to know how to download test code quickly.)

If the downloading is not smooth, please remove the USB cable from the main
board and then reconnect them and reopen Makecode to try again.

### Project 2: Light A Single LED

![](media/image/8c3f540a07aab97e1608ba8770837f7b.png)

**(1)Project Introduction**

In this project, we intend to control a certain LED of the micro:bit main board
to shine.

**(2)Components Needed:**

| ![6(1)](media/image/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/image/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the USB cable.

![5(1)](media/image/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Introduction of components:**

The LED dot matrix consists of 25 LEDs arranged in a 5 by 5 square. In order to
locate these LEDs quickly, as the figure shown below, we can regarded this
matrix as a coordinate system and create two aces by marking those in rows from
0 to 4 from top to bottom, and the ones in columns from 0 to 4 from the left to
the right. Therefore, the LED sat in the second of the first line is (1,0）and
the LED positioned in the fifth of the fourth column is (3,4）and others
likewise.

![](media/image/fe710eb3e622ac0e3544576acce9f03f.png)

**(5)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                    | File Name                         |
|-----------|------------------------------------------------------------------------------------------|-----------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 2：Light A Single LED | Project 2：Light A Single LED.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/65344f5c09b6100e39bd5c3749ea7c23.png)
![](media/image/aeb54a37d5588a71cac95a25fde1ff4a.png)

![](media/image/fe86356d61cade8641f76f9db5e8e7f0.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_HyKUHPcor5jj" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>


**(6)Test Result**

After uploading test code to micro:bit main board and powering the main board
via the USB cable, the LED in (1,0) lights up for 1s and the one in (3,4) shines
for 1s and repeat this sequence.
<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_HyKUHPcor5jj" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

### Project 3: LED Dot Matrix

![](media/image/8c3f540a07aab97e1608ba8770837f7b.png)

**(1)Project Introduction**

Dot matrices are very commonplace in daily life. They have found wide
applications in LED advertisement screens, elevator floor display, bus stop
announcement and so on.

The LED dot matrix of Micro: Bit main board contains 25 LEDs in a grid.
Previously, we have succeeded in controlling a certain LED to light by
integrating its position value into the test code. Supported by the same theory,
we can turn on many LEDs at the same time to showcase patterns, digits and
characters.

What’s more, we can also click”show icon“ to choose the pattern we like to
display. Last but not the least, we can design patterns by ourselves as well.

**(2)Components Needed:**

| ![6(1)](media/image/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/image/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the Micro USB cable.

![5(1)](media/image/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                | File Name                     |
|-----------|--------------------------------------------------------------------------------------|-------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 3：LED Dot Matrix | Project 3：LED Dot Matrix.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/0d6882d9ef08e1cf56a8bd73c768d9c2.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_8rAT5T6tqdLp" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(5)Test Result:**

After uploading test code to micro:bit main board and powering the main board
via the USB cable, we find that the 5\*5 dot matrix start to show numbers
1,2,3,4 and 5, and then it alternatively shows a downward arrow
![](media/image/2d4524f650129197874d4d62985e47c6.png), word “Hello”, a heart pattern
![](media/image/9b18b2b8dfaa0533d8859d08ff12611e.png), an arrow pointing at northeast
![IMG_256](media/image/364f2e355d6c354155b2e6db80830a62.png), then at southeast
![](media/image/fb3ba009a20245ab6076e537159a229c.png), then at southwest
![](media/image/7ec21961398787ca5155f0648bbd82cc.png), and then at northwest
![](media/image/ced0bb410c8269205fe18554aa2c9926.png).
<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_8rAT5T6tqdLp" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>


### Project 4: Programmable Buttons

![](media/image/06be84fb11b1fd07cd0cbb392132b903.png)

**(1)Project Introduction**

Buttons can be used to control circuits. In an integrated circuit with a push
button, the circuit is connected when pressing the button and it is open the
other way around.

Micro: Bit main board boasts three push buttons, two are programmable
buttons(marked with A and B), and the one on the other side is a reset button.
By pressing the two programmable buttons can input three different signals. We
can press button A or B alone or press them together and the LED dot matrix
shows A,B and AB respectively. Let’s get started.

**(2)Components Needed:**

| ![6(1)](media/image/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/image/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the USB cable.

![5(1)](media/image/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Test Code 1:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                      | File Name             |
|-----------|--------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 4：Programmable Buttons | Project 4：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/692855e3fe76aab1d8f0d120de9568b6.png)
![](media/image/e8c25665bb483f21a1f6c721626dab35.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_JhjFgV87aFKt" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(5)Test Result 1:**

After uploading test code to micro:bit main board and powering the main board
via the USB cable, the 5\*5 LED dot matrix shows A if button A is pressed and
then released, B if button B pressed and released, and AB if button A and B
pressed together and then released.

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_JhjFgV87aFKt" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

**(6)Test Code 2:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                      | File Name             |
|-----------|--------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 4：Programmable Buttons | Project 4：Code-2.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/72ac10a0b5e013d094e2c4d7392ae352.png)
![](media/image/0770dd8923359e6ed7cc6610de93555c.png)

![](media/image/2d58c013226b989c07a5ecacf669f026.png)
![](media/image/edd6f8b1577835b623ebb72dbca83e62.png)

![](media/image/50f89239057ac521950b5f110647f443.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_iHo9RwCVgF8L" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(7)Test Result 2:**

After uploading test code to micro:bit main board and powering the main board
via the USB cable, when the button A is pressed, the LEDs turning red increase
while when the button B pressed, the LEDs turning red reduce.

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_iHo9RwCVgF8L" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

### Project 5: Temperature Detection

![](media/image/206c8ec1c3f11d2de8d0f42fdf5b6b47.png)

**(1)Project Introduction**

The Micro:bit main board is not equipped with a temperature sensor, but uses the
temperature sensor built into NFR52833 chip for temperature detection.
Therefore, the detected temperature is more closer to the temperature of the
chip, and there maybe deviation from the ambient temperature. The sensor can
detect temperature of external environment with the range of 40℃\~105℃.

**(2)Components Needed:**

| ![6(1)](media/image/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/image/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the USB cable.

![5(1)](media/image/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Test Code 1:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                       | File Name             |
|-----------|---------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 5：Temperature Detection | Project 5：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/28c0c3261e05e7d512858b49acf48988.png)
![](media/image/3070e71d489e1626b97cff9049c106db.png)

![](media/image/76c43e7cd320c9d19e60450c9a42c902.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_PhaihwHHt0uJ" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(5)Test Result 1：**

After uploading test code 1 to micro:bit main board, powering the main board via
the USB cable, and clicking“Show console Device”, the data of temperature shows
in the serial monitor page as shown below.

![](media/image/a4763cbc3f2ec740ccf244319118eb95.png)

When you touch the processor nNRF52833 on the board for a while, its temperature
will rise gradually and the CoolTerm serial monitor will show the change of
temperature in the current environment, as shown in the figures below :

![](media/image/c2b124723b6dc8ca80e3a6537e9365ba.png)

If you're running Windows 7 or 8 instead of Windows 10, via Google Chrome won't
be able to match devices. You'll need to use the CoolTerm serial monitor
software to read data.

You could open CoolTerm software, click Options, select SerialPort, set COM port
and put baud rate to 115200 (after testing, the baud rate of USB SerialPort
communication on Micro: Bit main board is 115200), click OK, and Connect. The
CoolTerm serial monitor shows the change of temperature in the current
environment, as shown in the figures below :

![无标题](media/image/b3a18bca1b2a7b5337470735e5a0c5aa.png)

![无标题](media/image/f78128c148de3862a3fe10d86f063e22.png)

![无标题](media/image/13238e98c31d620f4ffd7742dd71c78d.png)

![](media/image/43c0b63e21f6d5e701d603f5f38e530e.png)

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_PhaihwHHt0uJ" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

**(6)Test Code 2:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                       | File Name             |
|-----------|---------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 5: Temperature Detection | Project 5：Code-2.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/6f1dd442a876e18ba91c775d0b838635.png)
![](media/image/803d39cec781e323ec6c49aba7853846.png)

![](media/image/3070e71d489e1626b97cff9049c106db.png)
![](media/image/a74e2faccc9921d75270d6440f686fb8.png)

**The complete code is as follows：**

(Please note that the value 35 in the statement below can be changed according
to real situation.)

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_4sse5q5dYRKt" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

1.  **Test Result 2:**

After uploading the code 2 to the board, when the ambient temperature is less
than 35℃, the 5\*5 LED dot matrix shows
![](media/image/4b1765e12b413dc5d562f2a16d32392f.png). When the temperature is
equivalent to or greater than 35℃, the
pattern![](media/image/f2705fbc4886efcfaac96589ca255f66.png) appears.

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_4sse5q5dYRKt" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

### Project 6: Geomagnetic Sensor

![](media/image/24c31bb0174e2ac672203e5c36c6875e.png)

**(1)Project Introduction**

This project aims to explain the use of the Micro: bit geomagnetic sensor, which
can not only detect the strength of the geomagnetic field, but also be used as a
compass to find bearings. It is also an important part of the Attitude and
Heading Reference System (AHRS).

Micro: Bit main board uses LSM303AGR geomagnetic sensor, which supports four
modes namely 100 kHz,400 kHz,1 MHz and 3.4 MHz and the dynamic range of magnetic
field is ±50 gauss.

In the board, the magnetometer module is used in both magnetic detection and
compass. In this experiment, the compass will be introduced first, and then the
original data of the magnetometer will be checked.The main component of a common
compass is a magnetic needle, which can be rotated by the geomagnetic field and
point toward the geomagnetic North Pole (which is near the geographic South
Pole) to determine direction.

Attention: this geomagnetic sensor built in the board can help us determine
bearings by showing readings in the value from 0 to 360. And the system will ask
us to calibrate it the first time it is put into operation by rotating the
board.Please note that metal materials around may attenuate the accuracy of the
reading and calibration.

**(2)Components Needed:**

| ![6(1)](media/image/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/image/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the USB cable.

![5(1)](media/image/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Test Code 1:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                    | File Name             |
|-----------|------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 6：Geomagnetic Sensor | Project 6：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/f133f96ecbab58bbdf67524fdea8dd06.png)
![](media/image/bfcdd73df2de99f489b53a943e08debf.png)

![](media/image/444745d070942a94e096e4e14ce170a4.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_60K2yPEHJcW9" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

Note: it is imperative to calibrate the Micro:bit board for different
geomagnetic fields existing in different places. And the system will make an
automatic requirement if it is used for the first time.

**(5)Test Result1：**

After uploading Test Code 1 to micro:bit main board and powering the board via
the USB cable, and pressing the button A, the board asks us to calibrate compass
and the LED dot matrix shows “TILT TO FILL SCREEN”. Then enter the calibration
page. Rotate the board until all 25 red LEDs are on as shown below.

![1(5)](media/image/acf3b8c0dee027d9e555fc708831f874.jpeg)

After that, a smile pattern
![IMG_256](media/image/55ad39536dff7bdf66379a1da7a4c137.png) appears, which implies
the calibration is done. When the calibration process is completed, pressing the
button A will make the magnetometer reading display directly on the screen. And
the direction north, east, south and west correspond to 0°, 90°, 180° and 270°
respectively.

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_60K2yPEHJcW9" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

**(6)Test Code 2:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                        | File Name             |
|-----------|----------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Tutorial/Project Code/Project 6: Geomagnetic Sensor | Project 6：Code-2.hex |

![](media/image/66c4482e3bcd71e712a54f4d73044104.png)

This module can keep reading data to determine direction, so does point to the
current magnetic North Pole by arrow.

![](media/image/d1a4e9f62bdf690ba809ae35c347b233.png)

For the above picture, the arrow pointing to the upper right when the value
ranges from 292.5 to 337.5. Because 0.5 can’t be input in the code, the values
we get are 293 and 338.

Then add other statements to make a set of complete code.

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/3720a2ee4a14d8e93f1e75d3ce697ade.png)
![](media/image/c60e9564b3912849511d7550e307f25c.png)

![](media/image/107ea0e69966ae8a5e198dcf31cb2293.png)
![](media/image/7bdf6cce3ae0f91c75c420ab44c29c57.png)

![](media/image/283d5470c7a3ccd095f14fa8bdce526f.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_f6yUhHXP0cLW" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(7)Test Result 2:**

Upload code 2 and plug micro:bit into power. After calibration, tilt micro:bit
board, and the LED dot matrix displays the direction signs.

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_f6yUhHXP0cLW" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

### Project 7: Accelerometer

![](media/image/24c31bb0174e2ac672203e5c36c6875e.png)

**(1)Project Introduction**

The Micro: Bit main board V2 has a built-in LSM303AGR gravity acceleration
sensor, also known as accelerometer, with a resolution of 8/10/12 bits. The code
section sets the range to 1g, 2g, 4g, and 8g.

We often use accelerometer to detect the status of machines.

In this project, we will introduce how to measure the position of the board with
the accelerometer. And then have a look at the original three-axis data output
by the accelerometer.

**(2)Components Needed:**

| ![6(1)](media/image/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/image/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

![5(1)](media/image/18c70cf16dcf8c9694a1af8b12530cf9.png)Attach the Micro:bit main
board to your computer via the USB cable.

**(4)Test Code 1:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                | File Name             |
|-----------|--------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 7：Accelerometer  | Project 7：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/2213a02053bc1eb939854d28ddb9eaf0.png)
![](media/image/a2dada106cdd0c950024b884e3ad9102.png)
![](media/image/69ef2fc14c29ee8d8273ec04173fae17.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_b1kWbWTzEW3z" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(5)Test Result 1：**

After uploading the test code 1 to micro:bit main board and powering the board
via the USB cable, if we shake the Micro: Bit main board，no matter at any
direction, the LED dot matrix displays the digit “1”.

When it is kept upright （make its logo above the LED dot matrix）, the number 2
shows.

![\_DSC3687](media/image/1600323e3e61e331c248cbeda5ccdcfc.jpeg)

When it is kept upside down( make its logo below the LED dot matrix) , it shows
as below.

![\_DSC3688](media/image/3be80acf957e53117f695801ce19c449.jpeg)

When it is placed still on the desk, showing its front side, the number 4
appears.

![\_DSC3689](media/image/5797dd7be9a9c2d3226123e0c29db0bd.jpeg)

When it is placed still on the desk, showing its back side, the number 5
exhibits.

When the board is tilted to the left , the LED dot matrix shows the number 6 as
shown below.

![\_DSC3703](media/image/326095934bcff0a925b4f9a09d6cf7d2.jpeg)

When the board is tilted to the right , the LED dot matrix displays the number 7
as shown below：

![\_DSC3697](media/image/185b0ac204e9b2c54dd8fa93d852568c.jpeg)

When the board is knocked to the floor, this process can be considered as a free
fall and the LED dot matrix shows the number 8. (Please note that this test is
not recommended for it may damage the main board.)

Attention: if you’d like to try this function, you can also set the acceleration
to 3g, 6g or 8g. But still ,we do not recommend.

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_b1kWbWTzEW3z" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

1.  **Test Code 2：**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                               | File Name             |
|-----------|-------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 7：Accelerometer | Project 7：Code-2.hex |

You can edit command blocks yourself

**Command blocks:**

![](media/image/3edd89b699b2e9ac793d44cf6fb7a9dc.png)
![](media/image/e781d350b96f186440baeacf43947a2b.png)

![](media/image/47307ff96c1a312385facc77fe4914b7.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_073a5g1X2KPW" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(7)Test Result 2:**

Upload test code to micro:bit main board, power the main board via the USB
cable, and click “Show console Device”.

![](media/image/feb1d8c40c5ac88363223a162de2fa38.png)

After referring to the MMA8653FC data manual and the hardware schematic diagram
of the Micro: Bit main board, the accelerometer coordinate of the Micro: Bit are
shown in the figure below:

![10](media/image/6303a0ac122680207fe856d9be38d01c.png)

The following interface shows the decomposition value of acceleration in X axis,
Y axis and Z axis respectively, as well as acceleration synthesis (acceleration
synthesis of gravity and other external forces).

![](media/image/8bb6dd52d8d22db71f023bf5c811fd78.png)

If you're running Windows 7 or 8 instead of Windows 10, via Google Chrome won't
be able to match devices. You'll need to use the CoolTerm serial monitor
software to read data.

You could open CoolTerm software, click Options, select SerialPort, set COM port
and put baud rate to 115200 (after testing, the baud rate of USB SerialPort
communication on Micro: Bit main board is 115200), click OK, and Connect. The
CoolTerm serial monitor shows the data of X axis, Y axis and Z axis , as shown
in the figures below :

![](media/image/46d779cbd39f94325b5f68026486abed.png)

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_073a5g1X2KPW" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

### Project 8: Light Brightness Detection

**(1)Project Introduction**

In this project, we focus on the light detection function of the Micro: Bit main
board V2. It is achieved by the LED dot matrix. And it can be viewed as a
photosensor.

![](media/image/8c3f540a07aab97e1608ba8770837f7b.png)

**(2)Components Needed:**

| ![6(1)](media/image/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/image/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

![5(1)](media/image/18c70cf16dcf8c9694a1af8b12530cf9.png)

Attach the Micro:bit main board to your computer via the USB cable.

**(4)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                            | File Name                                 |
|-----------|--------------------------------------------------------------------------------------------------|-------------------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 8：Light Brightness Detection | Project 8：Light Brightness Detection.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/3edd89b699b2e9ac793d44cf6fb7a9dc.png)
![](media/image/6294d3f74a97be6bf4a6e6b81f9535f0.png)

![](media/image/938fc78372d2b979421ade80986a0eb1.png)
![](media/image/26bc469d89b7cc2fa98f0fd26bb496b1.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_a03EFyLCLVw3" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(5)Test Result:**

Upload the test code to micro:bit main board, power the board via the USB cable
and click“Show console Device”.

![](media/image/80362de124b0f33064382555326f6076.png)

When the LED dot matrix is covered by hand, the light intensity showed is
approximately 0; when the LED dot matrix is exposed to light,the light intensity
displayed gets stronger with the light as shown below:

![](media/image/043c01cc37a5eb6432d7975748509538.png)

The 20 in the code is an arbitrary value of light intensity. If the current
light level is less than or equal to 20, the icon moon will appear on the LED
dot matrix. If it's bigger than 20, the sun will appear.

If you're running Windows 7 or 8 instead of Windows 10, via Google Chrome won't
be able to match devices. You'll need to use the CoolTerm serial monitor
software to read data.

You could open CoolTerm software, click Options, select SerialPort, set COM port
and baud rate to 115200 (after testing, the baud rate of USB SerialPort
communication on Micro: Bit main board is 115200), click OK, and Connect. The
CoolTerm serial monitor shows the value of light intensity , as shown in the
figures below :

![](media/image/b7b8a5af7fd7e74320a402117821a6d5.png)

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_a03EFyLCLVw3" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

### Project 9: Speaker

![](media/image/ac515b9ae8891dc32f368a29f194a2fb.png)

**(1)Project Introduction**

Micro: Bit main board has an built-in speaker, which makes adding sound to the
programs easier. With a speaker, all Micro:bit board can be used to create
sound-related projects. But the new version, that’s the version 2 is able to
make the speaker utter giggles, greetings and yawning and sound sad. It can also
be programmed to air all kinds of tones, like playing the song *Ode to Joy.*

**(2)Components Needed:**

| ![6(1)](media/image/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/image/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the USB cable.

![5(1)](media/image/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Test Code 1:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                         | File Name             |
|-----------|-------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 9: Speaker | Project 9：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/80655aa9a6fd1d5466992df654c73cab.png)
![](media/image/336245f9fd75aaee9a08f505827f2cb5.png)

![](media/image/e6d293945d0591c3b1ae78fb2aec1eec.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_1c1byieb0gXF" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(5)Test Result 1:**

After uploading the Test Code 1 to micro:bit main board and powering the board
via the USB cable, the speaker utters sound and the LED dot matrix shows the
logo of music.

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_1c1byieb0gXF" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

**(6)Test Code 2:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                         | File Name             |
|-----------|-------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 9：Speaker | Project 9：Code-2.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/80655aa9a6fd1d5466992df654c73cab.png)
![](media/image/336245f9fd75aaee9a08f505827f2cb5.png)

![](media/image/b781245f8f0b1d52e201cbbb339ad4c5.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_PreEdw2LkXv4" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

The musical score of *Ode to Joy* is attached below:

![乐谱](media/image/4a79470cc28f087a3834d168bc0c343f.jpeg)

Find more information about musical notations via this link:

https://en.wikipedia.org/wiki/Numbered_musical_notation

**(7) Test Result 2:**

After uploading the Test Code 2 to micro:bit main board and powering the board
via the USB cable, the speaker on built-in the Micro:bit board plays the sound
*Ode to Joy .*

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_PreEdw2LkXv4" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

### Project 10: Touch-sensitive Logo

![](media/image/644695850097c5ade080bb4848b4b481.png)

**(1)Project Introduction**

The Micro: Bit main board is equipped with a golden touch-sensitive logo, which
can act as an input component and function like an extra button.

It contains a capacitive touch sensor that senses small changes in the electric
field when pressed (or touched), just like your phone or tablet screen do.When
you press it , you can activate the program.

**(2)Components Needed:**

| ![6(1)](media/image/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/image/81bfee2741c94f7e5cb7f8ec66b83945.jpeg)  |
|-----------------------------------------------------|-----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                        |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the USB cable.

![5(1)](media/image/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                       | File Name                            |
|-----------|---------------------------------------------------------------------------------------------|--------------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 10：Touch-sensitive Logo | Project 10：Touch-sensitive Logo.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/5eac17c2b2297d4d58c631a40aa6e5d6.png)
![](media/image/00044636e4f1edb842c33ecdf952333c.png)

![](media/image/dc330b1d211f5066b4f8ecbd6e5180bb.png)
![](media/image/0b29fe8b7226b0fcdcd14a6490632c83.png)![](media/image/22ce4b96ea8e01f6bb6301585b474f8e.png)

![](media/image/018f9772fe5e038a93022fd625377522.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_4WU6uuDVaUVJ" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(5)Test Results:**

After uploading the test code to micro:bit main board and powering the board via
the USB cable, the LED dot matrix exhibits the heart pattern when the
touch-sensitive logo is pressed or touched and displays digit when the logo is
released. The longer it is pressed, the bigger the number is when it is
released.

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_4WU6uuDVaUVJ" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

### Project 11: Microphone

![](media/image/3073a8af772ab91ecf264843b37d3b74.png)![](media/image/7f0741158e734ff8449d5b87d5ba85f4.png)

**(1)Project Introduction**

The Micro: Bit main board is built with a microphone which can test the volume
of ambient environment. When you clap, the microphone LED indicator turns on.
Since it can measure the intensity of sound, you can make a noise scale or disco
lighting changing with music. The microphone is placed on the opposite side of
the microphone LED indicator and in proximity with holes that lets sound
pass.When the board detects sound, the LED indicator lights up.

**(2)Components Needed:**

| ![6(1)](media/image/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/image/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the USB cable.

**![5(1)](media/image/18c70cf16dcf8c9694a1af8b12530cf9.png)**

**(4)Test Code 1:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                             | File Name              |
|-----------|-----------------------------------------------------------------------------------|------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 11：Microphone | Project 11：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/64fb7ef7474f8bf6dfb4b4a3f70f7468.png)
![](media/image/d5fa6362f08016b3a171a33197515c7f.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_ixHczAWsa1Ks" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(5)Test Result 1:**

After uploading test code to micro:bit main board and powering the board via the
USB cable, the LED dot matrix displays
pattern“![](media/image/f496ba08ff8af3164cdbd5fc56cc5abb.png)”when you clap and
pattern ![](media/image/04fdfc9060943954e7938bb1a741d626.png) when it is quiet around.

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_ixHczAWsa1Ks" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

**(6)Test Code 2:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                             | File Name              |
|-----------|-----------------------------------------------------------------------------------|------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 11: Microphone | Project 11: Code-2.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/c22cc01fb824faed553d82eb66ee4632.png)
![](media/image/6645b09fcf339557aecdd4baea422c5c.png)

![](media/image/681bbd89228d414999f3afee128b14a0.png)
![](media/image/58a3639dfce22fa6246f8ab791a5203c.png)

![](media/image/22961dbf753ba383da060507e542a083.png)
![](media/image/b20a86aa98579aa973d44ee44c26379e.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_TFf2UvEadgq4" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(2)Test Result 2:**

Upload test code to micro:bit main board, power the board via the USB cable and
click “Show console Device”as shown below:

![](media/image/e22507af4953df977269bbdb2463d69e.png)

When the sound is louder around, the sound value shows in the serial port is
bigger as shown below:

![](media/image/50b81518d9f7925b0c20476ab1f64185.png)

What’s more, when the button A is pressed, the LED dot matrix displays the value
of the biggest volume( please note that the biggest volume can be reset via the
Reset button on the other side of the board ) while when clapping, the LED dot
matrix shows the pattern of the sound.

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_TFf2UvEadgq4" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

### Project 12: Play Music

**(1)Project Introduction**

In the previous projects, we have learned about the touch-sensitive logo and the
speaker respectively. In the project, we will combine these two components to
play music. That’s the logo will be applied to control the speaker to sing
songs.

**(2) Components Needed:**

| ![6(1)](media/image/b5a90ee5338cd7fb96e135fe71a79a61.png) | ![3](media/image/81bfee2741c94f7e5cb7f8ec66b83945.jpeg)   |
|-----------------------------------------------------|-----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                        |

**(3)Connection Diagram:**

![5(1)](media/image/18c70cf16dcf8c9694a1af8b12530cf9.png)Attach the Micro:bit main
board to your computer via the USB cable.

**(4)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                             | File Name                  |
|-----------|-----------------------------------------------------------------------------------|----------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 12: Play Music | Project 12：Play Music.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/f31bfc90ab7c4f5be17716ff6572bf16.png)![](media/image/08c9693968eccf0853632d80fb68bda6.png)

![IMG_256](media/image/7f761aee65bce7f67dd9d7b98ac9ac81.png)![](media/image/336245f9fd75aaee9a08f505827f2cb5.png)

![](media/image/c3d265154ac1b454efa270f1f87caf1c.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_3VwPAe57Wdz4" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(5)Test Results:**

After uploading test code to micro:bit main board and powering the board via the
USB cable, the speaker plays the song *Happy Birthday to You* when the logo is
touched.

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_3VwPAe57Wdz4" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

### Project 13: Dodge Bullets

**(1)Project Introduction**

In the previous projects, we have learned about the two programmable buttons,
button A and B, and the LED dot matrix respectively. In this one, we will
combine them to design a game- Dodge Bullets.

**(2)Components Needed:**

| ![6(1)](media/image/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/image/81bfee2741c94f7e5cb7f8ec66b83945.jpeg)  |
|-----------------------------------------------------|-----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                        |

**(3)Connection Diagram:**

![5(1)](media/image/18c70cf16dcf8c9694a1af8b12530cf9.png)Attach the Micro:bit main
board to your computer via the USB cable.

**(4)Game Rule1**

There are two bullets (marked as G1 and G2)falling from the LED dot matrix and a
role G on the bottom of the matrix. Button A and B can be used to control the
movement of the role to dodge bullets. It moves to the right when A is pressed
and to the left when B is pressed. The game is over when G is hit and the game
can start over by pressing A and B together.

**(5)Test Code 1:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                | File Name              |
|-----------|--------------------------------------------------------------------------------------|------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 13：Dodge Bullets | Project 13：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/59f4a7a5220320ed53862131eb0bdee0.png)
![](media/image/b0da291750cd328652b24fc3aa2a46b1.png)

![](media/image/bcb120fbe26807b6437652050543a15c.png)![](media/image/edfc0dcea9d7f0da349385478f6d8c62.png)

![](media/image/22f1deba1162a4438bd8459fb17873cf.png)
![](media/image/3d5d2e066df5919772690a5c1d74affa.png)

![](media/image/9d82e6fb0df19d56e196efd524fbb24b.png)
![](media/image/7f2ed2cbf5ce8b76b4d1940e068a3151.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_c7YC93J7rfDU" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

1.  **Test Result 1:**

The game begins when the code is uploaded to the main board. The bullets G1 and
G2 fall off and the role G is controlled by Button A and B to shun them. If the
role fail to avert the attacks, the game is over.

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_c7YC93J7rfDU" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

**(7)Game Rule 2:**

Built on the rule1, a new rule is added that one will get score in this game.
And with the accumulation of the score, the difficulty of this game mounts. The
detail of rule2 is that when the role G dodge a bullet, 1 score is gained and
that the game stops when it is hit and the game is over after the display of the
scores. Like rule1, the game will restart when button A and B pressed together.

**(8)Test Code 2:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                | File Name              |
|-----------|--------------------------------------------------------------------------------------|------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 13：Dodge Bullets | Project 13：Code-2.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/040845a1bf151447a4b4d57c219aa5a0.png)
![](media/image/602f887f942574b02a6d4f125a66ccaf.png)

![](media/image/471db99b4e224c956cb0e09d15c03781.png)
![](media/image/0bf268056da8347f78d1eb9a8943cac4.png)

![](media/image/a293e3fdfa0ef1ef7603ffbe0af3f5d4.png)![](media/image/22f1deba1162a4438bd8459fb17873cf.png)

![](media/image/3d5d2e066df5919772690a5c1d74affa.png)
![](media/image/e279f6a1e3685f63383a36b22b7facb2.png)

![](media/image/9d82e6fb0df19d56e196efd524fbb24b.png)
![](media/image/7f2ed2cbf5ce8b76b4d1940e068a3151.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_d4rJ1ff1DXmW" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(9)Test Result 2:**

The game begins when the code is uploaded to the main board. The bullets G1 and
G2 fall off and the role G is controlled by Button A and B to shun them. 1 score
will be tallied for each successful dodging. If the role fail to avert the
attacks, the game halts and it is over after the exhibition of the scores
gained.

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_d4rJ1ff1DXmW" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

### Project 14: Bluetooth Wireless Communication

![](media/image/55b2424d88ba1ba8a711c49418ca8dc6.png)

**(1)Project Introduction**

The Micro: Bit main board comes with a nRF52833 processor (with a built-in
BLE(Bluetooth Low Energy) device Bluetooth 5.1 ) and a 2.4GHz antenna for
Bluetooth wireless communication and 2.4GHz wireless communication. With the
help of them, the board is able to communicate with a variety of Bluetooth
devices, including smart phones and tablets.

In this project, we mainly concentrate on the Bluetooth wireless communication
function of this main board. Linked with Bluetooth, it can transmit code or
signals. To this end, we should connect an Apple device (a phone or an iPad) to
the board.

Since setting up Android phones to achieve wireless transmission is similar to
that of Apple devices, no need to illustrate again.

**(2)Components Needed:**

| ![6(1)](media/image/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/image/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) | ![](media/image/41abce34fdbca029fdea842bba8208c0.png)![12](media/image/989d26695fd03ea630b7fdf186ff78c1.png) |
|-----------------------------------------------------|----------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Micro:bit main board \*1                            | Micro USB cable\*1                                 | Smart Phone/iPad\*1                                                                              |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the Micro USB cable.。

![5(1)](media/image/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Procedures:**

**Step 1:**

For Apple devices, enter this link
<https://www.microbit.org/get-started/user-guide/ble-ios/> with your computer
first, and then click **“Download pairing HEX file”**to download the Micro: Bit
firmware to a folder or desk, and upload the downloaded firmware to the Micro:
Bit main board.

(Only Apple devices should follow this step. Not needed for Android systems.)

![](media/image/cfaf7f8ae83cbe2636c39162a78adc7f.png)

![图片11](media/image/6c1cef08d31fe3c4876b90ecc11554ff.jpeg)

![Untitled](media/image/63f1faf124af4949b31d7a84cee19a92.png)

**Step 2:**

Search “micro bit”in your App Store to download the APP micro:bit.

![](media/image/66d1f34d8d4c52e2b7c0ce10e602a063.png)

**Step 3:** Connect your Apple device with Micro: Bit main board :

Firstly, turn on the Bluetooth of your Apple device and click icon
![](media/image/ddfd27bdd24da96eb998ccc2e13fcf72.png) to open the APP micro:bit and
select item “Choose micro:bit”to start pairing Bluetooth.

![](media/image/34f5fbb1c0c371970d1aec6c59c5cbb5.png)

Secondly, click“Pair a new micro:bit”;

![](media/image/e20270a0ade9c00b61198b26fc2fd83b.png)

Following the instructions to press button A and B at the same time(do not
release them until you are told to) and press Reset & Power button for a few
seconds.

Release the Reset & Power button, you will see a password pattern shows on the
LED dot matrix. Now , release buttons A and B and click “Next”.

![](media/image/c00520400ecd1f20f958c1c6d1a3c907.png)

![](media/image/cabc60d7f8a030f5c9d86ac7de6c7bd7.png)

Set the password pattern on your Apple device as the same pattern showed on the
matrix and click “Next”.

![](media/image/9411a5280e6f3b0d45306a31f80c1b38.png)

Still click “Next”and a dialog box props up as shown below. Then click "Pair". A
few seconds later, the match is done and the LED dot matrix displays the "√"
pattern.

![](media/image/7b56c56e10415ac2881ac69448b4ad3c.png)![](media/image/803cb5cf5f7d595581a11f5e6b7e61ed.png)![](media/image/dc570950dd81f427edb5ea58f50b3a7e.png)![](media/image/f72e83dc6276d520e82c349659106e1a.png)

After the match with Bluetooth, write and upload code with the App.

Click “Create Code” to enter the programming page and write code.

Click ![](media/image/f3e9cc7884f7bba807fa4633c429422b.png) and the box
![](media/image/e081360be7c91b7a156b01a787e4a58c.png) appears, and then select “Create
√”.

![](media/image/d54bf2d1c01cd3c18544009b1f9dc5a0.png)

![](media/image/4e7a5d06a5f9a5a209ef5fbc005e9f62.png)

![](media/image/5bd84e8d293bf8c0c999c7f4e756cf30.png)

![](media/image/bd19bb4c97ad2a5bc300412b8eb93ede.png)

Name the project as “1 “and click
![](media/image/a32c2d832ab38d19eb623108143c744e.png) to save it.

![](media/image/25cf76f891c5eac7381b8095363a2748.png)

Click the third item“Flash”to enter the uploading page. The default code program
for uploading is the one saved just now and named "1" and then click the other
"Flash" to upload the code program "1".

![](media/image/c1661720ea2eaa521ff31a778501eb23.png)

![](media/image/350abcbb09d431d40427f34c3764f2eb.png)

![](media/image/4863bf826f119805a6a9bf9c12d5ec81.png)

If the program “1”is uploaded successfully a few seconds later, the App will
emerge as below and the LED dot matrix of the Micro: Bit main board will exhibit
a heart pattern.

![](media/image/ebfd31347a0553de0be4e01636652a15.png)

## Expansion Projects

The former 14 projects are the introduction of sensors and modules. The further
lessons are challenging for new starters.

Note: (G), marked on each sensor and module, is the negative pole and connected
to “G”, ”-”or “GND”on the sensor shield or control board ; (V) is the positive
pole and linked with V , VCC, + or 5V on the sensor shield or control board. And
you need to connect a power in case that power supply is weak.

### Project 1：LED Blinks

![13](media/image/98c9efc46d004ad501e0fe56f826a69c.png)

**(1)Project Introduction**

We’ve set up the micro:bit smart home. Now let’s get started from the most
simple experiment---LED blink.

LED is a type of semiconductor called "Light Emitting Diode "which is an
electronic device made of semiconductor materials (silicon, selenium, germanium,
etc.). It features unidirectional conductivity, that is, the positive voltage is
applied to the anode (long leg) and the cathode (short leg) of the diode. when
the voltage of its anode is higher than the voltage of its cathode, thus, the
diode is turned on(LED is on). When a reverse voltage is applied to the anode
and cathode, the diode is disconnected(that is, the LED is off). Therefore, the
disconnection and connection of the diode is equivalent to turning on and off
LED. Light-emitting diodes have an anode (+) and a cathode (-), and they can
only allow current to flow from one anode to the cathode. The components will be
damaged if LED is directly connected to the power supply. It’s essential that a
certain resistor must be connected in series in the LED circuit.

**(2)Yellow LED：**

| Working Voltage:    | DC 3.3-5V                      | ![](media/image/98a79cea0b6dae9d2b47785668ed2f9b.png) |
|---------------------|--------------------------------|-------------------------------------------------|
| Working current：   | \< 20mA                        |                                                 |
| Max Power：         | 0.1W                           |                                                 |
| Control Ports:      | Digital ports (digital input） |                                                 |
| Working Temperature | -10°C \~ +50°C                 |                                                 |
| Display Color：     | Yellow                         |                                                 |

**(3)Test Code**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| Type     | Route                                                                                  | File Name                 |
|----------|----------------------------------------------------------------------------------------|---------------------------|
| Hex file | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 1: LED Blinks | Project 1：LED Blinks.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/4c5f40ff2175d79937ce5a4be8a6bfcc.png)![](media/image/55a0e6575e1b39ca361f34b28a5984a8.png)

![](media/image/3647995145391436b5772ebf2baa9809.png)

**The complete code is as follows：**

| Micro：bit Shield | Yellow LED Module |
|-------------------|-------------------|
| GND               | G                 |
| 5V                | V                 |
| S（16）           | S                 |

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_57sfEc2YDRUM" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(4)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch.

The micro:bit will show smile expression，and a yellow LED will flash with an
interval of 1000ms. ([How to download?](#A01) [How to quick
download?](#_7.3.快速下载))

### Project 2：Breathing LED

![13](media/image/98c9efc46d004ad501e0fe56f826a69c.png)

**(1)Project Introduction**

In previous lesson, we control LED on and off and make it blink.

In this project, we will control LED’s brightness through PWM simulating
breathing effect. Similarly, you can change the step length and delay time in
the code so as to demonstrate different breathing effects.

PWM is a means of controlling the analog output via digital means. Digital
control is used to generate square waves with different duty cycles (a signal
that constantly switches between high and low levels) to control the analog
output.In general, the input voltages of ports are 0V and 3V. What if the 1.5V
is required? Or a switch among 1V, 1.5V and 3V? We cannot change resistors
constantly. For this reason, we resort to PWM.

For Micro:bit digital port voltage outputs, there are only LOW and HIGH levels,
which correspond to the voltage outputs of 0V and 3V respectively. You can
define LOW as“0”and HIGH as“ 1’, and let Micro:bit output five
hundred“0”or‘1’within 1 second. If output five hundred‘1”, that is 3V; if all of
which is‘0’,that is 0V; if output 250 01 pattern, that is 1.5V.

This process can be likened to showing a movie. The movie we watch are not
completely continuous. Actually, it generates 25 pictures per second, which
cannot be told by human eyes. Therefore, we mistake it as a continuous process.
PWM works in the same way. To output different voltages, we need to control the
ratio of 0 and 1. The more‘0’or ‘1’ output per unit time, the more accurate the
control.

In the graphic below, the green lines represent a regular time period. This
duration or period is the inverse of the PWM frequency. In other words, with
Micro:bit's PWM frequency at about 500Hz, the green lines would measure 2
milliseconds each. A call to analogWrite() is on a scale of 0-255, such that
analogWrite(255) requests a 100% duty cycle (always on), and analogWrite(127) is
a 50% duty cycle (on half the time).

![图1](media/image/704984700612966b997127cb9bde5c96.jpeg)

PWM is applied to light brightness adjustment, speed adjustment of motor and
sound emitting.

Parameters of PWM：

![IMG_256](media/image/b14db369936f55eef1dd18b050682a10.png)

pulse width (minimum / max)

Pulse cycle (insertion of pulse frequency within 1 second)

Voltage level（0V-3V）

There are commonly used PWM ports, namely P0, P1, P2, P3, P4 and P10. And there
are other rarely used ports, namely P5, P6, P7, P8, P9, P11, P12, P13, P14, P15,
P16, P19 and P20.

In the experiment, we connect the port S of yellow LED Module to the port S (16)
of the expansion board. And P16 can also be used as a PWM interface.

**(2)Yellow LED：**

| Working Voltage:      | DC 3.3-5V                     | ![](media/image/98a79cea0b6dae9d2b47785668ed2f9b.png) |
|-----------------------|-------------------------------|-------------------------------------------------|
| Working Current：     | \< 20mA                       |                                                 |
| Max Power：           | 0.1W                          |                                                 |
| Control Port:         | digital port (digital input） |                                                 |
| Working Temperature： | -10°C \~ +50°C                |                                                 |
| Display Color：       | Yellow                        |                                                 |

**(3) Test Code**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| Type     | Route                                                                                     | File Name                    |
|----------|-------------------------------------------------------------------------------------------|------------------------------|
| Hex file | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 2: Breathing LED | Project 2：Breathing LED.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/4c5f40ff2175d79937ce5a4be8a6bfcc.png)
![](media/image/55a0e6575e1b39ca361f34b28a5984a8.png)

![](media/image/3647995145391436b5772ebf2baa9809.png)
![](media/image/8c16a69b75ac41d59c7d9543133d0186.png)

![](media/image/20ef92f127236d4f1c7a773ca86d4e45.png)

**The complete code is as follows：**

| Micro:bit Expansion Board | Yellow LED Module |
|---------------------------|-------------------|
| GND                       | G                 |
| 5V                        | V                 |
| S（16）                   | S                 |

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_YLuJcR0hVJ3e" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(4)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch.

The micro:bit will show a smile expression, and LED smoothly changes its
brightness from light to dark and back to light, continuing to do so, which is
similar to a lung breathing in and out.

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

### Project 3：6812 2x2 Full Color RGB

![16](media/image/cdebaf0805f0e933e1ccfb3691258bc7.png)

**(1)Project Introduction**

6812 2X2 full-color RGB module integrates the controlling circuit and the
illuminating circuit. Each LED is the same as a 5050 LED lamp bead, and each
component is a pixel point. The inner pixel point includes a amplify driving
circuit that latch signal from digital ports shapes, a high-precision internal
oscillator and and a 12V high voltage programmable current control portion,
which effectively ensures that the color of the pixel point.

The data protocol uses a single-line zero code communication method. After the
pixel point is reset, the S-terminal receives the data transmitted from the
controller. First, the 24bit data sent by the first pixel is extracted by the
first pixel point, and sent to the internal portion of the pixel point.

It has the advantages of low-voltage driving, environmental protection, high
brightness, large scattering angle, good consistency, ultra-low power, long life
expectancy.

**(2)6812 2x2 Full-color RGB:**

| Working Voltage：                               | DC 3.3-5V  | Max Working Current： | 200mA        | Max Power:          | 1W                                |
|-------------------------------------------------|------------|-----------------------|--------------|---------------------|-----------------------------------|
| Working Temperature：                           | -10℃\~+50℃ | Source of light：     | SMD 5050 RGB | IC Type：           | 4 pcs/WS2811                      |
| Gray Scale：                                    | 256        | Illuminating Angle：  | 180°         | Illuminating Color: | Red, yellow, blue,green and white |
| ![](media/image/29efaf32be2cfacb8d2f8f3438772236.png) |            |                       |              |                     |                                   |

**(3)Add NeoPixel Library:**

Set code by the library, and click“Extensions”to add the library file.

![](media/image/792e3ec83c270dffdae7758a0721600d.png)

Click the neoPixel library, then NeoPixel library is installed.

![](media/image/dd2a1e4d4b71fbdc7f400286c7694870.png)

You can view it in the blocks list.

![](media/image/0912defee95f32e352a21e481b836efb.png)

**(4)Test Code 1**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                             | File Name             |
|-----------|---------------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 3: 6812 2x2Full-colorRGB | Project 3：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/f662876dc93548199e1d84d3e6c97076.png)
![](media/image/5f10026b74fe5cbcf58c8c1606618ea1.png)

**The complete code is as follows：**

| Micro:bit Expansion Board | 6812 2x2 Full Color  RGB Module |
|---------------------------|---------------------------------|
| GND                       | G                               |
| 5V                        | V                               |
| S（14）                   | S                               |

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_Jq8dMRemsRq5" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(5)Test Result 1:**

Upload the Test Code 1to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch. You will view the 6812 RGB module display red,
orange,yellow, green, blue,Indigo, violet, purple and white, in loop way. ([How
to download?](#A01) [How to quick download?](#_7.3.快速下载))

**(6)Test Code 2:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                             | File Name             |
|-----------|---------------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 3：6812 2x2Full-colorRGB | Project 3：Code-2.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/f662876dc93548199e1d84d3e6c97076.png)
![](media/image/8c16a69b75ac41d59c7d9543133d0186.png)

![](media/image/d1e2527365d23875a0e99774a4a58287.png)

![](media/image/e91267f0c5222aac0a9199908a7fba3d.png)
![](media/image/20ef92f127236d4f1c7a773ca86d4e45.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_902U7r43fF0a" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**7.5. Test Result2:**

Upload the test code 2 to the micro:bit，plug in power, dial the DIP switch to
ON and press“1”on the rocket switch.

You can view four WS2812RGB lights light up，like a flowing light.

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

**(8)Test Code 3:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                             | File Name             |
|-----------|---------------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 3: 6812 2x2Full-colorRGB | Project 3：Code-3.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/f662876dc93548199e1d84d3e6c97076.png)
![](media/image/8c16a69b75ac41d59c7d9543133d0186.png)

![](media/image/d1e2527365d23875a0e99774a4a58287.png)![](media/image/b925689ddad7baf1cc48eb47ad00f57a.png)

![](media/image/c14853e5ed880dba471fcabf672caa69.png)
![](media/image/7ba31169ee48cebb69bda5e89ae4b7f0.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_9r8Y0cJ8fixM" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

Upload the test code 3 to the micro:bit，plug in power, dial the DIP switch to
ON and press“1”on the rocket switch.

Then you will see 5 WS2812RGB lights light up with random colors, like a flowing
light.

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

### Project 4：PIR Motion Sensor

![15](media/image/8e527b21d2e89c43f0fa894cb32f55c8.png)

**(1)Project Introduction**

The Pyroelectric infrared motion sensor can detect infrared signals from moving
objects, and output switching signals. Applied to a variety of occasions, it can
detect movement of human body.

Conventional pyroelectric infrared sensors are much more bigger, with complex
circuit and lower reliability. Yet, this new pyroelectric infrared motion
sensor, is more practical. It integrates a digital pyroelectric infrared sensor
and connecting pins. It features higher sensibility and reliability, lower power
consumption, light weight, small size, lower voltage working mode and simpler
peripheral circuit.

**(2)About PIR Motion Sensor:**

![](media/image/ee515734c07dde5b3e5c06f3916e6b74.png)

| Working Voltage：      | DC 4.5-6.5V                                          |
|------------------------|------------------------------------------------------|
| Max Working Current：  | 50MA                                                 |
| Static Current:        | \<50uA                                               |
| Control Port：         | Digital output (high level is 3.3V，low level is 0V) |
| Control Signals:       | Digital signal 1/0                                   |
| Working Temperature：  | -10 \~ 50 ℃                                          |
| Max detection distance | 4m                                                   |
| Sensing Angle：        | ＜100°                                               |
| Trigger Way:           | L doesn’t repeatedly trigger/H trigger repeatedly    |

Note：

1\. The maximum distance is 4 meters during testing.

2\. In the test, open the white lens to check rectangular sensing part. When the
long line of the sensing part is parallel to the ground, the distance is the
best.

3\. In the test, covering the sensor with white lens can sense the distance
precisely.

4\. The distance is best at 25℃, and the detection distance value will reduce
when temperature exceeds 30℃.

5\. After powering up and uploading the code, you can start testing after 5-10
seconds, otherwise the sensor is not sensitive.

**(3)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                         | File Name                        |
|-----------|-----------------------------------------------------------------------------------------------|----------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 4：PIR Motion Sensor | Project 4：PIR Motion Sensor.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/ee606a1f9971d0a8225187832fca8faa.png)
![](media/image/57a0a37b70eb69d70483c66a49b71947.png)

![](media/image/ee272defaa7ac0cc8a31f3bddc7df0cf.png)

**The complete code is as follows：**

| Micro:bit Expansion Board | PIR Motion Sensor |
|---------------------------|-------------------|
| GND                       | G                 |
| 5V                        | V                 |
| S（15）                   | S                 |

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_RyWcKV180azi" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(4)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch.

The micro:bit will show a smile image. Then click“Show console device”

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

If PIR motion sensor detects someone nearby, the serial monitor will display “1”
, and the indicator on the module will be off. If nobody is around, the serial
monitor will show “0”, the indicator will be on.

As shown below:

![](media/image/e4cfd6624a82c7637694891563e2e27e.png)

If your computer system is Windows7/8 instead of Windows 10, the device can’t be
paired in Google Chrome, as a result, the digital and analog signals can’t be
read.

Here, we need CoolTerm software to read data.

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud
rate(the baud rate of USB serial communication of micro:bit V2 is 115200 through
the test). Click“OK”and“Connect”.

![](media/image/6073f5ee860986fb8ba4e37d3a84e6d4.png)

### Project 5：Induction Lamp

**(1)Project Introduction**

In the previous project experiment, we have mastered the working principle of
the PIR motion sensor and its control method. In this project, we combine it
with a yellow LED to control LED’s brightness

**(2)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                       | File Name                      |
|-----------|---------------------------------------------------------------------------------------------|--------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 5：Induction Light | Project 5：Induction Light.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/4c5f40ff2175d79937ce5a4be8a6bfcc.png)
![](media/image/a638710a0ef8870cbd3c094f8c20e422.png)

![](media/image/f932d480eba97befaa1a0be7acd542b4.png)

**The complete code is as follows：**

| Micro:bit Expansion Board | PIR Motion Sensor |   | Micro:bit Expansion Board | Yellow LED Module |
|---------------------------|-------------------|---|---------------------------|-------------------|
| GND                       | G                 |   | GND                       | G                 |
| 5V                        | V                 |   | 5V                        | V                 |
| S（15）                   | S                 |   | S（16）                   | S                 |

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_4c5Vg76j2h77" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(3)Test Results:**

Upload the test code to the micro:bit, plug in power, dial the DIP switch to ON
and press“1”on the rocket switch.

The micro:bit will show a smile image.

When the PIR motion sensor detects people, the yellow LED will be on; otherwise,
the LED will be off.

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

### Project 6: Adjust angles of servo

![](media/image/6f0776b01b35f18b0568158ffbbc7a77.png)

**(1)Project Introduction**

![](media/image/69be958142b773acdae33eeef12afed7.png)

Servo motor is a position control rotary actuator. It mainly consists of a
housing, a circuit board, a core-less motor, a gear and a position sensor. Its
working principle is that the servo receives the signal sent by MCU or receiver
and produces a reference signal with a period of 20ms and width of 1.5ms, then
compares the acquired DC bias voltage to the voltage of the potentiometer and
obtain the voltage difference output.

When the motor speed is constant, the potentiometer is driven to rotate through
the cascade reduction gear, which leads that the voltage difference is 0, and
the motor stops rotating. Generally, the angle range of servo rotation is 0°
\--180°.

**(2)Working Principle of Servo：**

The rotation angle of servo motor is controlled by regulating the duty cycle of
PWM (Pulse-Width Modulation) signal. The standard cycle of PWM signal is 20ms
(50Hz). Theoretically, the width is distributed between 1ms-2ms, but in fact,
it's between 0.5ms-2.5ms. The width corresponds the rotation angle from 0° to
180°. But note that for different brand motors, the same signal may have
different rotation angles.

![6780083(1)](media/image/0982cb7b28f4accde7d378ba812c8bcb.png)

Through the experiment, the pulse range of the servo is 0.65ms\~2.5ms.

| high level time | Servo angle | Reference signal cycle time（20ms） |
|-----------------|-------------|-------------------------------------|
| 0.65ms          | 0°          | 0.65ms high level+19.35mslow level  |
| 1.5ms           | 90°         | 1.5ms high level+18.5mslow level    |
| 2.5ms           | 180°        | 2.5ms high level+17.5mslow level    |

**(3)Servo：**

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

Note: Supplying power via USB cable or computer may burn the servo; thus, we
recommend using batteries.

**(4)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                              | File Name                             |
|-----------|----------------------------------------------------------------------------------------------------|---------------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 6: Adjust angles of servo | Project 6：Adjust angles of servo.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/7540e63e8641fd940b2a8c26e3ebcf18.png)
![](media/image/9200db9c2fdd6b0e9b5596009d6fa23b.png)

**The complete code is as follows：**

| Micro:bit Expansion Board | Servo  |
|---------------------------|--------|
| GND                       | Brown  |
| 5V                        | Red    |
| S（8）                    | Orange |

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_fK0aDY1vJgFU" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(5)Test Results:**

Upload the test code to the micro:bit, plug in power, dial the DIP switch to ON
and press“1”on the rocket switch. The micro:bit will show smile expression, the
servo will rotate 0°\~45°\~90°\~135°\~180°\~0°，in loop way. ([How to
download?](#A01) [How to quick download?](#_7.3.快速下载))

### Project 7: 130 Motor

![25(1)](media/image/e092ffebd3240e6e157a7872731a9b58.png)

**(1)Project Introduction**

130 motor adopts the HR1124S chip which is applied to single-channel H-bridge
drive chip in direct current motor.

H-bridge driving part uses the PMOS and NMOS power tubes of low on-resistance.
In addition, the HR1124S chip has the low standby and static current.

This motor is compatible with all kinds of MCU control boards. It comes with
2.54mm anti-reverse white connectors. In the experiment, you can take advantage
of the voltage direction of IN+和IN- to control the rotation of motor and alter
its speed via PWM signals

**(2)Parameters：**

| Working Voltage：                               | 3.3-5V(DC)    | Max Current：             | 200mA (DC5V)                       |
|-------------------------------------------------|---------------|---------------------------|------------------------------------|
| Max Power：                                     | 1W            | Control port：            | Dual digital port（digital input） |
| Working Temperature：                           | -10°C \~+50°C | Environmental Attribute： | ROHS                               |
| ![](media/image/2498f64be175011ed8b3263749146e4f.png) |               |                           |                                    |

**(3) Test Code 1:（high/low level control）**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                 | File Name             |
|-----------|---------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 7：130 Motor | Project 7：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/14926f94bec47701d715c550f546b163.png)
![](media/image/1c5639bb50df3862d3977f32f82d9279.png)

**The complete code is as follows：**

| Micro:bit Expansion Board | Motor |
|---------------------------|-------|
| GND                       | G     |
| 5V                        | V     |
| S（13）                   | IN+   |
| S（12）                   | IN-   |

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_Te0hopH6yCef" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**Code Explanation：**

| IN+（digital port P12）                         | IN-（digital port P13） | Fan              |
|-------------------------------------------------|-------------------------|------------------|
| high level（1）                                 | low level（0）          | Rotate clockwise |
| ![](media/image/5b05d8cffe8f993a7d7d66227dcaaa36.png) |                         |                  |

| IN+（digital portP12）                          | IN-（digital port P13） | fan                  |
|-------------------------------------------------|-------------------------|----------------------|
| low level（0）                                  | high level（1）         | Rotate anticlockwise |
| ![](media/image/5b05d8cffe8f993a7d7d66227dcaaa36.png) |                         |                      |

| IN+（digital portP12）                          | IN-（digital port P13） | fan          |
|-------------------------------------------------|-------------------------|--------------|
| low level（0）                                  | low level（0）          | Not rotating |
| ![](media/image/b05e7e6e2738c4c0cf746320a84f3b3b.png) |                         |              |

| IN+（digital portP12）                          | IN-（digital port P13） | fan          |
|-------------------------------------------------|-------------------------|--------------|
| high level（1）                                 | high level（1）         | Not rotating |
| ![](media/image/4c3fa131fad181e0cb7bc4d31e81773a.png) |                         |              |

**4.Test Code 2：（PWM Speed control ）**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                 | File Name             |
|-----------|---------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 7：130-Motor | Project 7：Code-2.hex |

You can edit code blocks yourself:

![](media/image/670d33bab272a0cfdfd6b8cd772fde6b.png)
![](media/image/1c5639bb50df3862d3977f32f82d9279.png)

**The complete code is as follows：**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_dwF3i5Wzfa3T" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**Code Explanation：**

| IN+（digital portP12）                          | IN-（digital portP13） | fan              |
|-------------------------------------------------|------------------------|------------------|
| high level（1）                                 | PWM 600                | Rotate clockwise |
| ![](media/image/9b4ffc888744c02b2cf152a3f3c43659.png) |                        |                  |

| IN+（digital portP12）                          | IN-（digital portP13） | Fan                  |
|-------------------------------------------------|------------------------|----------------------|
| low level（0）                                  | PWM 400                | Rotate anticlockwise |
| ![](media/image/432800171dbab6b1c2ae84de3d1246d8.png) |                        |                      |

| IN+（digital portP12）                          | IN-（digital portP13） | fan          |
|-------------------------------------------------|------------------------|--------------|
| low level（0）                                  | PWM 0                  | Not rotating |
| ![](media/image/5726c886bf6241e91702f02d5bd9d2af.png) |                        |              |

| IN+（digital portP12）                          | IN-（digital portP13） | fan          |
|-------------------------------------------------|------------------------|--------------|
| high level（1）                                 | PWM 1023               | Not rotating |
| ![](media/image/63545df9b0b7a819f0ee2f56c2048296.png) |                        |              |

**5.Test Results：**

Upload the test code to the micro:bit, plug in power, dial the DIP switch to ON
and press“1”on the rocket switch. The fan will rotate clockwise for 5s, stop 1,
rotate anticlockwise for 5s and stop for 1s, in loop way. ([How to
download?](#A01) [How to quick download?](#_7.3.快速下载))

### Project 8：Lithium Battery Power Module

**(1)Project Introduction**

This module integrates a charging and discharging chip, which can be interfaced
with an external rechargeable battery through the PH2.0MM interface. In the
experiment,we use a single lithium battery.

It has a Micro USB port and a charging port for solar panels, which can supply
power for an external lithium battery.

In addition, this module has a boost module which can increase the voltage of
batteries to 6.6V. The DIP switch on the module is the OUTPUT switch of 6.6V.
The pin G and V can output 6.6V and the pin S can read the battery voltage after
the resistance 1/2 voltage

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

![](media/image/189777dcc6b180028d01671c2ea49186.png)

**(4)Features：**

![](media/image/07e545ee5517782911cb24aac7b87a2d.png)

SOLAR4.8-6.0V, the input port of power, is connected to polar panels.

The solar energy is converted into electric energy via solar panels.

![](media/image/ca26c0fdc91084511b3d9a948df1fd66.png)

BAT, the output port of power, is interfaced with the lithium battery
holder(rechargeable batteries) and saves the electric energy into batteries.

![](media/image/252c3ee03fefe739a910924413f1cc62.png)

This is the switch. Slid to ON end, then the external lithium battery will be
connected, supplying to the expansion board; on the contrary, slide to OFF, then
the current of lithium battery will be disconnected.

![](media/image/92b0c19b4eab104090d92d8c8c7b8391.png)

You can charge the lithium battery via USB cable.

**(5)Test the solar battery panel：**

We can connect the solar battery panel and an LED we provide together, as shown
below.

Disconnect the power, after a while, you will see the LED light up.

![IMG_256](media/image/a4c83004e0303b67f36de54a9425c920.png)**![图2](media/image/5cbf09cac4f56831baf6224b1e9c546d.jpeg)**

### Project 9：1602 LCD

![KS0062 (4)](media/image/b28242c31d938ab51c634aa121490ffa.jpeg)

**(1)Project Introduction**

With I2C communication module, this is a display module that can show 2 lines
with 16 characters per line.

It shows blue background and white word and connects to I2C interface of MCU,
which highly save the MCU resources.

On the back of LCD display, there is a blue potentiometer for adjusting the
backlight. The communication address defaults to 0x27.

The original 1602 LCD can start and run with 7 IO ports, but ours is built with
Arduino IIC/I2C interface, saving 5 IO ports. Alternatively, the module comes
with 4 positioning holes with a diameter of 3mm, which is convenient for you to
fix on other devices.

Notice that when the screen gets brighter or darker, the characters will become
more visible or less visible.

![](media/image/fc7e69308162f73eda88903c6caf90e5.png)

**(2)Parameters：**

| Working Voltage ：                                               | DC5V                                             | I2C Address：                                                      | 0x27                     | Control Port： | I2C      |
|------------------------------------------------------------------|--------------------------------------------------|--------------------------------------------------------------------|--------------------------|----------------|----------|
| Working Current：                                                | \< 130mA                                         | Working Temperature：                                              | 0°C \~ 45°C（recommend） | Driving Chip： | PCF8574T |
| GND: a pin connected to the ground                               |  VCC：A pin that connects to a +5V power supply  | SDA： A pin that connects to analog port A4 for IIC communication  |                          |                |          |
| SCL：a pin interfaced with SCL or A5，used for IIC communication | Backlight                                        | Adjustable contrast                                                |                          |                |          |

**(3)Add I2C LCD 1602 Library：**

Set code by the library, and click“Extensions”to add the library file:

![](media/image/792e3ec83c270dffdae7758a0721600d.png)

Tap <https://github.com/keyestudio2019/ks_IoT> in the searching box and
click“Search”, as shown below. Click **IoT_keyestudio** library. Then the
IoT_keyestudio library is set up.

In addition, the I2C LCD 1602 library is included in the **IoT_keyestudio.**

![](media/image/b82aa069120beb40adcbf4dfbaab5b7b.png)

You can check the I2C LCD 1602 library in the block list.

![](media/image/e203135e4e792c75f1ac3c00df59ef0f.png)

**(4)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                | File Name               |
|-----------|--------------------------------------------------------------------------------------|-------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 9：1602 LCD | Project 9：1602 LCD.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/479e0d5b572bee55c927b7a03242fea7.png)
![](media/image/4ba05f6a2a403d67b8399f042923ed1e.png)

![](media/image/dc33c9fc033dd62a3a689c0f5f32f6d1.png)

**The complete code is as follows：**

| Micro:bit Expansion Board | I2C 1602 LCD Module |
|---------------------------|---------------------|
| GND                       | GND                 |
| 5V                        | 5V                  |
| SDA                       | SDA                 |
| SCL                       | SCL                 |

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_LJXcJjivqgcd" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(5)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch.

The micro:bit board will show a smile image. Then rotate the knob of the
potentiometer at the back of the LCD module, you will see“Keyestudio”at one row
and numbers at the second row. In addition, the number increases by 1 with an
interval of 0.5s.

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

Note: When the display doesn’t show characters, you can adjust the potentiometer
behind the 1602LCD and backlight to make the 1602LCD display the corresponding
character string.

### Project 10：Steam Sensor

![14](media/image/932398f7831e7e6d0f1c0b6f035a79a4.png)

**(1)Project Introduction**

This is a commonly used steam sensor. Its principle is to detect the amount of
water by bare printed parallel lines on the circuit board. The more the water
content is, the more wires will be connected. As the conductive contact coverage
increases, the output voltage will gradually rise. It can detect water vapor in
the air as well. The steam sensor can be used as a rain water detector and level
switch. When the humidity on the sensor surface surges, the output voltage will
increase.

The sensor is compatible with various microcontroller control boards, such as
Arduino series microcontrollers. When using it, connect the sensor to the analog
port of the Micro:bit microcontroller, and display the corresponding analog
value on the serial monitor.

Note: the connection part is not waterproof, therefore, don’t immerse it in the
water please.

**(2) Parameters：**

| Working Voltage：           | DC 3.3-5V                                                              | ![](media/image/3b0760476232188966281131ba9da7e5.png) |
|-----------------------------|------------------------------------------------------------------------|-------------------------------------------------|
| Working Temperature Range： | －10℃～＋70℃                                                           |                                                 |
| Max Working Current：       | 5uA (DC5V，when the two pins of the steam sensor are in short circuit. |                                                 |
| Control Port：              | Analog output                                                          |                                                 |

**(3)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                     | File Name                    |
|-----------|-------------------------------------------------------------------------------------------|------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 10：Steam Sensor | Project 10：Steam Sensor.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/dce9000ddbbe13b445bc25ad3cb284a6.png)![](media/image/6fa8bbc6fd7bbe12273cfdcad74a5f2d.png)

![](media/image/0741e42830dc22b6d7c2d482f8c34f1f.png)

**The complete code is as follows：**

| Micro:bit Expansion Board | Steam Sensor |
|---------------------------|--------------|
| GND                       | G            |
| 3V3                       | V            |
| S(0)                      | S            |

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_bvad4eYA745J" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(4)Test Results:**

Upload the test code, and plug in power with micro USB cable. Then the micro:bit
will show“❤”. At same time, click the“Show console Device” ([How to
download?](#A01) [How to quick download?](#_7.3.快速下载))

![](media/image/9efcc8dab24cf3a1a7ca9ebc8d360502.png)

The more the immersed area of the module, the larger the analog value.

As shown below;

The serial monitor will show the output data, and the steam sensor will read the
analog signals at the signal end.

![](media/image/3c3e48189a767dc50dc67ca5c424ed67.png)

If your computer system is Windows7/8 instead of Windows 10, the device can’t be
paired in Google Chrome, as a result, the digital and analog signals can’t be
read.

Here, we need CoolTerm software to read data.

Open **CoolTerm**, click **Options** to select **SerialPort**. Set **COM** port
and 115200 baud rate(the baud rate of USB serial communication of micro:bit V2
is 115200 through the test). Click“OK”and“Connect”.

The more the immersed area of the module, the larger the analog value.

As shown below;

![](media/image/56881fbbdf58e29e7d187927cfe19919.png)

### Project 11：Rains Alarm

**(1)Project Introduction**

Steam Sensor is a wide range of applications, such as raining alarm, automotive
automatic scraping system, intelligent lighting system, and smart sunroof
system. In the previous project experiment, we already know the working
principle of Steam Sensor, then in this project experiment, we combine Steam
Sensor, Micro:bit, and yellow LEDs, making a simple rain alarm.

**(2)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                    | File Name                   |
|-----------|------------------------------------------------------------------------------------------|-----------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 11：Rains Alarm | Project 11：Rains Alarm.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/4c5f40ff2175d79937ce5a4be8a6bfcc.png)
![](media/image/0165996a1f0c761cae6fc031bbbc7bf4.png)

![](media/image/a6fa09b49609f60b900650eabf6f8885.png)
![](media/image/2ebe5fba3339783f1232c0e8e495ec7d.png)

![](media/image/d2763eca7dee6a88012a469a4a21506f.png)

**The complete code is as follows：**

| Micro:bit Expansion Board | Steam Sensor |   | Micro:bit Expansion Board | Yellow LED Module |
|---------------------------|--------------|---|---------------------------|-------------------|
| GND                       | G            |   | GND                       | G                 |
| 3V3                       | V            |   | 5V                        | V                 |
| S（0）                    | S            |   | S（16）                   | S                 |

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_VPK8XAh8Hhdx" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(3)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch.

The micro:bit will show smile expression. When the detected analog signals are
more than 500, the micro:bit will emit“tick, tick”and the yellow LED will flash.
Otherwise, no sound and LED off.

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

### Project 12：Analog Gas（MQ-2）Sensor

![17](media/image/5ad704f1db5e43058513cf8ed2d53047.png)

**(1)Project Introduction**

This gas sensor is used for household gas leak alarms, industrial combustible
gas alarms and portable gas detection instruments. Also, it is suitable for the
detection of liquefied gas, benzene, alkane, alcohol, hydrogen, etc.,

The MQ-2 smoke sensor can be accurately a multi-gas detector, with the
advantages of high sensitivity, fast response, good stability, long life, and
simple drive circuit.

It can detect the concentration of flammable gas and smoke in the range of
300\~10000ppm. Meanwhile, it has high sensitivity to natural gas, liquefied
petroleum gas and other smoke, especially to alkanes smoke.

It must be heated for a period of time before using the smoke sensor, otherwise
the output resistance and voltage are not accurate. However, the heating voltage
should not be too high, otherwise it will cause internal signal line to blow.

It belongs to the tin dioxide semiconductor gas-sensitive material. At a certain
temperature, tin dioxide adsorbs oxygen in the air and forms negative ion
adsorption of oxygen, reducing the electron density in the semiconductor,
thereby increasing its resistance value.

When in contact with flammable gas in the air and smog, and the potential
barrier at the grain boundary is adjusted by the smog, it will cause the surface
conductivity to change. With this, information about the presence of smoke or
flammable gas can be obtained. The greater the concentration of smoke or
flammable gas in the air, the greater the conductivity, and the lower the output
resistance, the larger the analog signal output. In addition, the sensitivity
can be adjusted by rotating the potentiometer.

![](media/image/959fb3dc082b2bafcc8dc3f4a1845d6c.png)

1.  **Analog Gas（MQ-2）Sensor：**

| Working Voltage：          | 3.3-5V                             | ![](media/image/42a27e658a946a1d9845c5846db4b412.png) |
|----------------------------|------------------------------------|-------------------------------------------------|
| Working Current：          | 160mA (DC5V)                       |                                                 |
| Working Temperature：      | 0°C \~ 40°C                        |                                                 |
| Control Port：             | Digital and analog output          |                                                 |
| Detection concentration：  | 300-10000ppm (combustible gas )    |                                                 |
| Rake Ratio：               | ≤0.6(R3000ppm/R1000ppm C3H8)       |                                                 |
| Sensitivity                | Rs(in air)/Rs(1000ppm isobutane)≥5 |                                                 |
| Sensitive Resistance（Rs） | 2KΩ-20KΩ(in 2000ppm C3H8 )         |                                                 |

**Features：**

(1) Have a signal output instruction.

(2) Dual-channel signal output (analog output and TTL level output)

(3) TTL output effective signal is Low Level. (When the Low Level is output, the
signal light will be on)

(4) The analog output is 0 \~ 5V voltage. The higher the concentration, the
higher the voltage.

(5) a good sensitivity to liquefied gas, natural gas and urban gas.

(6) Have long-term life expectancy and reliable stability

(7) Fast response recovery.

**3.Test Code：**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                                | File Name                               |
|-----------|------------------------------------------------------------------------------------------------------|-----------------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 12：Analog Gas(MQ-2) Sensor | Project 12：Analog Gas(MQ-2) Sensor.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/dce9000ddbbe13b445bc25ad3cb284a6.png)![](media/image/6fa8bbc6fd7bbe12273cfdcad74a5f2d.png)

![](media/image/af20cbb0fdb97531070ceed6f6ba16f5.png)

**The complete code is as follows：**

| Micro:bit Expansion Board | Analog Gas（MQ-2）Sensor |
|---------------------------|--------------------------|
| GND                       | G                        |
| 5V                        | V                        |
| S（1）                    | D                        |

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_imPaCkH4m685" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(4)Test Results:**

Upload the test code to the micro:bit, plug in power and dial the DIP switch to
ON. Then the micro:bit will show smile expression and a green indicator will be
on. You can adjust the blue potentiometer to make the sensitivity high.

The micro:bit will show a smile image. You can maintain the sensitivity good by
adjusting the blue potentiometer and click“Show Console Device”.

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

![](media/image/41568bf77231c21bc1794d72279bec00.png)

The serial monitor will show 1 if the sensor doesn’t detect any gas; however, if
you make the firelighter close to it, number 0 will be output and the indicator
will be on. As shown below;

![](media/image/99500f8575bada38053466a39e2a3a6c.png)

If your computer system is Windows7/8 instead of Windows 10, the device can’t be
paired in Google Chrome, as a result, the digital and analog signals can’t be
read.

Here, we need CoolTerm software to read data.

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud
rate(the baud rate of USB serial communication of micro:bit V2 is 115200 through
the test). Click“OK”and“Connect”.

Enable fire lighter and make it close to the gas sensor , the serial monitor
will print 0; however, if you remove the fire lighter, number 1 will be output.

![](media/image/6073f5ee860986fb8ba4e37d3a84e6d4.png)

### Project 13：Gas Leakage Detector

**(1)Project Introduction**

This MQ-2 gas sensor is used for household gas leak alarms, industrial
combustible gas alarms and portable gas detection instruments. And it is
suitable for the detection of liquefied gas, benzene, alkane, alcohol, hydrogen,
etc., and widely used in various fire alarm systems. It can be accurately a
multi-gas detector, and has the advantages of high sensitivity, fast response,
good stability, long life, and simple drive circuit.

It can detect the concentration of flammable gas and smoke in the range of
300\~10000ppm.Meanwhile, it has high sensitivity to natural gas, liquefied
petroleum gas and other smoke, especially to alkanes smoke.

We will make a gas leakage detector with a MQ-2 gas sensor, a yellow LED and a
1602 LCD.

**(2)Add the 1602 LCD library**

Library link: <https://github.com/keyestudio2019/ks_IoT>

(refer to the project 91602 LCD)

**(3)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                             | File Name                            |
|-----------|---------------------------------------------------------------------------------------------------|--------------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 13: Gas Leakage Detector | Project 13：Gas Leakage Detector.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/4c5f40ff2175d79937ce5a4be8a6bfcc.png)![](media/image/6c65dc19f8bfe1115a666096d74a44a9.png)![](media/image/ed4873373d5346867179af7eac2a5a24.png)
![](media/image/af20cbb0fdb97531070ceed6f6ba16f5.png)
![](media/image/8a2447bcc90336249196091050f3bab4.png)![](media/image/51bd2173e551c65288fcad9c6f6c4ad0.png)

**The complete code is as follows：**

| Micro:bit Expansion Board | Analog Gas（MQ-2）Sensor |   | Micro:bit Expansion Board | Yellow LED Module |   | Micro:bit Expansion Board | 1602 LCD Module |
|---------------------------|--------------------------|---|---------------------------|-------------------|---|---------------------------|-----------------|
| GND                       | G                        |   | GND                       | G                 |   | GND                       | GND             |
| 5V                        | V                        |   | 5V                        | V                 |   | 5V                        | 5V              |
| S（1）                    | D                        |   | S（16）                   | S                 |   | SDA                       | SDA             |
|                           |                          |   |                           |                   |   | SCL                       | SCL             |

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_Kxz4U2iYJhVA" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(4)Test Results**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch.

The micro:bit will show a smile image. Make a fire lighter close to the gas
sensor and press its button, 1602 LCD will display“MQ-2”at the first row and
show“gas leakage”at the second row. At same time, it will emit“tick,tick”sound
and LED will flash.

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

### Project 14：DHT11 Temperature and Humidity Sensor

![1](media/image/f7ff148f3c57a033e5898e955479d368.png)

**(1)Project Introduction**

This DHT11 temperature and humidity sensor is a composite sensor which contains
a calibrated digital signal output of the temperature and humidity.

DHT11 temperature and humidity sensor uses the acquisition technology of the
digital module and temperature and humidity sensing technology, ensuring high
reliability and excellent long-term stability.

It includes a resistive element and a NTC temperature measuring device.

**(2) Parameters：**

| Working Voltage：     | 3.3V-5V（DC）              |    ![](media/image/915eb0254a9220c7441a5a1106d96d4f.png) |
|-----------------------|----------------------------|----------------------------------------------------|
| Max Working Current： | 50mA                       |                                                    |
| Max Power：           | 0.25W                      |                                                    |
| Control Port：        | Digital two-way single bus |                                                    |
| Temperature Range：   | 0-50℃（±2℃）               |                                                    |
| Humidity Range        | 20-90%RH（±5%RH）          |                                                    |
| Working Temperature   | -25℃\~+60℃                 |                                                    |

**DHT11 Temperature and Humidity Sensor：**

|                 | **Single-bus data format**                                                                                                                                                                                                                                     |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Initial signal  | The microprocessor pulls down the data bus(SDA) for at least 18 ms (less than 30 ms)                                                                                                                                                                           |
| Response signal | The sensor pulls down the data bus (SDA) 83 μs, and then pulls up 87 μs to respond to the initial signal of the host.                                                                                                                                          |
|  humidity       | The humidity high-bit is the humidity integer part of the data, the humidity low-bit is the humidity fractional part of the data.                                                                                                                              |
|   temperature   | The temperature high-bit is the temperature integer part of the data, the temperature low-bit is the temperature fractional part of the data. And the temperature low bit8 is 1, which indicates the negative temperature; otherwise the positive temperature. |
| Check bit       | Check bit = humidity high bit + humidity low bit+ temperature high bit + temperature low bit                                                                                                                                                                   |

**Overall Communication Process：**

After the user host (MCU) sends a start signal, the DHT11 is converted from the
low consumption mode to the high one. After the start signal is completed, the
DHT11 sends the 40bit data, triggering an information collection. The signal
transmission is shown in the figure.

Communication protocol of DHT11 Sensor：

<https://www.mouser.com/datasheet/2/758/DHT11-Technical-Data-Sheet-Translated-Version-1143054.pdf>

**(4)Add the DHT11 library**

Set code by the library, and click“Extensions”to add the library file.

![](media/image/792e3ec83c270dffdae7758a0721600d.png)

Copy the link <https://github.com/keyestudio2019/ks_IoT> in the searching box,
as shown below and click the **IoT_keyestudio** library. Then the
**IoT_keyestudio** library is set up.

![](media/image/b82aa069120beb40adcbf4dfbaab5b7b.png)

You can find it in the blocks list.

![](media/image/e962d234a486ee2c3e6ef4b5bb71df01.png)

**(5)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                                              | File Name                                             |
|-----------|--------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 14：DHT11 Temperature and Humidity Sensor | Project 14：DHT11 Temperature and Humidity Sensor.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/dce9000ddbbe13b445bc25ad3cb284a6.png)
![](media/image/a6de97b1224916ef06cd6c8f9de95808.png)

![](media/image/6fa8bbc6fd7bbe12273cfdcad74a5f2d.png)

**The complete code is as follows：**

| Micro:bit Expansion Board | DHT11 Temperature and Humidity Sensor |
|---------------------------|---------------------------------------|
| GND                       | G                                     |
| 5V                        | V                                     |
| S（2）                    | S                                     |

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_hWbgLu2WKCrL" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(6)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch. The micro:bit will show a smile image. Then
click“Show console Device” ([How to download?](#A01) [How to quick
download?](#_7.3.快速下载))

![](media/image/41568bf77231c21bc1794d72279bec00.png)

The detected temperature and humidity value is shown as below:

![](media/image/1eed40db46ad803d2380f7e1a0b10794.png)

If your computer system is Windows7/8 instead of Windows 10, the device can’t be
paired in Google Chrome, as a result, the digital and analog signals can’t be
read.

Here, we need CoolTerm software to read data.

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud
rate(the baud rate of USB serial communication of micro:bit V2 is 115200 through
the test). Click“OK”and“Connect”.

The temperature and humidity value will be displayed on the serial monitor, as
shown below:

![](media/image/de24244dc80605fe72da4f6fae9e387b.png)

### Project 15：Temperature and Humidity Display

**(1)Project Introduction**

We’ve mastered the working principle of the DHT11 temperature and humidity
sensor. In this project, we will make a temperature and humidity display with it
and a 1602 LCD.

**(2)Add the 1602 LCD and DHT11 library：**

The link to add libraries: <https://github.com/keyestudio2019/ks_IoT>

You can refer to project 9 and 14

**(3)Test Code：**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                                         | File Name                                        |
|-----------|---------------------------------------------------------------------------------------------------------------|--------------------------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 15：Temperature and Humidity Display | Project 15：Temperature and Humidity Display.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/image/dce9000ddbbe13b445bc25ad3cb284a6.png)
![](media/image/a6de97b1224916ef06cd6c8f9de95808.png)

![](media/image/51df049a60324fddc8e77194173f5ebe.png)

**The complete code is as follows：**

| Micro:bit Expansion Board | DHT11 Temperature and Humidity Sensor |   | Micro:bit Expansion Board | 1602 LCD Module |
|---------------------------|---------------------------------------|---|---------------------------|-----------------|
| GND                       | G                                     |   | GND                       | GND             |
| 5V                        | V                                     |   | 5V                        | 5V              |
| S（2）                    | S                                     |   | SDA                       | SDA             |
|                           |                                       |   | SCL                       | SCL             |

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_2kc9voWecV3W" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(4)Test Results：**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch. The micro:bit will show smile image.

The 1602 LCD will show the temperature and humidity value in the current
environment. ([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

### Project 16：Multiple Functions

**(1)Project Description: ：**

The final lesson is the combination of all modules and sensors. It is an analog
smart home.

**(2)Preparation：**

A micro:bit and the smart home model.

Interface the micro:bit with a computer with a micro USB cable.

Add the libraries：https://github.com/keyestudio2019/ks_IoT

**(3)Test Code:**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_hTJPL8hp2aVJ" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(4)Test Results:**

When you are close to the PIR motion sensor, the yellow LED will be on;
otherwise, the yellow LED will be off.

When dropping water onto the steam sensor and analog signal is more than 300,
the window will be close; when the analog signal is less than 300, the window
will be on.

The password can be set by the button A and B on the micro:bit board.

Pressing A and B respectively means‘.’and‘-’.

Pressing A and B simultaneously indicates“confirm”

The 5\*5 LED lights will show ![](media/image/15f93c52c9395ccaca4a5aa58e3aeef8.png)
picture and the I2C1602LCD will display “Successful”and“Open the door”, the 6812
2x2 RGB will show purple color. However, if the password is wrong, “error” will
pop up on the LCD module and show “Enter password”

Touch the logo area of the micro:bit, the 1602LCD will show“Close the
door”and“Enter password”. Next, the door will be closed and the 6812 module will
be off.

When the temperature sensor on the micro:bit detects the temperature higher than
or equal to 30℃ , the small fan will rotate

### Project 17：BT-controlled LED

**(1)Project Introduction**

We control LED on and off via app.

**(2)Preparation：**

**Install App**

Android system：

Search IoT microbit on Google play, or install the app package we provide(in the
Android APK folder)

![](media/image/41211c1f0617bf0c5a3b5277c915c269.png)

iOS system: search IoT microbit in the App store, as shown
below:![](media/image/2db677ed5bd948d439b235c18842a6a7.png)

Add the BT library file as shown below:

![](media/image/b39b92316672f6e1c4c0a53399b8981a.png)

**(3)Test Code:**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_LmPYzT2Ce9RK" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

Note: after finishing code, you need to enable “No paring Required: Anyone can
connect via Bluetooth”

![](media/image/aa681bc193cf3e2439e3c95e0c3823d3.png)

![](media/image/251cd113bfced468d8f947181675f168.png)

**(4)Test Results:**

Upload code to the micro:bit, open the switch of the smart home, enable the App
and click **Connect**

![](media/image/24b08a4c573bc4ccee000c4884d9bd72.png)

Search the Bluetooth name of micro:bit board

![](media/image/4327ae9bebfc837896d6f99d019c1e2f.png)

After connecting well, click LED icon

![](media/image/bac6406492337c07e399362d5804024e.png)

Then you will see LED on. If you click this icon again, LED will be off.

### Project 18：Smart Home

**(1)Project Introduction**

In this section, we will control the smart home via Bluetooth

**(2) Preparation：**

Download this app first.

![英文说明图](media/image/3d2edb248f622ff3bed976dc3f9f244e.png)

Add the Bluetooth library file.

![](media/image/b39b92316672f6e1c4c0a53399b8981a.png)

Add the libraries：https://github.com/keyestudio2019/ks_IoT

**(3)Test Code:**

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_hhLTbqgTvR7F" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

**(4)Test Results:**

Burn the code to the micro:bit, turn on the switch of the smart home model, and
enable the Bluetooth of your device and app.

![英文操作图111](media/image/b086bbbcf4dd831a9660ad977b6f9b50.png)

The password can be set by the button A and B on the micro:bit board.

Pressing A and B respectively means‘.’and‘-’.

Pressing A and B simultaneously indicates“confirm”

The 5\*5 LED lights will show ![](media/image/15f93c52c9395ccaca4a5aa58e3aeef8.png)
picture and the I2C1602LCD will display“Successful” and“Open the door”, the 6812
2x2 RGB will show purple color. However, if the password is wrong, “error” will
pop up on the LCD module and “Enter password”will appear.

You can touch the logo of the micro:bit to close the door.

## Resources:

[https://fs.keyestudio.com/KS4027-4028](https://fs.keyestudio.com/KS4027-4028)


