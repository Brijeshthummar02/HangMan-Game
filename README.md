**Hangman Game - Java Edition**
===============================

**📌 Overview**
---------------

This is a simple **Hangman game** implemented in **Java**, where the player guesses letters to uncover a hidden word. The word is randomly selected from a file (`words.txt`). The player has **6 chances** to guess the correct word before the game ends.

* * * * *

**📜 Features**
---------------

✔️ Reads words from an external file (`words.txt`)\
✔️ Random word selection\
✔️ ASCII-based Hangman visualization\
✔️ Tracks correct and incorrect guesses\
✔️ Ends the game when the word is fully guessed or after 6 incorrect attempts

* * * * *

**🛠️ Installation & Setup**
----------------------------

### **1️⃣ Prerequisites**

Ensure you have the following installed:

-   **Java Development Kit (JDK)** (Version 8 or later)
-   **IntelliJ IDEA** (or any Java IDE)

### **2️⃣ Setting Up the Project**

1.  **Download or Clone the Project**

    ```
    git clone https://github.com/your-repo/hangman-java.git
    cd hangman-java

    ```

2.  **Create `words.txt` File**\
    The game reads words from a file named **`words.txt`**.

    -   Create a new file **in the same directory as `Main.java`**
    -   Add words (one per line), for example:

        ```
        apple
        banana
        computer
        java
        python
        elephant

        ```

3.  **Open in IntelliJ IDEA**

    -   Open **IntelliJ IDEA**
    -   Click **File → Open...** and select the project folder

* * * * *

**🚀 Running the Game**
-----------------------

1.  **Compile & Run in IntelliJ**

    -   Open **Main.java**
    -   Click **Run ▶️** or press `Shift + F10`
2.  **Run in Terminal (Optional)**

    ```
    javac Main.java
    java Main

    ```

* * * * *

**🎮 How to Play**
------------------

1.  The game randomly selects a word from **words.txt**
2.  You will see underscores (`_`) representing the hidden word
3.  **Guess a letter** by typing it in the console
4.  If correct, the letter appears in its position
5.  If incorrect, the Hangman progresses
6.  **Win by guessing the word before 6 mistakes**

* * * * *

**🖼️ Hangman Visual Representation**
-------------------------------------

| Wrong Guesses | Hangman Art |
| --- | --- |
| 0 |  |
| 1 | `o` |
| 2 | `o` ` |
| 3 | `o` `/ |
| 4 | `o` `/ |
| 5 | `o` `/ |
| 6 | `o` `/ |

* * * * *

**🛠️ Debugging with Java Visualizer in IntelliJ IDEA**
-------------------------------------------------------

### **Enabling the Java Visualizer Plugin**

1.  Go to **File → Settings → Plugins**
2.  Search for **Java Visualizer**
3.  Click **Install** → Restart IntelliJ

### **Using Java Visualizer for Debugging**

1.  **Set a Breakpoint** in `Main.java` (e.g., inside the loop checking guessed letters).
2.  **Start Debugging** (`Shift + F9`).
3.  **Right-click a variable in Debugger** → Select **"Show in Java Visualizer"**.
4.  View the game's internal state (word, guesses, etc.).

* * * * *

**📜 Example Gameplay**
-----------------------

```
************************
Welcome to Java Hangman!
************************

Word: _ _ _ _ _ _ _

Guess a letter: e
Correct guess!

Word: _ _ e _ _ _ _

Guess a letter: x
Wrong guess!

   o

Word: _ _ e _ _ _ _

Guess a letter: p
Correct guess!

Word: _ p e _ _ _ _

...

```

* * * * *

**💡 Enhancements & To-Do**
---------------------------

✅ **Add difficulty levels** (Easy, Medium, Hard)\
✅ **Improve word selection** with categories\
✅ **Add multiplayer support**

* * * * *

**📄 License**
--------------

This project is **open-source**. Feel free to modify and improve it!

* * * * *
