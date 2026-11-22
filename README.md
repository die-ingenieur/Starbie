# Starbie- 
<img width="473" height="428" alt="image" src="https://github.com/user-attachments/assets/86ba4592-77f6-4c86-bc30-5e0260ea9471" />


Starbie, your desktop toy!
It is simply a toy where you can use the movement and temperature of the surrounds to influence how your pet behaves. You can use a menu to interact with your pet and affect its stats.

Starbie,  a desktop which i made following help from the week one starter project.
I made it because i practically had no idea what to do or how to actually do anything so starbie was a great help.

## Content
Contains: menus, music, reactions behaving to movement
Features: Oled screen as a display , MPU6050 in order to track movement acceleration, Dht11 sensor to track temperature  , switches and a buzzer in order to play music
## What i changed:
What i wanted from my toy was to be able to have more functions,
  - For this , i added a buzzer to my project to be able to play melodies
  - I also changed the code to include more menu items for the user to go through like
      -  An option to change the look of your pet
      -  An option to play music based on your pet's stats
## what it does:
- When you plug into power through the usb, it turns on the oled screen
- this brings a mini pet into the world
- there are two buttons on the board
      - one is used to show the pets stats like energy, sleep, love ,etc
      - one bring up a menu of 4 options, allowing you to choose options to boost certain stats + animation. One          option gives you the ability to go to a second menu which allows you to switch the avatar of your pet and         play music
- the mpu5060 tracks simply movement, this is how you can select options of the menu
- the dht11 checks for temp in this case for "specialised cutscenes"
## how to make:
- the gerber files(files telling companies how to make the pcb) are already placed in production, export them and send them to an online pcb maker (in this case i used pcbway or jlcpcb as its cheap). Warning be wary of tarrifs, customs and taxes before you order for your specific country
- buy all the components, they are all through holes so it should be easy to solder(you need to solder them)
- using an arduino ino editor, set it up for the xiao-esp32-C3 -the microcontroller we used here-  and download(or copy and paste the code into the editor upload it to the microcontroller.
## The board:
<img width="471" height="472" alt="image" src="https://github.com/user-attachments/assets/b658b68b-ea65-4f6c-9128-ee02b2b2c6f5" />

## The schematics:
<img width="724" height="514" alt="image" src="https://github.com/user-attachments/assets/f4331cdc-8976-40a3-bffd-8502e97ed1a7" />


## Bill of Materials

| Item | Qty | Supplier | Cost/item | Total cost | Link |
|---------|--:|------------------------|------:|------:|--------|
| MPU6050 | 1 | SZHJW Technology Store| $1.55 | $1.55 | [AliExpress](https://www.aliexpress.com/item/1005010057794277.html) |
| Keyboard switch | 1 | Dropshipping Daily Life Pro Store| $1.76 | $1.76 | [AliExpress](https://www.aliexpress.com/item/1005012157731141.html) |
| XIAO ESP32-C3 | 1 |ALL MY Store| $9.49 | $9.49 | [AliExpress](https://www.aliexpress.com/item/1005007084388623.html) |
| DHT11 sensor | 1 |SZHJW Technology Store| $1.06 | $1.06 | [AliExpress](https://www.aliexpress.com/item/1005010175387094.html) |
| Circuit board | 1 | JLCPCB | $10.00 | $10.00 | [PCBWay](https://www.pcbway.com/QuickOrderOnline.aspx) |
| Keyboard caps | 1 |SZElectronic Store| $2.36 | $2.36 | [AliExpress](https://www.aliexpress.com/item/1005010720096151.html) |

**Estimated component total: $26.22**

Estimated shipping is $0.00 , may vary in supplier.
