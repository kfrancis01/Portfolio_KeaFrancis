<h1>CleanRobotics: TrashBot</h1></br>

<h2> Description</h2>
<p> The TrashBot is a trashcan that utilizes A.I. to sort waste, recycling, ect. <p>

<h2> Skills </h2>
<p>* Particle </p>
<p>* Electron </p>
<p>* C/C++ </p>
<p>* GitHub </p>

<h2> Personal Role/ Contributions</h2>
* Remote Reset Feature
    <p>Allow user to reset Particle while there is a WiFi connection<p>
  
* UART Connection
    <p>Communication between Particle and Raspberry Pi<p>

* Remote trigger
    <p> Allow user to activate light gate for testing TrashBot<p>
  
* Application WatchDog
    <p>Software reset whenever the code stalls for a predetermined length of time<p>
  
* AccelStepper

<h2> Library Code Update</h2>
<p>* Have motor find zero after triggering a magnetic limit switch</p>
<p>* Motor accelerate to a start point then move to specific position and back to start based on state machine<p>
