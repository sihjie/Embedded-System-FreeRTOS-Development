# Lab 5: fat file system with SPI to micro SD card adaptor device
[Lab5.pdf](https://github.com/user-attachments/files/21922841/Lab5.pdf)

- Connect an external module to the development board to read and play WAV files from the micro SD card.
- Write data to the micro SD card.

**Implementation details**
- When the blue button is pressed, an interrupt will be triggered, executing the callback function and notifying the button task.
- Inside the button task, the function GetButtonEvent() will be used, which returns whether the user’s action is a single click, double click, or long press. The missing part needs to be implemented to complete this judgment.
- State transition diagram:
  <img width="812" height="465" alt="image" src="https://github.com/user-attachments/assets/4a939757-2fa4-41fd-bd51-09306dccf31a" />


---
### HackMD 
I documented my learning process and key takeaways in a series of HackMD notes, available [here](https://hackmd.io/@GDIF3DlmRBa7hCk6nQfzkQ/SJQJFAVKxx).

---
### Demo Video
https://github.com/user-attachments/assets/e92f1bba-39e3-4a19-8065-7441aa7cefd3

