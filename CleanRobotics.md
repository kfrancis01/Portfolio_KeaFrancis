## Description
<p> The TrashBot is a trashcan that utilizes A.I. to sort waste, recycling, ect. <p>

## Skills
* Particle
* Electron
* C/C++
* GitHub

## Personal Role/ Contributions
* Remote Reset Feature
<p>Allow user to reset Particle while there is a WiFi connection<p>
  
* UART Connection
Communication between Particle and Raspberry Pi

* Remote trigger
<p> Allow user to activate light gate for testing TrashBot<p>
  
* Application WatchDog
<p>Software reset whenever the code stalls for a predetermined length of time<p>
  
* AccelStepper

## Library Code Update
* Have motor find zero after triggering a magnetic limit switch
* Motor accelerate to a start point then move to specific position and back to start based on state machine
