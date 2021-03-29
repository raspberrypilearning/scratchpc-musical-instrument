## Connect and Code your instrument
In this step, you will connect the wires from your musical instrument to the pins on the Raspberry Pi, then create some code in Scratch to make it playable.

Now that you have finished making the physical components of your instrument, the next step is to link each separate contact to your Raspberry Pi’s GPIO pins. 

In this example, I have connected the drums to Pins 2,3,4,14 and 15 as they are the lowest numbers available and therefore easy to remember. Because my drumsticks are the **common ground** for all of my circuits, I have connected them to ground pins 6 and 9.  

--- task ---
Take each one of the jumper cables connected to your instrument and attach them to your Pi using the GPIO pins. Use the pinout diagram here:
[The Raspberry pi pinout shows the forty GPIO pins laid out with the odd numbered pins on the left and even pins on the right.](image/GPIO-Pinout-Diagram-2.png)
--- /task ---

Now that your instrument is wired up to the Pi, we need to write some code to make it work. The most basic version of the instrument is very easy to program, allowing you lots of options for customizing what happens on screen and the sounds your instrument will make.

--- task ---
Open a blank project in Scratch and add the Raspberry Pi Simple Electronics extension to your project.
[The extension menu is theblue square at the bottom left of the Scratch workspace](image/extension.jpg)
[The Simple Electronics extension button](image/GPIOext.jpg)
--- /task ---

--- task ---
For each of the GP pins you have connected, add a simple block of code that activates when the button is pressed, and plays the required sound.

The most basic code required to have a playable music instrument is this:

```blocks3
When Button (2) pressed :: extension hat
Start sound [Low Tom v]
```
--- /task ---

Whether you use a different sprite for each contact or a single sprite with all of your code on it doesn't matter, unless you want to do something interesting on screen. In the drum kit project, the sprites change costume when you strike each drum. In the violin project, there is no screen component (but there easily could be!)

--- task ---
Have fun playing your instrument! 
--- /task ---

--- save ---
