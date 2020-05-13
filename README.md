# VLE-Attendance
Attendance made easy

Ensure the directory that the executable is stored in has the following files in it too:
  1. A file called "Session{}" with the session number replacing the braces
  2. A file called "RollCall" saved in the CSV UTF-8 (Comma delimited) format
 If these files are not in the directory, the program will not work.

This will create a new CSV file named "RollChecked {}" with the session number replacing the braces.

If the program fails to run, it will shut down immediately. Ensure the necessary files are present and run the program again.
