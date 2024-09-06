## WPM Typing Test
This is a command-line-based typing speed test built using Python and the curses library.
The application allows users to practice typing and calculates their typing speed in words per minute (WPM). 

## How It Works:
Start Screen:
When the program is launched, it shows a welcome message and prompts the user to press any key to begin the test.

Text Display and Typing:
The program loads a random line of text from a file (text.txt). This is the target text that the user must type. As the user types, their input is compared to the target text. Correctly typed characters are displayed in green, while incorrect characters are shown in yellow.

Real-Time WPM Calculation:
The program continuously calculates the user's WPM based on the number of correctly typed characters and the elapsed time since the test started. The formula for WPM is:

Ending the Test:
The test ends when the user successfully types the entire target text. At that point, the program stops accepting input and shows the final WPM score. The user is then prompted to press any key to either continue with another test or exit by pressing the ESC key.

## Key Features:
Backspace Handling: Users can delete characters with the backspace key.
Escape Key: Pressing the ESC key at any point exits the test.
Real-Time Feedback: Characters are color-coded to indicate whether the user's input matches the target text.
WPM Calculation:
Words per minute (WPM) is calculated by dividing the number of characters typed by 5 (since the average word length is assumed to be 5 characters), and then dividing by the time elapsed in minutes.

