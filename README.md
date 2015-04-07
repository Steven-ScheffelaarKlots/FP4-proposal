# Project Title: RacketSynth
### Problem Statement
The RSound sound engine is a powerful tool. It allows for the representation, reading, writing, playing and manipulation of
sounds. Unfortunately, it is rather complicated and difficult to use. Our plan is to simplifiy it's use by wrapping it with
a graphical user interface. This will be done using the Racket GUI Toolkit. 

We would also like to create a playable instrument using the Racket GUI Toolkit and RSound. Users can use their keyboard and the
interface mentioned above to control sounds. 

### Problem Analysis
We will need to take the difficult process of creating particular types of sound waves at particular frequencies and abstract it
in to simple procedures. These procedures will then be called by our user interface which will present a clear, obvious way to
create sounds. 

This will allow users to more expressively control the RSound library. 

### Data set or other source materials
The only things we plan to use that isn't code we've written ourselves is the GUI Toolkit and RSound. 

### Deliverable and Demonstration
The final version of our project will, ideally, have an interface for creating various types of sound waves at selected
frequencies. These could be sine, sawtooth, square, or pulse waves. The frequencies will have reasonable upper and lower limits
in order to protect the user's audio hardware and their ears. If we have time, we would like to add the layering of multiple
sounds and differnet values. Theoretically, these layers could be used to synthesize any sound. 

We will also create a way for the frequencies to be set by mapping keyboard inputs to particular values. This will allow a user
to use their computer's keyboard as a playable instrument. 

We will show all of the working freatures in our final demonstration. 

### Evaluation of Results
As the main purpose of this assignment is to make RSound easier to use, (though will a reduced functionality), we will conduct
brief usability tests. This will consist of asking friends, both with substantial experience with computers and without, to use
our program and describe the experience. We may also give them a short list of simple tasks to complete. Also, we will have the
program tested by a keyboard or piano player to see if they can actually get some music out of the program. 

## Work Plan and Schedule
Explain how you will go from proposal to finished product. Write your general plan here. 
There are three deliverable milestones to explicitly define, below. The nature of deliverables depend on your project, but may include things like processed data ready for import, core algorithms implemented, interface design prototyped, etc. 

You will be expected to turn in code, documentation, and data (as appropriate) at each of these stages, so take care in writing concrete steps for your schedule. 

In this general plan, and in the deliverables below.

### First Milestone (04-13)
We would like to have the user interface completed, though with very little actual functionality. However, any user actions in
the interface shoud trigger special test events so that we know the user actions are being detected. This could be a test as
simple as displaying a string in the interpreter when the user presses a particular button. 

This will not yet include any of the keyboard instrument functionality. 

### Second Milestone (04-21)
The user interface should now be able to call procedures that create sounds according to the user's specifications. The sound
creation should be achieved through simple, expressive procedure calls. 

We will also have the interface for the keyboard instrument working. As we will need to take keyboard input, a good test would 
be echoing whatever key is pressed in the interpreter, again, to make sure that user input is being properly detected. 


## Group Responsibilities
Here each group member gets a section where they, as an individual, detail what they are responsible for in this project. Each group member writes their own Responsibility section. Include the milestones and final deliverable.

### Susan Scheme
will write the....

### Leonard Lambda
will work on...

## Proposal Presentation Link
insert your google presentation public link here, so with one click it will open up in the browser and you can present.

<!-- Links -->
[piazza]: https://piazza.com/class/i55is8xqqwhmr?cid=453
[markdown]: https://help.github.com/articles/markdown-basics/
