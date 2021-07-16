##Loops Questions Project##

**Q:** How do you creat a for loop?

> **A:** First, declare a variable counter and initialize it to. 
Second, display the value of counter in the Console window if counter is less than 5.
Third, increase the value of counter by one in each iteration of the loop. 
```js
// (Example)program to display text 5 times
const counter = 5;

// looping from i = 1 to 5
for (let i = 1; i <= counter; i++) {
    
}
```

---

**Q:** What are loops used for?

> **A:** Loops allow you to repeat a process over and over without having to write the same (potentially long) instructions each time you want your program to perform a task.

---

**Q:** Why can the follwing loop be bad for your computer?

```js
const counter = 0;
for (let i = 1; i <= counter; i++) {
    
}
```

> **A:** the follwing loop is an infinet loop, it can be dangerous if it never blocks or sleeps. This can take the CPU to near 100% utilization and prevent other programs from running very well.