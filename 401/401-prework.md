#### [Home](../README.md) | [Code 102](../102main.md) | [Code 201](../201main.md) | [Code 301](../301main.md) | [Code 401](../401main.md)

---

# Code 401 | Prework Reading Notes

## READINGS

### **[Solving Problems](https://simpleprogrammer.com/solving-problems-breaking-it-down/)**

1. Read the problem completely twice.
   Test whether or not you can explain the problem to someone else.
2. Solve the problem manually with 3 sets of sample data.
   Example of reversing string "zebra":

-   Write “Zebra” down.
-   Start a new word, and put “a” as the first letter. (Why –> because it is the last letter, we want to start here)
-   Put “r” down as the 2nd letter. (Why –> because it is the next letter backwards from the last letter we copied)
-   Put “b” down as the 3rd letter. (Why –> same as above)
-   Etc.

3. Optimize the manual steps.

-   Write “Zebra” down.
-   Start at the last letter in the word and create a new empty word.
-   Append the current letter to the new word
-   If there is a previous letter, make the previous letter the current letter and start back at 3.

4. Write the manual steps as comments or pseudo-code.

```
// NewWord = ""
// Loop backwards through word to reverse
// NewWord += CurrentLetter
// Return NewWord
```

5. Replace the comments or pseudo-code with real code.

```
String newWord = ""
for(int index = oldWord.Length – 1; index <= 0; index-)
   newWord += oldWord[index];
return newWord;
```

6. Optimize the real code.

### **[Act like you make $1,000/hr.](https://medium.com/swlh/pretend-your-time-is-worth-1-000-hour-and-youll-become-100x-more-productive-f04628bb3e6d)**

> **Imagine that an hour of your time is worth $1,000.**
> What would your life look like?
> What people would you stop putting up with?
> What problems would you stop wasting time on?
> What things would you stop — and start — doing?

Be less busy, but more **focused**.

### **[How to think like a programmer](https://medium.freecodecamp.org/how-to-think-like-a-programmer-lessons-in-problem-solving-d1d8bf1de7d2)**

When encountering a new problem:

1. Understand - be able to explain the problem in simple terms
2. Plan - don't start solving without a plan; give your brain time to analyze/process the information
3. Divide - break the problem into sub-problems, then solve one by one
4. Stuck?

-   Debug
-   Reassess
-   Research

### **[The 5 Whys](https://www.mindtools.com/pages/article/newTMC_5W.htm)**

Drill down into a problem by asking "Why?" 5 times.

## VIDEOS

### **[What the heck is the event loop anyway](https://www.youtube.com/watch?v=8aGhZQkoFbQ)**

### **[The Super Mario Effect](https://www.youtube.com/watch?v=9vJRopau0g0)**

Finding the right way to frame the learning process. \
**OBSERVATION**:

> What if you frame the learning process in such a way that you didn't concern yourself with failure?
> How much more successful could you be? How much more could you learn?
> If this is a real effect, clearly there must be some evidence for this in real life.

SUPER MARIO EFFECT: Focusing on the Princess and not the pits, to stick with a task and learn more.\
SUPER MARIO EFFECT: Shifting the focus from falling into pits to saving the princess, to stick with a task and learn more.

### **Bonus video (that I added myself)! [The Power of Belief](https://youtu.be/pN34FNbOKXc)**

1. Recognize that the growth mindset is not only beneficial, but is also supported by science. Neuroscience shows that the brain changes and becomes more capable when we work hard to improve ourselves.
2. Learn and teach others about how to develop our abilities. Learn about deliberate practice and what makes for effective effort. When we understand how to develop our abilities, we strengthen our conviction that we are in charge of them.
3. **Listen for your fixed mindset voice, and when you hear it, talk back with a growth mindset voice.**

---

#### [Home](../README.md) | [Code 102](../102main.md) | [Code 201](../201main.md) | [Code 301](../301main.md) | [Code 401](../401main.md)
