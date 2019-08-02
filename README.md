# ECE440-Project

PLEASE NOTE: This configuration has many moving parts and has only been confirmed to work on Graham's home PC running Windows 10 and Python 3.7.4. Any attempts to run this project on a Linux machine, a machine with insufficient CPU power, or on an older version of Python will likely encounter unforeseen issues.

That said, if any issues do arise, please email Graham at gg12gg@shaw.ca

We used two non-standard Python libraries when creating this project:

1. Numpy (for mathematic functions and array handling)
2. Bottle (used by the snake to host itself so it can respond to the Battlesnake engine)

Both of these can be installed by running "pip install numpy" and "pip install bottle" once Python 3.7.4 has been installed.

Instructions for running the project code:

1. Open a Powershell window (shift right click in the Windows 10 file browser -> Open Powershell window here) in the same directory as the engine executable. 
2. Enter the command "./engine"
3. Open enemy-snake/app and open a Powershell window there
4. Enter the command "python main.py"
5. Return to the base directory (where the engine executable is) and open a third Powershell window there
6. Enter the command "python main.py"

If all goes well the engine should be running in one window, the enemy snake should be running in another window, and the training loop should be running in the third window. Note that any "tcp 6060" error messages are expected and won't cause any issues.

