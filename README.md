# Interactive-Quiz-Game
In this script:

    displayQuestion function is used to display the current question and its options. Each option is a button that, when clicked, calls checkAnswer with the respective option.

    checkAnswer function checks if the selected option is correct. It alerts the user if the answer is correct or wrong.

    After checking the answer, the script increments currentQuestion and calls displayQuestion again to load the next question. If there are no more questions, it alerts the user that the quiz is completed.

    The initial call to displayQuestion at the end of the script starts the quiz by displaying the first question.
