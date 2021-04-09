# ISI-CDAC Illusion experiments portal

This is a new rewrite of the illusion experiments done in psychopy and psychopy.js. This is being developed to be deployed on servers.  

Innitially the idea was to develope a python package that can be distributed to allow other people to conduct the experiment. The one click install thing became very difficult to implement due to dependency issues. The abaondoned code base can be accessed [here.](https://github.com/mm-crj/geomexp) 

Then this idea changed to a web based implementation. The python library previously used to do the experiments [Psychopy](https://www.psychopy.org/) had publised a web verion with easy code block translation to JS. This library was called [Psychopy.js](https://github.com/psychopy/psychojs). The problems that arose were manyfold. Firsty the code base of psychopy.js is under active development and is not stable. It aslo has the most basic features of the pyhton counterpart, so many stuff cant be implemented on the web verion. This is not a problem of the web platform, but a limitation of the library itself. And then ther are hosting  and experiment performing charges if we use the [Pavlovia](pavlovia.org/) hosting solution. Its good for people with limited technical expertise and has a resonable fee, but for our purposes we decided to write the thing from scratch again and abondon the PSYCHOPY libary. 

This time the idea is to design the experiments on the DJANGO platform with our own user management and data handling. 
