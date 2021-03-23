## Make your instrument

By the end of this step, you will have designed and built your instrument's physical components - the body, contacts and wiring. 

The first step in making a musical instrument is to think about what kind of instrument you’d like to make, and what is possible. It’s important to consider *how* your instrument will be played to determine whether it will work or not.

Our instrument will be based on ‘buttons’ like the ones you used in the challenge projects; while you might use actual buttons, you could also use any sort of conductive contacts that will close a circuit (like two pieces of aluminium foil). 

A really neat way to make a lot of circuits that are all interactive is to use the player as the ground - that way whatever contacts they touch, they will be closing an open circuit and triggering our set event. Even better: we only need to wire up one ground pin for our whole project, halving the number of wires we’ll need to mess about with!

In this example, I’ll be making a drum kit. I chose a drum kit because it’s really easy to have the drumsticks be the ground contacts that the player uses to make the sounds. That way, whatever drum the player touches with the stick will close that circuit, triggering the drum sounds. You can make whatever instrument you like, but you will need to consider how your player will close the contacts or press the buttons. (Using *actual* buttons like the ones you can get from electronics shops might be a better option for instruments like pianos or guitars.)

--- task ---
Consider how many pins you might need to close your circuits - it will likely be one GPIO pin for each different sound you want to make.

In the example drum kit there is a kick drum, a floor tom, a snare drum and a cymbal - that’s four drums. In order to make the drum kit work, I’ll need four GPIO pins (one for each drum) and one or two ground pins (depending on if I want one or two drumsticks for the player to hold.) 
--- /task ---

--- task ---
Look at the materials you have available, and work out how you will create the physical parts of your instrument. You might want to cut a shape out of cardboard, or use existing items and stick them together to make the body of your instrument. To make my drumkit, I used some simple items I found around the workshop and just covered them in foil. For the guitar and violin, I used some old packing foam I had lying around. Be creative in recycling materials for your instrument!
--- /task ---

Whatever you use, make sure that you can connect your aluminium foil contacts in the right places and that it is of a manageable size to play - trying to play a *tiny* guitar might be a bit frustrating!

Once the instrument body is made, you will need to add foil contacts to it for the player to interact with. One way is to use small pieces of foil which you glue onto the instrument in the right places. A drumkit will need drumsticks as well - here you can see how I wrapped pencils in foil and taped them up, making sure the wire is touching a good amount of the foil.

[Wrapping simple home items in aluminium foil and adding a wire taped to the metallic surface will provide a good contact for a drumkit](image URL)

To make the drum kit here, I used aluminium foil to wrap; a toilet roll, a roll of tape, a jar lid and a piece of cardboard cut into a circle. Because the drums in the example are completely covered in conductive foil, we just taped the wires to the side. 

--- task ---
Take each of your f-f jumper cables and remove *one* of the connectors by pulling it off the end. It might take a little strength to manage, but don’t worry - we’re going to use this exposed end to attach to your instrument’s contacts using tape. Make sure to attach the exposed ends of your wires *underneath* the foil contacts, ensuring they have a good amount of connection to the foil and glue them down well. You can also secure them with strong tape, if you have some.

--- /task ---

--- task ---

--- /task ---



--- task ---

Once your instrument body is complete, think about how your player will close the circuits - what will they hold or wear as a contact to close the circuit, or does your instrument have the player contacts included as part of itself, like a button? 

--- /task ---

[A pencil wrapped in foil with a wire taped to the end makes an excellent drumstick.](imageURL)

In this example the player holds the drumsticks, which are simply pencils wrapped in aluminium foil, and connected by a wire to a ground pin, which closes the circuit and activates our drum. 

Other kinds of instruments will need clever solutions to this problem - a cardboard piano may use foil buttons for keys like you made in previous projects, or have some type of contact the player can wear on their fingers instead of holding drumsticks, for example. 

--- task ---
Create your instrument’s interface by making something that the player can touch to the instrument contacts and close the circuits you have created.
--- /task ---

In the next step, we will connect our instruments to the GPIO pins and code them to make sounds and animations on screen!


--- save ---