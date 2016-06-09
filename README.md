<h3>Toy Robot Simulator</h3>
<img src = "https://github.com/jeff1978/Toy-Robot-Simulator/blob/master/robot.jpg" align = right>
This C# .NET solution is a simulator of a toy robot that moves on a tabletop. The development of this project is driven by unit tests. These are included in this repository. A full requirements specification can be found here:<br><a href = "https://github.com/jeff1978/Toy-Robot-Simulator/blob/master/ToyRobotSimulator/App%20Specification.txt">App Specification.txt</a>
<br><h4>Design Patterns Used</h4>
<b>Command :</b>
<br>A class is used to represent user input data, validate it and return appropriate object types or error messages. The class has no dependencies and it's methods are unit tested before being set to work with the rest of the application.
<h4>Instructions</h4>
Follow the on screen instructions to place a robot and move it around the board. To exit the application at any time type EXIT (this must be in uppercase)
<h4>Valid commands</h4>
PLACE X,Y,FACING<br>This puts the toy on the table in position X,Y and facing NORTH, SOUTH, EAST or WEST. If the toy is already placed, issuing another valid PLACE command will place the toy in the newly specified location. MOVE This moves the toy one unit forward in the direction it is currently facing. LEFT This rotates the toy 90 degrees to the left (i.e. counter-clockwise) without changing the position RIGHT This rotates toy 90 degrees to the right (i.e. clockwise) without changing the position. REPORT This announces the X,Y and direction of the toy by printing to the console. EXIT This closes the application.
<h4>Installing and Running</h4>
The application runs in a single executable file. For convenience the file can be downloaded from here: <a href = "https://github.com/jeff1978/Toy-Robot-Simulator/blob/master/ToyRobotSimulator/bin/Debug/ToyRobotSimulator.exe">\ToyRobotSimulator\bin\Debug\ToyRobotSimulator.exe</a> The executable file can be opened by double clicking it. The user can follow instructions on the console and also use it to type their input.
<h4>Development Notes and Acknowledgements</h4>
A full list of information sources can be found here: <a href = "https://github.com/jeff1978/Toy-Robot-Simulator/blob/master/ToyRobotSimulator/Acknowledgements.txt">\ToyRobotSimulator\Acknowledgements.txt.</a>
<h4>Supported operating systems</h4>
Toy Robot Simulator should run on any Windows operating system. It has been tested on Windows 10 Home Edition 32-bit.
<h4>Issues</h4>
Existing issues can be logged on the <a href = "https://github.com/jeff1978/Toy-Robot-Simulator/issues">Issues page.</a>
<h4>Future Developement Work</h4>
The the design and use of the interfaces requires refactoring from their current working form.<br>The classes for console checking also need to be checked for possible refactoring.
<h4>Licence</h4>
Toy Robot Simulator is licensed under the GNU Lesser General Public License v.3.0
<h4>Why the LGPL?</h4>
The GPL is specifically designed to reduce the usefulness of GPL-licensed code to closed-source, proprietary software. The BSD license (and similar) do not mandate code-sharing if the BSD-licensed code is modified by licensees. The LGPL achieves the best of both worlds: an LGPL-licensed library can be incorporated within closed-source proprietary code, and yet those using an LGPL-licensed library are required to release source code to that library if they change it.
