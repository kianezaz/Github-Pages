# Kian Ezaz

- [Kian Ezaz](#kian-ezaz)
  - [About me](#about-me)
  - [First Week Back at School](#first-week-back-at-school)
  - [Today's Tasks](#todays-tasks)

## About me

I am a third-year math-cs student attending UCSD. I started off on the pre-med track, but later realized that I *really* enjoy solving programming problems. So, I recently switched to my current major and have been enjoying it very much. Plus, I love spending time on campus (**especially Geisel Library**).

![This is an image](https://ucsdnews.ucsd.edu/news_uploads/Resized_Geisel_Library_08.31.jpg)

Since beginning programming about a year ago, I've mainly used the languages:
- Java 
- C 
- C++ 
- Javascript
- SQL 
  
In addition to other techologies like 

- React.js
- Express.js
- MongoDB
- GDB

Other things I'm interested in are:
1. sports (especially soccer)
2. going to the beach
3. playing the guitar

## First Week Back at School

Today (9/24/21) marks the second day of the 2021-22 UCSD school year. My Algorithms professor started off the first lecture by showing how we can go beyond using the obvious solution to problems for optimization. For example, the common way to go about finding the nth term in the Fibonacci sequence is:
```
int fib1(n) {
    if (n <= 1) {
        return n;
    }
    return fib1(n - 1) + fib1(n - 2);
}
```
According to the website GeeksForGeeks, 
> this implementation does a lot of repeated work... So this is a bad implementation for nth Fibonacci number.

However, a more optimized way to go about solving this problem would be by using dynamic programming:
```
int fib2(n) {
    int[] f = new int[n + 2];
    f[0] = 0;    f[1] = 1;
    for (int i = 2; i <= n; i++) {
        f[i] = f[i - 1] + f[i - 2];
    }
    return f[n];
}
```
Additional methods and time complexity can be found [here](https://www.geeksforgeeks.org/program-for-nth-fibonacci-number/)

One of my other classes is Software Engineering (the same class I'm doing this current lab for). This lab aims to familiarize us with Git and working with VS Code. Screenshots of the types of commands that were used for today's lab can be found [here](screenshots/../Screenshots/CSE110-Lab1-Part1a.png) and [here](Screenshots/CSE110-Lab1-Part1b.png)

## Today's Tasks
- [x] Commute to campus on time
- [ ] Play pick-up soccer
- [ ] Work on my side project