Virtual Assistant
You can use the program on Windows OS for now (only tested on Windows 10 atm).
The program includes the following functions:
    - getting data about a person or a thing from Wikipedia
    - generating random numbers from 0 to 100
    - telling random jokes
    - telling the time and date
    - calculating simple math problems with +, -, *, / operators.

If you get an error message when launching the program, you may need to install Visual C++ Redistributable. (don't yet know all of the errors that may occur)

When you start the program it will ask you to enter an audio sentence (so the program works by talking to the mic). If the sentence includes a function call it will return a result, otherwise, nothing will happen
and the loop will start again.

Calling functions:
    GREETING A PERSON: If the sentence includes the words "hi", "hello", "hey". The program will return one of the greeting gestures.

    TIME: If the sentence includes the word "TIME" the program is gonna return the current time. (Example: Can you tell me the time)

    DATE: If the sentence includes the word "DATE" the program is gonna return the current date. (Example: Can you tell me the date)

    CALCULATOR: If the sentence includes the words "CALCULATOR WHAT IS XYZ" the program will return the answer. (Example: Calculator what is 2*2+4/6+1)

    RANDOM NUMBER: If the sentence includes the words "RANDOM NUMBER" the program will return a random number from 0 up to 100. (Example: Can you generate me a random number)

    DATA ABOUT A PERSON: If the sentence includes the words "WHO IS XYZ" or "WHO WAS XYZ" the program will tell you 2 sentences about that person. If there are multiple entries a window will open and you will be able to choose between the options. Before talking a window opens with the same info, there are 2 buttons one lets you copy the page URL and the other closes the window. Note that including words/sentences after calling the function will result in an error. (Example: Who is Steve Jobs)

    DATA ABOUT SOMETHING: If the sentence includes the words "WHAT IS XYZ" the program will return 2 sentences about it. If there are multiple entries a window will open and you will be able to choose between the options. Before talking a window opens with the same info, there are 2 buttons one lets you copy the page URL and the other closes the window. Note that including words/sentences after calling the function will result in an error. (Example: What is Area51)

    JOKE: If the sentence includes the word "JOKE" the program will return a random joke from a txt file. (Example: I would like to hear a joke)

    QUIT: If the sentence includes the words "QUIT PROGRAM" it exits the program. (Example: Quit program please)

    Example of combining functions "hello can you tell me the time and date generate me a random number and who is James Charles".
