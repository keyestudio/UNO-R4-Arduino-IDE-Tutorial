# UNO R4 Arduino IDE Tutorial

## Windown System

### 1. Download and Install IDE

1\. download Arduino IDE (Arduino IDE2.1.1 and later versions support UNO R4).

For old version of Arduino IDE, press Ctrl+ Shift+P and execute “Arduino: Check for Arduino IDE Updates” command.

Or direct to download the latest version at [Arduino IDE](https://www.arduino.cc/en/software). 

![Img](./media/img-20240913160523.png)

Click "<span style="color: rgb(255, 76, 65);">JUST DOWNLOAD</span>" .

![Img](./media/img-20240913160832.png)

Click "<span style="color: rgb(255, 76, 65);">JUST DOWNLOAD</span>" again to download the package of **<span style="color: rgb(255, 76, 65);">arduino-ide_2.3.2_Windows_64bit.exe</span>** .

Downloaded:

![Img](./media/img-20240913161030.png)

2\. Install Arduino IDE.

Click the package of **<span style="color: rgb(255, 76, 65);">arduino-ide_2.3.2_Windows_64bit.exe</span>** and you will see an interface, please click "<span style="color: rgb(255, 76, 65);">I Agree</span>" .
![Img](./media/img-20240913162236.png)

Tick "<span style="color: rgb(255, 76, 65);">Anyone who uses this computer (all users)</span>", and "<span style="color: rgb(255, 76, 65);">Next</span>" .

![Img](./media/img-20240913162401.png)

Click "<span style="color: rgb(255, 76, 65);">Browse...</span>" to choose a path for installation. Disk C is recommended. After that, click "<span style="color: rgb(255, 76, 65);">Install</span>".

![Img](./media/img-20240913162549.png)

Installed:

![Img](./media/img-20240913162629.png)

3\. Open Arduino IDE.

![Img](./media/img-20240909085113.png)

![Img](./media/img-20240909085139.png) -- Used to check for any compilation errors.

![Img](./media/img-20240909085159.png) -- Used to upload programs to the Arduino board.

![Img](./media/img-20240909085603.png) -- Used for single-step debugging while writing programs.

![Img](./media/img-20240909085240.png) -- Used to receive serial data from the board and send them to the serial monitor of the board.

![Img](./media/img-20240909085255.png) -- Used to convert the data received by the serial port into a dynamic graph.

![Img](./media/img-20240909085402.png) -- Used to open a recently saved sample Sketch.

![Img](./media/img-20240909085426.png) -- Used to manually install the development board.

![Img](./media/img-20240909085444.png) -- Used to manually install library files.

## 2. Install Arduino UNO R4 Board Package

1\. Click ![Img](./media/img-20240909085707.png) to open “BOARDS MANAGER”. Search “UNO R4” to “INSTALL” Arduino UNO R4.

![Img](./media/img-20240909090108.png)

2\. In “Tools” → “Board”, Arduino UNO R4 boards includes two options: “Arduino UNO R4 WiFi” and “Arduino UNO R4 Minima”.

![Img](./media/img-20240909090505.png)

If you connect the UNO R4 WiFi Board to your computer via USB cable, choose “Arduino UNO R4 WiFi”:

![Img](./media/img-20240909090832.png)

If you connect UNO R4 Minima board to the computer via USB cable, choose “Arduino UNO R4 Minima”:

![Img](./media/img-20240909091139.png)

## 3. Compile and Upload Sketch

1\. For the first use of Arduino UNO R4 board, there may be no port after plugging USB cable. Click “Tools” → “Port” and you will see “COM1”. <span style="color: rgb(255, 76, 65);">Here we take “Arduino UNO R4 WIFI” to have a demonstration.</span>

![Img](./media/img-20240909093802.png)

2\. Wait for a while and Arduino UNO R4 driver will be installed automatically. After that, open “Tools” → “Port” and you will see “COM 7(Arduino UNO R4 WIFI)”. Choose this port.

![Img](./media/img-20240909094036.png)

3\. Run program “File”→“Examples”→“01 Basics”→“Blink”, which can be executed without any external library.

![Img](./media/img-20240909094855.png)

![Img](./media/img-20240913081449.png)

4\. Click ![Img](./media/img-20240909095201.png) to upload the program to UNO R4 WiFi board, and the on-board LED-L blinks.

![Img](./media/img-20240909095333.png)

![Img](./media/img-20240909095404.png)

![Img](./media/img-20240909100344.jpg)

<span style="color: rgb(255, 76, 65);">**For how to upload code to UNO R4 Minima board, please refer to the above steps**.</span> 

## MacOS System

### 1. Download and Install IDE

Choose the macOS version of Arduino IDE, and its method of download and install are similar to that of Windows.

![Img](./media/img-20240913162956.png)

Once the download is complete, click it and follow the prompts to install.

<span style="color: rgb(255, 76, 65);">**Special Reminder：** Other operations can refer to the relevant content of the Windown system above.</span>
