# Assignment for implementing a simple IoT architecture with Node-RED and Ubidots

<ol>
<li>
Modify the flow <code>assignment.json</code>  to implement a Node-RED server that behaves as follows:
<ul>
<li>It acquires Rpi3 sense hat data from the broker <code>test.mosquitto.org:1883</code>, with topic <code>unige/dibris/room328/sensehat</code>;</li>
<li>It computes the absolute value of the difference between the last two temperature measurements;</li> 
<li>It sends to the same broker with topic <code>unige/dibris/room328/display</code> the Rpi3 command to set all display pixels to color red, if such a value is greater than 1, to green, otherwise.
</ul>
  
<b>Hint:</b> use a <code>join</code> node.</br>
</li>

<li>
Implement the same functionality by exploiting Ubidots derived variables and events with web-hooks. 
</li>
</ol>
