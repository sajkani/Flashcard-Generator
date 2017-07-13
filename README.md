# Flashcard-Generator

Basic FlashCard backend node application.

Run 'node FlashCard.js' via command prompt.

The flow of the application is:

After initially running FlashCard.js, Inquirer will present with prompt:

    What would you like to do? (Use arrow keys)
    add-flashcard
    run-through-cards

    *add-flashcard will take you to a prompt to add a flash card.
        basic-flashcard creates a card with a Q and A.  EX:  Q.What color is the sky? A.Blue
        close-flashcard creates a card with cloze deletation.  EX: Q._____ played Han Solo in Star Wars.  A.Harrison Ford

    *run-through-cards will run through cards that have been created and appended to log.txt and ask the questions.  If entering the correct answer, the user will be prompted with 'Correct!'
    If entering the incorrect answer, the user will be prompted with 'Wrong!'
    After all of the card runs, you will return to the command prompt.

    *exit will return you to the command prompt.