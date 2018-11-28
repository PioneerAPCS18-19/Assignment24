# Assignment 24

A school has 100 lockers and 100 students. All lockers are closed on the first day of school.

As the students enter, the first student, denoted `S1`, opens every locker. Then the second student, `S2`, begins with the second locker, denoted `L2`, and closes every other locker. Student `S3` begins with the third locker and changes every third locker (closes it if it was open, and opens it if it was closed). Student `S4` begins with locker `L4` and changes every fourth locker. Student `S5` starts with `L5` and changes every fifth locker, and so on, until student `S100` changes `L100`.

After all the students have passed through the building and changed the lockers, which lockers are open?

## Specifications

Please print the locker numbers that are open (1 - 100). If you don't notice a pattern with the numbers, you probably made a mistake somewhere.

Only one class is necessary, but you should create some other methods (don't put everything in `main`).

### Sample Output

Suppose the third, tenth, fiftieth, and seventy-sixth lockers are open.

```
3
10
50
76
```

### Grading

As always, your program will be graded on its functionality according to the project specifications and proper code style.

