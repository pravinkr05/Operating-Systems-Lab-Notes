Output:

---

# Fork Example

This program demonstrates process creation using `fork()` in C. It creates child processes and displays their process IDs.

## Compilation and Execution

To compile and execute the program:

```sh
gcc as10fork.c -o fork
./fork
```

**Expected Output:**

```
my parent's pid 18952
i am child2 having pid 18954
i am child2 and my siblings id 18953
```

## Code Description

- The parent process prints its own PID.
- It then creates two child processes. The second child process prints its PID and the PID of its sibling.

---

Feel free to modify as needed!
