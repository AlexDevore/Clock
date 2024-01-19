# Clock
This simple C++ program allows users to input a specific time (hours, minutes, and seconds) and then displays a continuously updating clock-like interface on the console.

Features

    User input for setting the initial time.
    Validates input to ensure that the entered time is within the valid range (hours < 24, minutes < 60, seconds < 60).
    Continuous display of the time in HH:MM:SS format.
    The program uses the Windows API function Sleep to create a one-second delay between each update.

How to Use

    Run the program.
    Enter the desired initial time when prompted.
    The program will continuously display the time in a clock-like format.
    
Example

  enter hour:
  12
  enter minutes:
  30
  enter seconds:
  45
  12:30:45
  12:30:46
  12:30:47

If you find any issues or have any suggestions, please open an issue or contribute to the project.
