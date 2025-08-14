## Lab 1: MultiTask, with Inter-Task Communication (ITC) mechanism
[Lab1.pdf](https://github.com/user-attachments/files/21773873/Lab1.pdf)

This lab requires a button to toggle between two states of the LED task:
#### 1. LED Task
The LED task has two states:
**S1** (Sequential Switching Mode):
- Red LED on for 1 second (others off)
- Orange LED on for 1 second (Red off)
- Green LED on for 1 second (Red and Orange off)

Repeats in sequence: Red → Orange → Green

**S2** (Orange Blinking Mode):
Orange LED on for 2 seconds, off for 2 seconds, repeating continuously

#### 2. Button Task
When the button is pressed, the LED task switches state: 
- S1 → S2
- S2 → S1 (can be extended if needed)

Must include:
- Debounce handling
- Edge detection handling to ensure the state changes only on the moment of button press
---
### HackMD 
I documented my learning process and key takeaways in a series of HackMD notes, available [here](https://hackmd.io/@GDIF3DlmRBa7hCk6nQfzkQ/B1NHxwoueg).

---
### Demo Video
https://github.com/user-attachments/assets/6e3e09f9-1d87-4aef-be7b-a8379e1cdd38




https://github.com/user-attachments/assets/a0e6d244-1d2a-4bc1-a3f8-47bced38dbf4

