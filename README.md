# Flash-cards-application
This is a simple flash card application for memorizing the words
This Python code creates a flashcard application using Tkinter, a GUI (Graphical User Interface) library for Python. Here's a breakdown of what the code does:

Imports necessary libraries: random for selecting random items, tkinter for creating the GUI, and pandas for handling data.

Defines constants such as BACKGROUND_COLOR, which sets the background color for the application.

Sets up the main window (window) with a title, padding, and background color.

Creates a canvas widget (canvas) within the window to display flashcards.

Loads images for the front and back of the flashcards (card_front_img and card_back_img) and sets up an initial card with the front image displayed.

Initializes variables current_card and to_learn, and attempts to read previously saved data from a CSV file. If the file is not found, it reads data from another CSV file.

Defines functions:

flip_card(): Flips the current card to reveal the other side.
next_card(): Selects the next flashcard to display.
is_known(): Removes the current card from the list of cards to learn and saves the updated list to a CSV file.
Creates buttons for indicating whether the user knows the word or not (unknown_button and known_button) and associates them with the corresponding functions.

Sets up a timer (flip_timer) to automatically flip the card after a certain time.

Calls the next_card() function to display the first flashcard when the application starts.

Enters the Tkinter event loop (window.mainloop()), allowing the application to run and respond to user interactions.

Overall, this code creates a simple flashcard application where users can flip through cards, mark them as known or unknown, and learn new vocabulary. It utilizes Tkinter for the GUI and pandas for data manipulation.






