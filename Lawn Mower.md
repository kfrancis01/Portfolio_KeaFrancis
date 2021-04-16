## Lawn Mower </br>

<h3>Skills:</h3>
* C++ Programming </br>
* Arduino Sensor Integration </br>
* UART Communication </br>

<h3> Project Description:</h3>
<p>The objective was to systematically mow a lawn autonomously with minimal external
influence. Implementation of proper safety features, such as an emergency stop, were also
high priority.</p>

<p>As the second phase of the project, we were limited by some decisions made by the phase
one team. They had decided to use the MarvelMind triangulation system that included 4
beacons and a GPS tracker that was attached to the mower.</p>

<p>The MarvelMind was used to allow the mower to navigate autonomously within a 4 sided
polygon area. Beacons were placed on the four corners of the area. The beacons would
then triangulate the position of the mower. If the mower was within a close tolerance to
one of the beacons it would turn in a 90 degree angle. There were several checkpoints
where the rotary encoders would analysis the placement of the motors to make sure it was
moving as expected. The entire system created in the second phase included an Arduino,
rotary encoders, and Kangaroo motion controller.<p>
