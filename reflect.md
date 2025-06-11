# Assignment 02: Reflection on Week 00 and Week 01

As the last two assignments were relatively short, I wanted to make sure that I gave them a good shot. That being said, I think I got pretty close to the given solution. It compiled the way I needed it to, but with a few mistakes/inefficiencies here and there.

The first inefficiency I wanted to address was the way I set the code up for the assignment for week 01. In the solution, the `Integer` object is set up immediately and is set to `null`, then, if needed, replaces the "`null`" object with the smallest value from the array. I constructed the object at the end rather than at the start, and had the construction set up in the conditional statement. Either way, the `Integer` object was constructed in my code, but it's probably more efficient to set it up so that it is set up with a default value.

I also wanted to address was the mistake in leaving the return statements in the if statement. There's not much else to say besides that's not the best practice, as I've learned.

As for `add()`, I think that our set ups were pretty much the same. The only difference is that I added the new value as a part of the for loop rather than outside of it. Again, it's probably more efficient to use the conditional outside, as the code wouldn't have to check the conditional statement every time it iterates through.

One thing I think I did well was commenting. I erred on the side of overexplaining to make sure that my ideas were clear in my code. For the future, however, I think most of these issues could be avoided by paying better attention to what needs to be initialized before continuing on with coding.