# Voice-Controlled-Robot-Car-Using-Arduino-Bluetooth-and-L293D-Motor-Driver
<h1>🤖 Voice Controlled Robot Car using Bluetooth</h1>

<p>This project demonstrates how to control a robot car using voice commands via Bluetooth. The system consists of an <strong>Arduino Uno</strong>, an <strong>HC-05 Bluetooth module</strong>, an <strong>L293D motor driver</strong>, and two <strong>DC motors</strong>. The user can send voice commands such as <code>forward</code>, <code>backward</code>, <code>left</code>, <code>right</code>, and <code>stop</code> to control the car.</p>

<h2>📦 Components Required</h2>
<ul>
  <li>Arduino Uno</li>
  <li>HC-05 Bluetooth Module</li>
  <li>L293D Motor Driver Module</li>
  <li>2 DC Motors</li>
  <li>2 × 9V Batteries</li>
  <li>Jumper Wires</li>
</ul>

<h2>📈 Circuit Diagram</h2>
<p><em>Connect all components as per the circuit diagram.</em></p>

<h2>⚙️ Working Principle</h2>
<ol>
  <li>The HC-05 Bluetooth module receives voice commands from an Android app.</li>
  <li>The Arduino reads the incoming command via the Serial communication.</li>
  <li>Based on the received command, the Arduino sets the corresponding motor driver pins HIGH or LOW.</li>
  <li>The L293D motor driver controls the two DC motors accordingly.</li>
</ol>

<h2>🧠 Motor Control Logic</h2>
<ul>
  <li><code>forward</code>: Both motors move forward.</li>
  <li><code>backward</code>: Both motors move backward.</li>
  <li><code>left</code>: Left motor stops, right motor moves forward.</li>
  <li><code>right</code>: Right motor stops, left motor moves forward.</li>
  <li><code>stop</code>: Both motors stop.</li>
</ul>

<h2>🚀 How to Use</h2>
<ol>
  <li>Connect all components as per the circuit diagram.</li>
  <li>Upload the Arduino code.</li>
  <li>Pair your phone with the HC-05 module using a Bluetooth terminal app.</li>
  <li>Send commands (<code>forward</code>, <code>backward</code>, <code>left</code>, <code>right</code>, <code>stop</code>) via the app.</li>
  <li>The robot moves accordingly.</li>
</ol>


📬 Author: Jitendra Sharma 📧 Email: jitendrasharma7409@gmail.com 🔗 Follow for more: https://github.com/jitendrasharma-eng?tab=repositories | www.youtube.com/@ECodeLab-mv4jm | linkedin.com/in/jitendra-sharma-484072248 [https://www.linkedin.com/in/jitendra-sharma-484072248?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BdRzhEpUKQSqQh6%2Fm6UayRw%3D%3D]
