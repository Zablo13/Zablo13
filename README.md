# 👋 Hi, I’m Daniel Zablotny   (Zablo13)

I’m a career-changer retraining as an **Application Developer (Fachinformatiker für Anwendungsentwicklung)**.  

With a background in tech support and a passion for creative coding, I enjoy building games and tools using **Python** and the **Godot engine**.  
I also craft pixel art with **Aseprite** — including my hand-pixeled profile picture.

-  Based in **Bochum, Germany**  
-  Interests: Game development · Fullstack Development · Cryptography  
-  Currently learning: **JavaScript** and **Angular**  
-  Growing interest in **cryptography** and **secure software design**  

Feedback is always welcome — check out some of my projects below!

---

## Projects

### 🔒 Zablos Secret Sharer
**Repo:** [ZablosSecretSharer](https://github.com/Zablo13/ZablosSecretSharer)  

A small cryptography utility that splits and recombines secret messages using one-time-pad style shares and helper functions.  
 
Since I was a child, I have been fascinated by secret codes. During my retraining as an application developer, I picked up this curiosity in my first Python project: a message encoder based on the One Time Pad.   
 
Step by step, I learned important fundamentals – working with variables, control structures, functions, IO operations, string manipulations, system calls, error handling, and user input via input(). The menu runs in a loop within the main() function and allows messages to be entered as well as JSON files to be loaded or saved, which can then be encrypted or decrypted.     
<br>
Since I discovered that math.random() does not produce true random numbers and would therefore be insecure, I instead rely on the secure secrets module.
   
All in all, it is a small but very educational project, through which I learned a lot about Python – and which also practically demonstrates the principles of the One Time Pad.
   
For future versions, I plan to implement user interfaces with Tkinter and argparse and to revisit the project from an object-oriented perspective.
        
**Features:**
- Split a message into multiple shares  
- Combine shares to recover the message  
- OTP support
<br><br>
(S)plit, (C)ombine, (M)astercode, (O)TP, (W)ipe, Sa(V)e, (L)oad, (Q)uit? s <br>
enter shares count 2 -> 99: 3 <br>
Message: This Message is split in 3 parts <br><br>
C1: use a random OTP with at least the message length <br>
C2: HÄKFQ^u3>°}}MKä09T@^jKjwCü6veü1-;<nw..-eAVÄQy^MHs <br>
C3: u6Ü"5xVFH2FF[0Rg[!A@§*,a>vLwgü<OZepz?pc~F^HÖ§M3°& <br><br>

-> recombine the message:<br>
Message: This Message is split in 3 parts


---

### 🏀 Basket Brawl
**Repo:** [Basket_Brawl_no_sound](https://github.com/Zablo13/Basket_Brawl_no_sound)  

A small arcade-style basketball game (no sound). Built with Godot — focusing on mechanics and input handling.  
 

---

### 🧱 Brick Breaker
**Repo:** [brickbreaker](https://github.com/Zablo13/brickbreaker)  

A classic brick breaker project made with Godot (or Python + Pygame, depending on repo). Good demonstration of collision handling, level design, and simple physics.  


---

## Skills & Tools
- **Languages:** Python (comfortable), JavaScript (learning), SQL (basic)  
- **Frameworks / Engines:** Godot · Aseprite (Pixel Art)  
- **Dev tools:** Git · GitHub · VS Code  
- **Focus areas:** Cryptography, secure software design, game development, fullstack  

---

## How to Run / Contribute

Clone a repository:
```bash
git clone https://github.com/Zablo13/<repo-name>.git
Godot projects: open the .godot file directly in the engine.

Python projects: create a venv and run


📫 Contact
GitHub: Zablo13

Location: Bochum, Germany
