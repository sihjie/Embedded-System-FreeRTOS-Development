# Lab 4: 
[FreeRTOS_Lab4.pdf](https://github.com/user-attachments/files/21918998/FreeRTOS_Lab4.pdf)

This lab requires 2 parts:
### Part 1 Implement the vPrintFreeList
- Implement your vPrintFreeListfunction in heap_2.c.
- Task print_task should print the correct free block list to console through UART.

### Part 2 Modify the prvInsertBlockIntoFreeList macro
- Modify prvInsertBlockIntoFreeListmacro in heap_2.c to implement
memory merge.
- After merging the adjacent free blocks, the free blocks should still be sorted in
ascending order based on their size.

---
### HackMD 
I documented my learning process and key takeaways in a series of HackMD notes, available [here](https://hackmd.io/@GDIF3DlmRBa7hCk6nQfzkQ/HkkN7jVtxx).

---
### Demo Video
https://github.com/user-attachments/assets/dcad75bc-058d-4b15-9695-14eb65bd02ad

https://github.com/user-attachments/assets/ea902243-2d0e-4261-8a23-216b861f77f8

