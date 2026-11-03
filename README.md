# Auceps
<img width="458" height="249" alt="image" src="https://github.com/user-attachments/assets/9ba0a776-26c6-4e6a-88b9-373bff4417fe" />






# Description 
A powerful keylogger designed and programmed by myself with the following features, 

1. One of the coolest and most powerful features is
   Gladius's ability to run in the background which
   allows for covert data collection.

2. Can write to a text file, and send data over a tcp
   socket concurrently. 

3. Requires a relatively low amount of CPU usage

4. Logs all keystrokes with 100% accuracy.

# Flowchart
<img width="402" height="501" alt="image" src="https://github.com/user-attachments/assets/c414d792-8bd9-49b0-9421-28295f8b9610" />

# Why? 

To be honest, I've been wanting to write a keylogger for quite some time now! Prior to this, I had spent many attempts trying but ultimately failing. The main point of failure initially was trying to find a way to log keystrokes accurately, once I found a work around by utilizing a completely method of logging, I was able to successfully write them into an output stream with ease and I was genuinely happy. 

Long story short, I actually found the solution by applying an algebraic concept I learned from high school math. Zeroing a function. I realized I could zero out a specific windows API function through every iteration that the program checks to see if a keystroke has been pressed. It was completely unintuitive for me however, made the experience far more rewarding when I eventually solved it.

It was also a great challenge, and a great opportunity to sharpen my C++ skills. 
