# LANNA-Actam-Project

![](https://github.com/giuris/LANNA-Actam-Project/blob/main/screenshots/logo.png)

**Index**

- [LANNA-Actam-Project](#lanna-actam-project)
  - [Introduction](#introduction)
- [INTERFACE](#interface)
  - [Layout](#layout)
  - [Software involved](#software-involved)
- [FEATURES](#features)
- [INTERACTIVE MENU](#interactive-menu)
- [CONCLUSION](#conclusion)





## Introduction
As a project for the Advanced Coding Tools and Methodologies course we decide to create an educational keyboard that helps young students to learn the basics of notes and chords. 

Our keyboard can be played directly with your computer keys or using the mouse. Regarding to the minimal layout, we created it using Photoshop and Pixelmator.

In the upper part of the interface there is a screen in which animations will appear when the keys are pressed. In order to show to the user how a triad is composed, we create four buttons “MAJOR TRIAD, MINON TRIAD, AUGMENTED TRIAD, DIMINISHED TRIAD” that allows you to hear and see which notes make the triad chosen.

# INTERFACE

![](https://github.com/giuris/LANNA-Actam-Project/blob/main/screenshots/layout.png)

## Layout 
The  minimal layout presents the buttons NOTE and FREQ which have been created with Photoshop, while the piano keys and the logo “LANNA-GMA™” have been created with Pixelmator.
We obtained the background using the gradient fading property of the CSS programming language. 

## Software involved
This web application has been realized with the use of HTML, CSS and JavaScript languages and, thanks to the use of the Brackets editor, we were able to write every part of the code and collect everything here on GitHub.


# FEATURES
Our project is based on HTLM,CSS and JS code. With HTML we manage the structure of the interface, in fact we have used it to insert in the code the images to create the layout. With a combination of HTML and CSS we create the animations, the triad’s buttons and the menu. JavaScript has an important role in the project, because it is used for the dynamic interactions between the keyboard and the user and between different part of the project. In fact JS allows us to link the piano keys to sounds and animations.

![](https://github.com/giuris/LANNA-Actam-Project/blob/main/screenshots/tastieraFREQNOTE.png)

1. NOTE button to see the animation of the note related to the pressed key;
2. FREQ button to see the sinusoid related to the played key;
3. Keyboard. You can play it with your computer or clicking the single keys with your mouse or trackpad.


### NOTE button
Pressing the NOTE button you will be able to see the animations of the notes that you are playing on the right of the display. 
Pressing the button it changes its color, from blue (unpressed) to red.

Here is an example:

![](https://github.com/giuris/LANNA-Actam-Project/blob/main/screenshots/notee.png)



### FREQ button
The FREQ button allows to see the swing of the pure tone related to the played note to the left of the screen. In fact, every note has its related frequency, and the graph shows a different sinusoid for each one.
Like the NOTE button, Pressing the FREQ one it changes its color, from blue (unpressed) to red.

Here is an example:

![](https://github.com/giuris/LANNA-Actam-Project/blob/main/screenshots/freqq.png)


###### Other features
- When NOTE and FREQ modes are enabled, the user is able to see both the animations of the played notes and their frequencies on the display of the keyboard. 


### Chords

![](https://github.com/giuris/LANNA-Actam-Project/blob/main/screenshots/tastieraCHORDS.png)

A triad is a chord with three notes that can be set as thirds because their pitches work together. Each note in a triad bears a specific label. The bottom note is called the root, the middle note is called the third, and the top note is called the fifth. 

The four main types of triads that exist in music are called Major (1), Minor (2), Augmented (3) and Diminished (4). 

To produce the various chords we have chosen to use all 4 different types of triads. The functioning is very intuitive: If the user wants an example of Major Triad (and it is the same for the other triad’s buttons), he/she has to press the corresponding button and after choose a note and play it. 

The keyboard allows to listen the third and the fifth notes associated to the one played. At the same time, the animations referring to the three notes of the triad will appear on the screen.


# INTERACTIVE MENU
The application has an animated menu in which, by clicking on it, we find the items Tutorial, Example and Contacts.

![](https://github.com/giuris/LANNA-Actam-Project/blob/main/screenshots/menu.png)

In Tutorial there is a simple explanation of how to play and what the various buttons do.

The Example section shows a simple description of what a triad is and explains how to make simple chords.

In the end, by clicking on Contacts it is possible to reach us out.


# CONCLUSION
This project may have several additional features if developed over time, like the MIDI support, the possibility to change the frequency range and adding potentiometers and new scales.

For now, it has the basis to become a usable application in schools to teach the fundamentals of music theory, and the ideal would be to install this software on each student's computer!

------------------------------------

Finally, here you can find a demo video.
`<link>` : <https://youtu.be/O90AwhouFe4>
