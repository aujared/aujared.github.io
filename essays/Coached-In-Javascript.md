---
layout: essay
type: essay
title: Coached in Javascript?
# All dates must be YYYY-MM-DD format!
date: 2019-09-23
labels:
  - Javascript
  - ESLint
  - Coding Standards
---

## Parallels with Sports?
I’ve often compared learning a new programming language (provided you already know one) to an athlete learning a different sport. The physical fitness of the athlete is still needed for the new sport, similar to how your problem solving and algorithmic skills are applicable to other languages. The athlete will need to learn the rules of the sport, and get used to the equipment needed to play it, whereas a programmer will need to learn differences in syntax and convention, and adapt to the new tools at their disposal. Making use of a coding standard assistant like ESLint is like having a good coach, while it might seem like a pain at times when you have your fundamentals criticized, learning how to do things the right way really does make the acclimatization process much quicker.

## Initial Impressions
So far I am thoroughly impressed with ESLint and IntelliJ, it’s ability to recognize so many different problems and potentials for bugs/errors within my code is amazing. I do wish I could configure it to turn off certain features, but having it catch all my small typing errors, and remind me of important actions like returns and function calls is exactly what I need as a forgetful programmer.

### The Bad
 One general thing I do not like about ESLint is the errors it gives for small spacing discrepancies, for example, I do not like the fact that it tells me to space out my function declarations, I feel that:

``` function(data){} ``` 

Is just as correct as:

``` function (data) { ```

```} ```

Whereas the latter does look much cleaner and easier to read, it often feels like an annoyance that I need to clear up before proceeding with my code. A good parallel here, is a coach telling a player to adjust their stance very slightly, while it is a good practice to have, it can often feel like nagging. I do however understand that a universal coding standard is good as it makes reading and interpreting other people’s code much easier and will try my best to correct these bad habits & adhere to common conventions.

### The Good
One thing that I absolutely love about ESLint is its ability to recognize how functions are implemented and remind you if you have forgotten to meet a particular checkbox. Say I write a utility function that sums an array but forget to invoke it later on in my program, the error being displayed by ESLint will alert me that the function has been declared but not invoked, which will remind me to incorporate it.

A few of my friends who are also enrolled in this course, actually did not finish the first WOD because they forgot to return their answer variables, this is such a small part of the problem-solving process that they overlooked it as a possible source of error. However ESLint would catch this error, and alert the user that the function does not return anything, and will return undefined.
My absolute favorite feature I the reminder for variable usage, I often use similar variable names when coding (usually due to a lack of creativity), and sometimes make a slight yet unintended variation in the name that causes errors. An example of this may be:

``` let totalnums = 1 ```

```While (totalnum != 1) {Do stuff} ```

This function would not work correctly because I declared one variable as totalnums, yet used totalnum in the code. ESLint would create an error on the declaration line, letting me know that the variable was declared but not called throughout the rest of the code. 
These features are very useful, and I would compare them to a coach instructing you that you’re holding the racket wrong, or throwing the ball incorrectly, large fundamental errors that need to be corrected immediately. 

## Conclusions
In conclusion ESLint is a very useful tool when used correctly, it’s like a sports coach, it can set you on the path to success, or irritate you until you switch. I do think the usage of IntelliJ + ESLint is a step forward for us in our JavaScript careers (over using JSFiddle), as it gives us a powerful tool for reinforcing proper programming conventions and standards while still providing agency to the user. 


