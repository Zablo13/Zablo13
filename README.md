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
 
Step by step, I learned important fundamentals – working with variables, control structures, functions, IO operations, string manipulations, system calls, error handling, and user input via input(). The menu runs in a loop within the main() function and allows messages to be entered which can then be encrypted or decrypted.     
     
All in all, it is a small but very educational project, through which I learned a lot about Python – and which also practically demonstrates the principles of the One Time Pad.
   
For future versions, I plan to implement user interfaces with Tkinter and argparse and to revisit the project from an object-oriented perspective.
        
**Features:**
- Split a message into multiple shares  
- Combine shares to recover the message  
- OTP support
  
-> create OTP and split message with OTP:  
OTP: i*S=#>Erbj8BYz<Eo:b"  

(S)plit, (C)ombine, (M)astercode, (O)TP, (W)ipe, (Q)uit? s  
enter shares count 2 -> 99: 2  
Message: short secret message  
OTP: i*S=#>Erbj8BYz<Eo:b"  
  
-> result are two shares:  
Share1/2: i*S=#>Erbj8BYz<Eo:b"  
Share2/2: A,Mß,]e<18WiX<re4k5ß
  
-> recombine the shares:  
Message: short secret message  
  
---

### 🕵️ Zablos Substitution Cipher
**Repo:** [ZablosSubstitutionCipher](https://github.com/Zablo13/Substitution-Cipher-Maker)  
A playful text encryption tool for puzzle fans who are bored with Sudoku 😄.  
Uses a random substitution cipher (A–Z letters and "+" "-" are shuffled).  

Supports 3 difficulty levels:  
Level 1: Basic 1:1 substitution.  
Level 2: + Space substitution.  
Level 3: + Doubled characters masked behind dedicated repeat previous sign. XX, YY -> XI, YI   
       

Enter difficulty 1-3: 3  
Encrypted text: S+CA+EHCAWY+CFBEX+Y+CSBUYNCVFEQIBEGKAGKAEVM+NEZM-PI+VN+MAW+   
 
--- 

### 🔢 Zablos-Zahlen-Zieher  
**Repo:** [Zablos-Zahlen-Zieher](https://github.com/Zablo13/Zablos-Zahlen-Zieher)     
A universal number system converter for bases 2 through 36.  
Converts numbers from any base to decimal.  
Converts decimal numbers to any target base.  
Supports digits 0–9 and letters A–Z.  
  
Interactive input with error handling for invalid characters.  
  
👉 Example: 1011 in base 2 → 11 in decimal → B in base 36.  

---

### 🏀 Basket Brawl
**Repo:** [Basket_Brawl_no_sound](https://github.com/Zablo13/Basket_Brawl_no_sound)  
My first project: a small arcade-style basketball game. I enjoy games like Smash Bros., Brawlhalla, or Rayman’s Kung Foot, and wanted to create a fun couch game for 1 vs 1 or 2 vs team matches.
Built with Godot, focusing on mechanics and input handling.
All graphics are hand-drawn in Aseprite.
The code includes many comments in German, written to help teach my nephew.

With the knowledge I’ve gained since starting, I would set up the game with a different approach today — but it works fine as it is.
 

---

### 🧱 Brick Breaker
**Repo:** [brickbreaker](https://github.com/Zablo13/brickbreaker)  

A classic brick breaker project made with Godot. Good demonstration of collision handling, level design, and simple physics.  


---

## Skills & Tools
- **Languages:** Python (comfortable), JavaScript (learning), SQL (basic)  
- **Frameworks / Engines:** Godot · Aseprite (Pixel Art)  
- **Dev tools:** Git · GitHub · VS Code  
- **Focus areas:** Cryptography, game development, fullstack  

---
