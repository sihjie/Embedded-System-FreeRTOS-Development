# Lab 3: Motion Detection
[lab3.pdf](https://github.com/user-attachments/files/21794007/lab3.pdf)

- Must use sensor interrupt : motion detection.
  - When you shake your board, it will trigger the interrupt.
- Please use the deferred interrupt handling task.
  - Use semaphore.
  - ISR will give the semaphore and the handler task enters the running state.
- At the beginning, the green LED blinking, then shake the board, the red LED triggered（switch state） by ISR and the orange LED blinking five times in handler task.
- When orange LED blinking, you should not trigger the sensor interrupt if you shake the board.

<img width="283" height="80" alt="image" src="https://github.com/user-attachments/assets/ed0676ea-63f7-4e1b-a3b1-eaaec336691a" />

## HackMD
I documented my learning process and key takeaways in a series of HackMD notes, available [here](https://hackmd.io/@GDIF3DlmRBa7hCk6nQfzkQ/BkFXjqhOle).

## Demo Video
https://github.com/user-attachments/assets/733dadf0-1f02-4526-9d14-ba2419b98c4a

