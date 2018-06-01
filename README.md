# Nintendo-Switch-JoyCon-Hack
Hardwiring a push button in a JoyCon to grant debug/bootloader


                     ██╗ ██████╗ ██╗   ██╗ ██████╗ ██████╗ ███╗   ██╗    ██╗  ██╗ █████╗  ██████╗██╗  ██╗                     
                     ██║██╔═══██╗╚██╗ ██╔╝██╔════╝██╔═══██╗████╗  ██║    ██║  ██║██╔══██╗██╔════╝██║ ██╔╝                     
                     ██║██║   ██║ ╚████╔╝ ██║     ██║   ██║██╔██╗ ██║    ███████║███████║██║     █████╔╝                      
                ██   ██║██║   ██║  ╚██╔╝  ██║     ██║   ██║██║╚██╗██║    ██╔══██║██╔══██║██║     ██╔═██╗                      
                ╚█████╔╝╚██████╔╝   ██║   ╚██████╗╚██████╔╝██║ ╚████║    ██║  ██║██║  ██║╚██████╗██║  ██╗                     
                 ╚════╝  ╚═════╝    ╚═╝    ╚═════╝ ╚═════╝ ╚═╝  ╚═══╝    ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝
                                                                                                XxWiReDxX

This is a tutorial on how to hack the Nintendo Switch JoyCon to grant the user escalated access for Custom Firmware *(CFW)* and HomeBrew. I created this hack and tutorial to help users and myself to easily use the Nvidia Integra exploit. Current hacks require a user to use a jig tool by inserting it in the right JoyCon slot, using aluminum on a JoyCon and inserting it in the right JoyCon slot, or shorting and breaking the right JoyCon pins, every time a user wants to boot into bootloader. This can be cumbersome  and annoying when switching between stock firmware and custom firmware, and this hack is to make it a seamless operation for the user.

Also, currently all exploits require the user to use the Nvidia Integra exploit every time the Nintendo Switch is shutdown or rebooted, and this can be a burden if you are using a purchased or homemade tool. By modding your controller easily and once, you now will have a hassle-free method of getting into the bootloader. This will come in handy with Xecuters USB C Modchip (https://sx.xecuter.com/), for a fast and easy CFW launch. A list of resellers can be found Here (https://team-xecuter.com/where-to-buy/).

# Team Xecuter
[![Team Xecuter](https://i2.ytimg.com/vi/Z8TSo3lIK00/hqdefault.jpg?sqp=-oaymwEXCPYBEIoBSFryq4qpAwkIARUAAIhCGAE=&rs=AOn4CLBNXbw_M2KmwchKGBKpj2bhJTjzRw)](https://www.youtube.com/embed/Z8TSo3lIK00)

## * Works on every Switch
  * SX OS Works with every Nintendo Switch out there. On every firmware version!
## * Play all Games!
  * With SX OS you can play all your favorite games straight off of the microSD card inserted into your Nintendo Switch.
## * Homebrew Games & Apps
  * Using SX OS homebrew menu launcher you can enjoy all the quality games and software by independent developers.
## * Continued Support
  * Team Xecuter is always actively working to bring more exciting functionality to SX OS.
## * Backwards Compatible
  * Using the SX OS Launcher you can easily boot into the normal Nintendo Switch firmware to enjoy your original games.


# How it Works / How to Use
If your momentary switch is installed properly, to enter the bootloader you need to insure your device is powered off, and then press and hold the installed button and the volume up button. While holding these 2 buttons power the device on with the power button. *(If you see the Nintendo logo, it did not boot properly. If it booted to a blank black screen, congratulations you have access to the bootloader.

# Starting Notes
  1. Take your time. Do not rush through the project. The JoyCon hardware is sensitive *(Ribbon Cables can come loose if pulled hard)* and the components are small.

  2. Measure twice and Mod once. Make sure the placement of you button is in a location free of the existing hardware to insure the device closes back up again.

  3. A little goes a long way. When you are gluing or securing your button, use just a small amount of adhesive to prevent freezing up the momentary button.

# Recommended Supplies
  1. Adhesive
     * Hot glue and Hot glue Gun or
     * Liquid-Plastic Welding Tool Pen (http://a.co/b2NHN5n). I have not tested this yet.

  2. 6x6 Push Button Switch (http://a.co/0qSeANA). For $10.00 it is worth getting various button heights. 

  3. Wire and Connector *(I recommend a connector to easily connect and disconnect from the button)* .
      * Female to Female 4 Inch Solderless Ribbon Dupont Jumper Wires *(This is what I used)* . or
      * Wire and solder
    
  4. Soldering Iron *(Try and use a fine tip soldering iron for lower heat and better control)* & Solder.

  5. Drilling Device
     * Dremel with a bit slightly larger than the button of the switch or
     * Drill with a bit slightly larger than the button of the switch or
     * A Prison shank with a tip slightly larger than the button of the switch. 
  
  6. Shrink Tubing (http://a.co/6SDwGox). I recommend getting a kit of various sizes at $7.99
  
  7. Heat Gun or Lighter *(Used for the Shrink Tubing)* .

  8. Solder Flux *(Optional, but it helps solder flow)* .
  
  9. Security Screw Driver Set *(YBit & Phillips used to open the JoyCon)* . I used my own set, but here is a link to one (http://a.co/aoYPtmz).
  
  10. Right JoyCon controller. *(This will not work with the left JoyCon)*

#### Disclaimer
Please keep in mind that I am not responsible for any issues caused by this modification. With that said, follow instructions and you should be okay.

# HOW TO
### Prep the Jumper/Connector Wire
#### On my project I used a female jumper cable *(Image 1 - link above)* .

![20180521_200503](https://user-images.githubusercontent.com/25444976/40401018-3c1a21a4-5e0a-11e8-93da-5d1d1c382f54.jpg)
***(Image 1 - Female Jumper)***

1. Remove the female housing from the jumper. I used a small Philips screwdriver to get under the locking tab to lift it up and free it from the crimp connector. Lift the tab up and slide the connector off *(Images 2-4). The housing is to long for the pins on the switch to reach the metal connector, so it must go!* Do this twice. You will need two wires.

![20180521_200626](https://user-images.githubusercontent.com/25444976/40401474-2745544a-5e0c-11e8-9940-615d616e4f2f.jpg)
***(Image 2 - Lifting the Locking Tab)***

![20180521_200647](https://user-images.githubusercontent.com/25444976/40401475-276b45ce-5e0c-11e8-9912-44626dc0587d.jpg)
***(Image 3 - Removing the Jumper Housing)***

![20180521_200654](https://user-images.githubusercontent.com/25444976/40401473-27252094-5e0c-11e8-8ff0-b058eec01b8b.jpg)
***(Image 4 - Jumper Housing Removed)***

2. Measure the protective shrink tubing before cutting *(Image 5)* .

![20180521_200832](https://user-images.githubusercontent.com/25444976/40401911-90f2ffe4-5e0e-11e8-86d7-a3c25a17ee24.jpg)
***(Image 5 - Measuring the Shrink Tubing)***

3. Cut the shrink tubing x2 for the two wires *(Image 6)* .

![20180521_200902](https://user-images.githubusercontent.com/25444976/40401915-953713ba-5e0e-11e8-9670-ef948f10d4ac.jpg)
***(Image 6 - Cut Shrink Tubing)***

4. Slide the shrink tubing around the crimp connector, covering all exposed metal, and apply light heat with a heat gun or lighter to shrink the tube around the connector. It should look like *(Image 7)* .

![20180521_201006](https://user-images.githubusercontent.com/25444976/40401986-e0e50a7e-5e0e-11e8-847b-8af78140531a.jpg)
***(Image 7 - Heated Shrink Tubing)***


### Prep the Momentary Switch
#### On my project I used a simple pushbutton momentary switch *(Images 8-9 - link above)* .

![20180521_201048](https://user-images.githubusercontent.com/25444976/40402216-fb456c00-5e0f-11e8-9774-13dfcb6344be.jpg)
***(Image 8 - Momentary Switch - Top)***

![20180521_201058](https://user-images.githubusercontent.com/25444976/40402219-ff1b1bb8-5e0f-11e8-9ba9-86237d797998.jpg)
***(Image 9 - Momentary Switch - Side & Bottom)***

1. Verify which posts you are going to use. Most of these switches use the two side post in pairs, resulting in two circuit paths for one switch *(Essentially you can control two devices with one switch)* . If your switch came with a wiring diagram, refer to that, or you can always do a connectivity test with a multimeter *(Image 10)* or even a battery & led.

![20180521_201143](https://user-images.githubusercontent.com/25444976/40402372-cb75fe80-5e10-11e8-8912-9fb90fab46ee.jpg)
***(Image 10 - Multimeter and Momentary Switch)***

2. Remove unused side posts to prevent unnecessary exposure *(Image 11). (You can bend them back and forth until they break, which is fairly easy)* .

![20180521_201336](https://user-images.githubusercontent.com/25444976/40402413-1573ca3a-5e11-11e8-8966-06ff8f42a220.jpg)
***(Image 11 - Momentary Switch with Side Posts Removed)***

3. Straighten the remaining posts out to the side as seen in *(Image 12). (Be very careful to not break them. Bend them in warm conditions if possible and slowly. Try to only bend them once)* .

![20180521_201423](https://user-images.githubusercontent.com/25444976/40402418-1cf99f96-5e11-11e8-8c75-4b1884be0466.jpg)
***(Image 12 - Momentary Switch with Side Posts Bent Straight)***

4. Test the connection with your fabricated jumpers to make sure they fit right. *(Image 13)*

![20180521_201630](https://user-images.githubusercontent.com/25444976/40402577-1be3b6f4-5e12-11e8-96ea-5f20ff953b23.jpg)
***(Image 13 - Momentary Switch Connected to Jumpers)***


### Prep the JoyCon Back

1. Remove the 4 YBit Screws from the back of the JoyCon. *(You may have to press hard and turn slowly to initially break them free. Be very careful not to strip them)* . Set them in a secure location so you do not lose them and then carefully remove the back as in *(Image 14)* .

![20180521_202227](https://user-images.githubusercontent.com/25444976/40402950-415bd1d0-5e14-11e8-89c4-18ff00567901.jpg)
***(Image 14 - JoyCon Back Removed)***

2. Use a Phillips screwdriver to remove the JoyCon slide connector board in *(Image 15)* and then carefully slide it off the main housing without disconnecting the ribbon cables *(It should just fold over)* . I fully disconnected mine as seen in *(Image 15)* , but I do not recommend it.

![20180521_202255](https://user-images.githubusercontent.com/25444976/40403500-ee78291a-5e17-11e8-8689-b9c8fe7297f4.jpg)
***(Image 15 - JoyCon Slide Connector Board Fully Removed)***

3. Mark the back of the JoyCon controller to where you are going to drill the button hole. Used the switch to help find the proper location *(Image 16). (I recommend tight to the rumble housing, the rectangle box, all the way to the back before the case curves)* . Once you have marked your drilling location, drill the whole in the back of the JoyCon *(Use the low speed setting, and drill slow. You do not want the plastic to melt)* . In *(Image 17)* I drilled my hole a little to far too the left, but it still works.

![20180521_211826](https://user-images.githubusercontent.com/25444976/40403120-534f7a62-5e15-11e8-85fe-a4d115c24fa0.jpg)
***(Image 16 - Using Momentary Switch to Find the Drill Location)***

![20180521_211812](https://user-images.githubusercontent.com/25444976/40403137-70f8cb2c-5e15-11e8-8120-7536c5bb954f.jpg)
***(Image 17 - Drilled Hole on the Back of the JoyCon Controller (A Little to Far to the Left))***

4. Insure your momentary switch button properly fits in the drilled hole. If it does not slowly increase the hole size with a larger bit or sandpaper.


### Connect the Momentary Switch to the JoyCon Back
#### On my project I used a hot glue gun. I really wanted to give the recommended UV glue a go, but I was currently out.

1. Place your momentary switch in the intended place orientated with the pins toward the JoyCon slide connector board. While holding it in place, apply a small amount of adhesive to the most exposed and easiest accessed side. Hold until set. Once the momentary switch is tacked in place, continue to secure the rest of the sides like in *(Image 18)* .

![20180521_215216](https://user-images.githubusercontent.com/25444976/40403554-3840dab0-5e18-11e8-84c6-8f896e62851e.jpg)
***(Image 18 - Momentary Switch Secured with Hot Glue)***


### Connect the Jumper Wires to the JoyCon Slide Connector Board

1. Measure the length of wire you need to cut off of your jumper wires to properly connect the JoyCon Slide Connector Board
 to the momentary switch. *(I recommend leaving just a little bit of room for error)* . Once you have your measurement, cut your wire and strip the ends exposing just a mm long *(This will reduce the error of over exposed wire shorting)* .
 
2. Prep your wire to be soldered to the JoyCon Slide Connector Board by pre-soldering the wire as seen in *(Image 19). (I use flux to help the solder flow, but it is especially useful when soldering the jumper wire to the JoyCon board)*

![20180521_202047](https://user-images.githubusercontent.com/25444976/40403819-f154fdbe-5e19-11e8-9611-9ead4324185c.jpg)
***(Image 19 - Jumper Wire with Soldered Ends)***

3. Find the locations on the JoyCon Slide Connector Board that you are going to solder to. I used a voltmeter to find the solder posts for pins 1 & 10 *(Images 20-21)* , which will be what we will solder to.

![20180521_202549](https://user-images.githubusercontent.com/25444976/40404025-324763f6-5e1b-11e8-994f-669c4cae5a57.jpg)
***(Image 20 - Testing Pins to Find the Associated Solder Posts)***

![20180521_202307 2](https://user-images.githubusercontent.com/25444976/40404058-604cf5fe-5e1b-11e8-9b20-58a55470f75a.jpg)
***(Image 21 - Solder Posts for Pins 1 & 10 Circled in Red)***

4. Solder the jumper wires to the located solder posts with a soldering iron like in *(Images 22-23) (I recommend using flux). (Be very cautious of the ribbon cable and plastic and only using the soldering iron for short bursts to prevent burning or melting)* .

![20180521_203557](https://user-images.githubusercontent.com/25444976/40404253-71dd4c96-5e1c-11e8-9c3c-955b05bd98ec.jpg)
***(Image 22 - Jumper Wires Soldered to the JoyCon Slide Connector Board)***

![20180521_210507](https://user-images.githubusercontent.com/25444976/40404266-807c25f6-5e1c-11e8-9c85-7ce62830b093.jpg)
***(Image 23 - Jumper Wires Soldered to the JoyCon Slide Connector Board)***


### Connect and Close Everything Up

1. Connect the jumpers to the momentary switch and then screw the JoyCon Slide Connector Board back to the JoyCon back plate as seen in *(Image 24)* .

![20180521_215440](https://user-images.githubusercontent.com/25444976/40404381-148d529c-5e1d-11e8-95cd-d2b28838c76d.jpg)
***(Image 24 - JoyCon Slide Connector Board Connected to the Momentary Switch and JoyCon Back)***

2. Button the JoyCon controller back up. It may take some playing around with to close them together, so be patient. It should never take excessive force to close them together. If you cannot close them look to see if there is something catching and make the movements or adjustments needed. *(I needed to trim some hot glue and slide the wires as close to the rumble pack box as I could)* . Once you have it all clamed together, re-install the 4 security screws you placed off to the side.

# Congratulations

![20180522_000710](https://user-images.githubusercontent.com/25444976/40404723-ecc259d6-5e1e-11e8-9c85-40488424fda3.jpg)
![20180522_000702](https://user-images.githubusercontent.com/25444976/40404727-ee9fb35c-5e1e-11e8-8915-c330e910feb2.jpg)
