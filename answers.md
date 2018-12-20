# Assignment 7: Basics of Scheduling

## Question 1


---
## Question 2
|          Process         | G | B | A |  D |  C |  F |  H |  E |
|:------------------------:|:-:|:-:|:-:|:--:|:--:|:--:|:--:|:--:|
| Expected run time (msec) | 2 | 5 | 8 | 12 | 16 | 21 | 34 | 55 |

sum = msec * (2 + 7 + 15 + 27 + 43 + 64 + 98 + 153) = __409 msec__

average = 409 msec / 8 = __51.125 msec__

---
## Question 3
If the process hasn't finished yet, nothing significant would happen except that all the others process would have to wait longer for their time.

If the process is finished then the outcome depends on how the scheduler reacts to this situation. If the scheduler:
- ignores the process because it does not exist anymore nothing will happen
- does not ignore the procces the scheduler might crash
