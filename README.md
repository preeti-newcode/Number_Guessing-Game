****🎮 Number Guessing Game Using Queue in C****

This interactive console-based number guessing game is designed to reinforce core programming logic and data structure concepts—specifically, the Queue implemented via a linked list. Users guess a randomly generated number based on difficulty level, with all incorrect guesses tracked dynamically in a queue.

**🚀 Features**
Difficulty Levels:
Easy (0–100)
Medium (0–1000)
Hard (0–5000)

Dynamic Guess Tracking:
Incorrect guesses are stored in a queue (linked list)
Memory managed via malloc()
Wrong attempts displayed at the end

Intelligent Hints:
Suggests whether the guess should be higher or lower

User Options:
Enter -1 anytime to quit
Replay mode included after each game

**🛠️ Technical Overview**
Queue Implementation:
Linked list used for storing guesses
insert() adds to rear, display() prints wrong attempts

Random Number Logic:
Uses rand() and srand(time(NULL)) for unique numbers

Input Handling:
Takes user input via scanf()

Gracefully exits and offers replay on user command

This project provides a fun and educational approach to practicing data structures, especially dynamic queues, while building problem-solving and logic skills in C programming.

