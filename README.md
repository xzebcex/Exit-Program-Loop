# Exit-Program-Loop
This script is a simple program that prompts the user to type a response and then prints the response back to the user. The script will continue to prompt the user for a response until the user types 'exit', at which point the script will exit.

## Description
This program is a simple script that runs an infinite while loop that repeatedly prompts the user to type in a response and then prints out the response. The program imports the sys module and uses its exit() function to break out of the infinite loop when the user types in "exit" as their response. The user can type any string to interact with the program, when the user types "exit", the program will terminate using sys.exit() function. The program uses the input() function to get the user's response and assigns it to the variable "response". Then it checks if the response is equal to "exit" using an if statement. If the response is "exit", the program will exit by calling the sys.exit() function, otherwise, it will print "your typed 'response'."


## Requirements
This script requires Python3 to be installed on the system.

## Usage
To run the script, open a command line terminal and navigate to the directory where the script is located. Then, enter the command ‘python3 script.py.

The script will start running and will repeatedly prompt the user to type a response. The user can type any response, and the script will print the response back to the user. To exit the script, the user must type 'exit' (without quotes) and press enter.

## Limitations
This script is a basic example and doesn't include any error handling or validation. It is intended to be used as a starting point for more complex programs.

## Conclusion
This script is a simple program that demonstrates the basic functionality of user input and output in Python. It can be used as a starting point for more complex programs that require user input and output. The script uses a while loop that continues running until the user types "exit", and then it uses ‘sys.exit()’ to exit the script. As always, it is important to consider the legal and ethical implications of any code you write and run.
