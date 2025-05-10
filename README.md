****🎯 Number Guessing Game in C (with Queue Data Structure)****

*This C-based console project blends programming logic with data structure application. It simulates a number guessing game where all wrong guesses are stored in a queue implemented using a linked list. Designed for learners, it strengthens understanding of dynamic memory management and queue operations.*


**🧠 Project Objective**
The goal of this project is to:

1) Implement a number guessing game with multiple difficulty levels.

2) Use a queue (linked list) to store all incorrect guesses in the order they were made.

3) Offer user-friendly interaction with hints and the ability to exit or replay the game.


Demonstrate practical usage of:

1) Random number generation

2) Queue operations (enqueue and traversal)

3) Dynamic memory allocation

4) Looping and conditionals

5) Function modularity


**🔑 Key Features**
*🔢 Difficulty Selection:*

Easy (0–100)

Medium (0–1000)

Hard (0–5000)


**💡 Smart Hint System:**

Tells users if they need to guess a higher or lower number after each attempt


*🧾 Guess Tracking with Queue:*

All wrong guesses are dynamically stored in a queue using linked list

Efficient memory handling using malloc()

Prevents memory waste by deallocating when needed


*❌ Quit Anytime:*

Users can enter -1 to exit mid-game


*🔁 Replay Option:*

After each game, users can choose to replay


*📜 Guess Display:*

At game end, the queue is traversed to show all incorrect attempts in order



**🛠️ Technical Breakdown**

✅ Queue Implementation
A linked list is used to simulate queue behavior.

Functions used:

insert() to enqueue each wrong guess at the rear

display() to print all guesses in FIFO order

Queue structure prevents memory overflow by dynamically managing nodes

✅ Random Number Generation
Uses:

rand() to generate a random number within the selected range

srand(time(NULL)) to ensure randomness on each run

✅ User Interaction
Input via scanf() for smooth console-based play

Graceful exit using -1

Option to replay or terminate after each round

✅ Modularity
Clean, modular code structure:

main() handles flow

Dedicated functions for:

Game logic

Queue operations

Random number setup

User prompts and validation


**🎓 Educational Value**
This project helps students and beginners in:

Applying data structures like queues in a real scenario

Understanding dynamic memory allocation

Practicing looping, branching, and user input handling

Writing clean, modular C code
