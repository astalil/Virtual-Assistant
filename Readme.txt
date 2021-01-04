Virtual Assistat
You can use the program on Windows OS for now (only tested on Windows 10 atm).
The program includes the following functions:
    - getting data about a person or a thing from Wikipedia
    - generating random numbers from 0 to a 100
    - telling random jokes
    - telling the time and date
    - calculating simple math problems with +, -, *, / operators.

If you get an error message when launching the program, you may need to install Visual C++ Redistributable. (dont yet know all of the errors that may occur)

When you start the program it will ask you to enter an audio sentence (so the program works by talking to the mic). If the sentence includes a fuction call it will return a result, otherwise nothing will happen
and the loop will start again.

Calling functions:
    GREETING A PERSON: If the sentence includes words "hi", "hello", "hey". The program will return one of the greeting gestures.

    TIME: If the sentence includes a word "TIME" the program is gonna return the current time. (Example: Can you tell me the time)

    DATE: If the sentence includes a word "DATE" the programs is gonna return the current date. (Example: Can you tell me the date)

    CALCULATOR: If the sentence includes words "CALUCALTOR WHAT IS xyz" the pgoram will return the anwser. (Example: Calculator what is 2*2+4/6+1)

    RANDOM NUMBER: If the sentence includes words "RANDOM NUMBER" the program will return a random number from 0 up to 100. (Example: Can you generate me a random number)

    DATA ABOUT A PERSON: If the sentence includes words "WHO IS xyz" or "WHO WAS xyz" the program will tell you 2 sentences about that person. If there are multiple entries you will get to pick the
        person you are looking for. Also a window opens with short information about the person. You can close the window by clicking the CLOSE button, there is also a COPY button that copies the used wikipedia URL. Note that including words/sentences after asking about a person will resault with no anwser or with a poor one. (Example: Who is Steve Jobs)

    DATA ABOUT SOMETHING: If the sentence includes words "WHAT IS xyz" the program will return 2 sentences about it. If there are multiple entries you will get to pick the
        thing you are looking for. Also a window opens with short information about the searched thing. You can close the window by clicking the CLOSE button, there is also a COPY button that copies the used wikipedia URL.  Note that including words/sentences after asking about a thing will resault with no anwser or with a poor one. (Example: What is Area51)

    JOKE: If the sentence includes a word "JOKE" the program will return a random joke from a txt file. (Example: I would like to hear a joke)

    QUIT: If the sentence includes words "QUIT PROGRAM" it exits the program. (Example: Quit program please)

    Example of combining functions "hello can you tell me the time and date generate me a random number and who is James Charles".