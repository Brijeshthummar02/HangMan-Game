# 🎨 What This Code Does

✅ **Green (`\u001B[32m`)** for correct guesses and `"YOU WIN!"`  
✅ **Red (`\u001B[31m`)** for wrong guesses, game over, and missing file errors  
✅ **Yellow (`\u001B[33m`)** for welcome messages

---

## 🔹 More ANSI Colors

| **Color**  | **Code**          |
|------------|------------------|
| **Black**  | `\u001B[30m`     |
| **Red**    | `\u001B[31m`     |
| **Green**  | `\u001B[32m`     |
| **Yellow** | `\u001B[33m`     |
| **Blue**   | `\u001B[34m`     |
| **Purple** | `\u001B[35m`     |
| **Cyan**   | `\u001B[36m`     |
| **White**  | `\u001B[37m`     |
| **Reset**  | `\u001B[0m`      |

---

## 🚀 How to Use ANSI Colors in Java

You can use **ANSI escape codes** to change text color in the terminal.  
Wrap your text with the **color code** at the start and `\u001B[0m` at the end to reset the color.

### ✅ **Simple Example**
```java
public class AnsiColorExample {
    public static void main(String[] args) {
        System.out.println("\u001B[32mThis is green text!\u001B[0m");
        System.out.println("\u001B[31mThis is red text!\u001B[0m");
        System.out.println("\u001B[33mThis is yellow text!\u001B[0m");
        System.out.println("\u001B[36mThis is cyan text!\u001B[0m");
    }
}
