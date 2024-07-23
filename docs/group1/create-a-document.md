---
sidebar_position: 2
---

# Components in the Agricultural Cabinet

The agricultural cabinet is a system comprising various devices such as circuit breakers, contactors, timers, etc. Particularly, our industrial cabinet utilizes the Modbus RTU Relay 32CH and Yolo Uno (ESP32-S3) for device control.

## Modbus RTU Relay 32CH
---
RS485 32-Ch Relay Module
Modbus RTU Protocol, Multi Isolation Protection Circuits, Safe & Stable & Reliable

![](https://www.waveshare.com/media/catalog/product/cache/1/image/560x560/9df78eab33525d08d6e5fb8d27136e95/m/o/modbus-rtu-relay-32ch-1.jpg)


Function:
- Controls the on/off state of 32 relay channels via the Modbus RTU protocol.
  
Connection:
- Power Supply: Connect to a 24V DC power source.
RS485 Communication: Connect to the Yolo Uno via the RS485 port.

Usage:
- Configure Modbus Address: Use the DIP switches on the relay module to set the Modbus address.
- Send Control Commands: Utilize the Yolo Uno to send Modbus commands to control the state of each relay.
  

Product: [www.waveshare.com](https://www.waveshare.com/modbus-rtu-relay-32ch.htm).



## Yolo Uno (esp32-s3)
---

![](https://docs.ohstem.vn/en/latest/_images/yolo_uno1.png)


- Yolo UNO is a programming circuit designed in the form of Arduino Uno with ESP32-S3 chip, Espressif's latest chip line, with 16MB flash memory and up to 8MB PSRAM memory.

- In addition to the size and pinout being fully compatible with the traditional Arduino Uno circuit, Yolo UNO also has 12 built-in Grove standard connection ports, making it easy to use with modules and sensors in the AI ​​device ecosystem. /IoT by OhStem.


Product: [docs.ohstem.vn](https://docs.ohstem.vn/en/latest/yolo_uno/lam_quen/gioi_thieu_yolo_uno.html).

## RS485 TTR
---
Function:
- Facilitates data communication between devices via RS485.

Connection:
- Communication Wires: Connect the A and B lines of RS485 between the Yolo Uno and the Modbus RTU Relay 32CH.

Usage:
- Configure Communication: Set parameters such as baud rate, parity, and stop bits on both the Yolo Uno and the Modbus RTU Relay 32CH.
- Send/Receive Data: Use control commands on the Yolo Uno to send/receive data via RS485.
  
![](https://nshopvn.com/wp-content/uploads/2020/01/module-giao-tiep-ttl-rs485-i4sm-3.jpg)

Product: [nshopvn.com](https://nshopvn.com/product/module-giao-tiep-ttl-rs485/)
## Timer THC30A
---
![](https://down-vn.img.susercontent.com/file/sg-11134201-22100-uah5xidtnaivcf)

Function:
- Automatically schedules devices to turn on/off.

Connection:
          |               |               |
          |----------------|---------------|
          |Powre Supply   | 220V          |
          |Capacity       |30A            |
          |Timer range    |1min ~ 168 hr   |
          |Average error  |1S/24h, 25 °C  |
          |Display        |LCD            |
          |Program        | 20 on/off each day|
          |Mini interval  |1min           |
          |Temp.range     | -20°C ~ 50°C  |

Usage:
- Set actual time for THC30A:
(This step is only performed when the time indicator inside THC30A displays a time that is not correct with the actual time) Settings are as follows: hold the Clock button and press the following buttons one at a time until the screen displays the correct time

    - **D+**: change the day of the week

    - **H+**: change time

    - **M+**: change minutes

- Select mode for THC30A:
After installation is complete, press MODE (Button with hand symbol) to select the oper-
ating mode for THC30A
The bottom right corner of the screen has displays corresponding to the following 3 modes:

    - **ON**: Output is always powered

    - **Auto**: Output ON - OFF according to the scheduled time 

    - **OFF**: Output is always without power




Product: [shopee.vn/THC30A-Din-220V-30A](https://shopee.vn/R%C6%A1-Le-C%C3%B4ng-T%E1%BA%AFc-H%E1%BA%B9n-Gi%E1%BB%9D-K%E1%BB%B9-Thu%E1%BA%ADt-S%E1%BB%91-2-D%C3%A2y-THC30A-Din-7-Ng%C3%A0y-AC-220V-230V-12V-24V-48V-16A-30A-i.904936388.23306359429?gidzl=RWNzQmknHmPY7lXg0Qv106KR-6yQ_4u2AaNmRapt7LCgHQDjIl4K0NWIeciOfqbIUHJrQ65HWOvR3BH700).


## Aptomat ELCB Hyundai 30A
---

![](https://down-vn.img.susercontent.com/file/vn-11134207-7r98o-lnbrskmnts6lc7)
Function:
- Protects the electrical system from overload and short circuits.

Connection:
- Power Supply: Connect the 220V AC power source to the input terminals of the circuit breaker.
- Protected Device: Connect the device to be protected to the output terminals of the circuit breaker.

Usage:
- Check Rating: Select a circuit breaker with an appropriate rating for the system’s current.
- Reset Breaker: In the event of a trip, identify the cause and reset the breaker by toggling the switch.

Product:[shopee.vn/ELCB-Hyundai-30A](https://shopee.vn/%C3%81t-ch%E1%BB%91ng-gi%E1%BA%ADt-ELCB-Hyundai-H%C3%A0n-Qu%E1%BB%91c-h%C3%A0ng-t%E1%BB%93n-kho-m%E1%BB%9Bi-100-d%C3%B2ng-r%C3%B2-15ma-30ma-i.61028488.19084052776?gidzl=JKhOClGyi7b1KTqp_YEsVqPKt3VbSRXy2GhKDhDwwoq92eSrjNpYVrjTXZFdAhyiMblHC66DGrnzypcmVm)

## Contactor
---
Function:
- Controls the on/off state of high-power devices.

Connection:
- Control Power Supply: Connect to a control power source (typically 24V DC or 220V AC).
- Load Power Supply: Connect the load power to the contactor’s input terminals.
- Controlled Device: Connect the device to be controlled to the contactor’s output terminals.

Usage:
- Activate Contactor: Use control signals from the Yolo Uno or Timer to activate the contactor’s coil.
- Verify Operation: Ensure the contactor operates correctly without arc formation.
  
![](https://down-vn.img.susercontent.com/file/61c55914d38bf90d9403cf172bfa39b1)

product: [shopee.vn/CHN-40-220v](https://shopee.vn/Kh%E1%BB%9Fi-%C4%91%E1%BB%99ng-t%E1%BB%AB-c%C3%B4ng-t%E1%BA%AFc-t%C6%A1-CHN-63-40-25-20A-220v-d%C3%B9ng-l%E1%BA%AFp-c%C3%B9ng-c%C3%B4ng-t%E1%BA%AFc-%C4%91i%E1%BB%81u-khi%E1%BB%83n-t%E1%BB%AB-xa-c%C3%B4ng-t%E1%BA%AFc-h%E1%BA%B9n-gi%E1%BB%9D-c%C3%B4ng-t%E1%BA%AFc-wifi-i.128742053.7283263441?xptdk=0ac6187b-a70c-422c-8777-f1163d1530aa)