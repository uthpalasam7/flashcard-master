# flashcard-master

**flashcard-master** is a simple Java console application for creating and studying flashcards. Users can add flashcards, view them, and test their knowledge with a quiz. It's designed to help with active recall and spaced repetition learning.

## Features
- **Add Flashcards**: Create flashcards by entering a question and its corresponding answer.
- **View Flashcards**: Display all saved flashcards.
- **Quiz Mode**: Test your knowledge by answering the questions from your flashcards. Get your score at the end of the quiz.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/uthpalasam7/flashcard-master.git
    ```
2. Compile and run the program:
    ```bash
    javac Main.java
    java Main
    ```

## Structure
- `Main`: Handles menu and program control.
- `Flashcard`: Represents a flashcard with a question and answer.
- `FlashcardService`: Manages flashcards, including adding, viewing, and running quizzes.
